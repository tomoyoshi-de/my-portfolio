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
          <p>1986年12月8日 / 佐賀県鳥栖市出身</p>
          <p><b>経歴</b></p>
          <p>2017年4月〜<a
            href="https://diffeasy.com"
            target="_blank"
          >株式会社diffeasy</a></p>
          <p>2009年4月〜2017年3月 日本アイ・ビー・エム共同ソリューション・サービス</p>
          <p><b>スキル</b></p>
          <p>プロジェクトマネジメント</p>
          <p>Ruby on Rails / Vue.js / GoogleCloudPlatform / PL/I(COBOL)</p>
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
          <a href="https://note.mu/tomoyoshi_de" target="_blank">note</a>
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
