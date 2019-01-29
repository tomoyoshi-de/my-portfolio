<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <div class="text-xs-center">
        <vuetify-logo />
      </div>
      <v-card>
        <v-card-title class="headline mt-4">宮原 智新
          <span class="subheading ml-2">（みやはら ともよし）</span>
        </v-card-title>
        <v-card-text>          

          <p>2017年4月〜<a
            href="https://diffeasy.com"
            target="_blank"
          >株式会社diffeasy</a></p>
          <hr class="my-3">
          <v-btn fab small>
            <a href="https://twitter.com/tomoyoshi_de" target="_blank">
              <v-icon>fab fa-twitter</v-icon>
            </a>
          </v-btn>
          <v-btn fab small>
            <a href="https://www.facebook.com/tomoyoshi.miyahara" target="_blank">
              <v-icon>fab fa-facebook-f</v-icon>
            </a>
          </v-btn>
        </v-card-text>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    VuetifyLogo
  }
}
</script>
