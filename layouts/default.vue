<template>
  <v-app>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
    <v-navigation-drawer
      v-model="drawer"
      fixed
      app
      right
    >
      <v-list>
        <v-list-tile>
          <v-list-tile-action>
            <v-icon @click="drawer = !drawer">clear</v-icon>
          </v-list-tile-action>
        </v-list-tile>

        <v-list-tile>
          <v-list-tile-action>
            <v-icon @click="drawer = !drawer">apps</v-icon>
          </v-list-tile-action>
          <v-list-tile-content>ホーム
          </v-list-tile-content>
        </v-list-tile>

        <v-list-tile>
          <v-list-tile-action>
            <v-icon>bubble_chart</v-icon>
          </v-list-tile-action>
          <v-list-tile-content>
            <a href="https://diffeasy.com" target="_blank">株式会社diffeasy</a>
          </v-list-tile-content>
        </v-list-tile>
        <v-list-tile>
          <v-list-tile-action>
            <v-icon>bubble_chart</v-icon>
          </v-list-tile-action>
          <v-list-tile-content>
            <a href="https://kojo-shin.com/lp" target="_blank">大会運営向上心〜KOJO-SHiN〜</a>
          </v-list-tile-content>
        </v-list-tile>

      </v-list>
    </v-navigation-drawer>
    <v-toolbar
      apps
    >
      <v-toolbar-title v-text="title" />
      <v-spacer></v-spacer>
      <v-toolbar-side-icon @click="drawer = !drawer" />
    </v-toolbar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>

    <v-footer
      app
    >
      <span class="ml-2">&copy; 2019 Tomoyoshi Miyahara</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      drawer: false,
      title: 'Tomoyoshi Portfolio'
    }
  }
}
</script>
