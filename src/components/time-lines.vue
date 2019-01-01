<template>
  <v-timeline>
    <v-timeline-item color="purple lighten-2" fill-dot right small>
      <span slot="opposite">2018/10〜</span>
      <v-card>
        <v-card-title class="purple lighten-2">
          <div class="white--text font-weight-light fs20">AI自動採点システム開発</div>
        </v-card-title>
        <v-container>
          <v-layout>
            <v-flex xs12>
              <div class="fs20">概要</div>
              <span>
                AIによる評価システムプロジェクトです。
                主に管理画面や受検画面の開発をしております。
                プランニングチームが別にあり、そこで企画された内容に沿って、開発を進めています。
              </span>
              <div class="fs20 mtop-8">担当工程</div>
              <v-chip outline color="primary">設計</v-chip>
              <v-chip outline color="primary">実装</v-chip>
              <v-chip outline color="primary">テスト</v-chip>
              <div class="fs20 mtop-8">経験技術</div>
              <v-chip outline color="primary">HTML・CSS</v-chip>
              <v-chip outline color="primary">JavaScript</v-chip>
              <v-chip outline color="primary">TypeScript</v-chip>
              <v-chip outline color="primary">Vue.js</v-chip>
              <v-chip outline color="primary">Angular</v-chip>
              <v-chip outline color="primary">Ruby on Rails</v-chip>
              <v-chip outline color="primary">Go</v-chip>
            </v-flex>
          </v-layout>
        </v-container>
      </v-card>
    </v-timeline-item>

    <v-timeline-item color="amber lighten-1" fill-dot left small>
      <span slot="opposite">2017/12〜2018/09</span>
      <v-card>
        <v-card-title class="amber lighten-1 justify-end">
          <div class="white--text font-weight-light fs20">保育支援システム開発</div>
        </v-card-title>
        <v-container>
          <v-layout>
            <v-flex xs12>
              <div class="fs20">概要</div>
              <span>
                保育園向けの自社プロジェクトです。
                企画、要件、設計、開発、テスト、運用の全ての工程を１人で携わりました。
              </span>
              <div class="fs20 mtop-8">担当工程</div>
              <v-chip outline color="primary">企画</v-chip>
              <v-chip outline color="primary">要件定義</v-chip>
              <v-chip outline color="primary">設計</v-chip>
              <v-chip outline color="primary">実装</v-chip>
              <v-chip outline color="primary">テスト</v-chip>
              <div class="fs20 mtop-8">経験技術</div>
              <v-chip outline color="primary">HTML・CSS</v-chip>
              <v-chip outline color="primary">JavaScript</v-chip>
              <v-chip outline color="primary">Angular.js</v-chip>
              <v-chip outline color="primary">PHP</v-chip>
            </v-flex>
          </v-layout>
        </v-container>
      </v-card>
    </v-timeline-item>

    <v-timeline-item color="cyan lighten-1" fill-dot right>
      <v-card>
        <v-card-title class="cyan lighten-1">
          <v-icon class="mr-3" dark size="42">mdi-email-outline</v-icon>
          <h2 class="display-1 white--text font-weight-light">Title 3</h2>
        </v-card-title>
        <v-container>
          <v-layout>
            <v-flex
              v-for="n in 3"
              :key="n"
              xs4
            >Lorem ipsum dolor sit amet, no nam oblique veritus no nam oblique.</v-flex>
          </v-layout>
        </v-container>
      </v-card>
    </v-timeline-item>

    <v-timeline-item color="red lighten-1" fill-dot left small>
      <v-card>
        <v-card-title class="red lighten-1 justify-end">
          <h2 class="display-1 mr-3 white--text font-weight-light">Title 4</h2>
          <v-icon dark size="42">mdi-account-multiple-outline</v-icon>
        </v-card-title>
        <v-container>
          <v-layout>
            <v-flex xs2>
              <v-icon size="64">mdi-server-network</v-icon>
            </v-flex>
            <v-flex
              xs10
            >Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit, an vim zril disputando voluptatibus.</v-flex>
          </v-layout>
        </v-container>
      </v-card>
    </v-timeline-item>

    <v-timeline-item color="green lighten-1" fill-dot right>
      <v-card>
        <v-card-title class="green lighten-1">
          <v-icon class="mr-3" dark size="42">mdi-phone-in-talk</v-icon>
          <h2 class="display-1 white--text font-weight-light">Title 5</h2>
        </v-card-title>
        <v-container>
          <v-layout>
            <v-flex>Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit, an vim zril disputando voluptatibus, vix an salutandi sententiae.</v-flex>
          </v-layout>
        </v-container>
      </v-card>
    </v-timeline-item>
  </v-timeline>
</template>
