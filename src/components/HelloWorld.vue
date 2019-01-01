<template>
  <v-app light>
    <v-content style="padding-top:0px">
      <section>
        <v-parallax :src="require('@/assets/cover_photo.png')" height="600">
          <v-layout column align-center justify-center class="white--text">
            <!-- <img src="../assets/vuetify.png" alt="Vuetify.js" height="200"> -->
            <h1 class="catch-copy">技術で、日々をもっと楽しく</h1>
            <!-- <div class="subheading mb-3 text-xs-center">Powered by Vuetify</div> -->
            <!-- <v-btn class="blue lighten-2 mt-5" dark large href="/pre-made-themes">Get Started</v-btn> -->
          </v-layout>
        </v-parallax>
      </section>

      <section>
        <v-layout column wrap class="my-5" align-center>
          <v-flex xs12 sm4 class="my-3">
            <div class="text-xs-center">
              <h2 class="headline" style="margin-bottom:15px;">このサイトについて</h2>
              <span class="subheading">このサイトはWebエンジニアである私のポートフォリオです
                <br>自分のスキルや経歴、アウトプットしたものをまとめています
                <br>息抜きがてらに見て頂ければ幸いです
              </span>
            </div>
          </v-flex>
          <v-flex xs12>
            <v-container grid-list-xl>
              <v-layout row wrap align-center>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="icon-font blue--text text--lighten-2">account_box</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">自己紹介</div>
                    </v-card-title>
                    <v-card-text>いい感じの文章を書きたい。ページも遷移させる</v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="icon-font blue--text text--lighten-2">laptop_mac</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline">技術</div>
                    </v-card-title>
                    <v-card-text>いい感じの文章を書きたい。ページも遷移させる</v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="icon-font blue--text text--lighten-2">work</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">職務経歴</div>
                    </v-card-title>
                    <v-card-text>いい感じの文章を書きたい。ページも遷移させる</v-card-text>
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
          </v-flex>
        </v-layout>
      </section>

      <Skill v-if="false"></Skill>
      <SelfIntroduction v-if="false"></SelfIntroduction>
      <TimeLines style="width:800px;margin:0 auto;"></TimeLines>
      <!-- <section>
        <v-parallax :src="require('@/assets/section.jpg')" height="380">
          <v-layout column align-center justify-center>
            <div
              class="headline white--text mb-3 text-xs-center"
            >Web development has never been easier</div>
            <em>Kick-start your application today</em>
            <v-btn class="blue lighten-2 mt-5" dark large href="/pre-made-themes">Get Started</v-btn>
          </v-layout>
        </v-parallax>
      </section>

      <section>
        <v-container grid-list-xl>
          <v-layout row wrap justify-center class="my-5">
            <v-flex xs12 sm4>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Company info</div>
                </v-card-title>
                <v-card-text>
                  Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                  Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                  Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm4 offset-sm1>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Contact us</div>
                </v-card-title>
                <v-card-text>Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.</v-card-text>
                <v-list class="transparent">
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">phone</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>777-867-5309</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">place</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>Chicago, US</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">email</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>john@vuetifyjs.com</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                </v-list>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </section>-->
      <v-footer class="blue darken-2">
        <v-layout row wrap align-center>
          <v-flex xs12>
            <div class="white--text ml-3">© 2018 Naoto Suzuki</div>
          </v-flex>
        </v-layout>
      </v-footer>
    </v-content>
  </v-app>
</template>
<script>
import TimeLines from './time-lines'
import SelfIntroduction from './self-introduction.vue'
import Skill from './skill.vue'
export default {
  components: {
    TimeLines,
    SelfIntroduction,
    Skill,
  },
  data() {
    return {
      title: 'Your Logo',
    }
  },
}
</script>

<style scoped>
.catch-copy {
  color: #2d3842;
  margin-top: 330px;
  font-size: 32px;
}
.icon-font {
  font-size: 80px !important;
}

@media screen and (max-width: 480px) {
  .catch-copy {
    font-size: 26px;
  }
}
</style>
