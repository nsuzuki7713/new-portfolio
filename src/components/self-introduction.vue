<template>
  <v-container grid-list-md text-xs-center>
    <v-layout row wrap>
      <v-flex xs6>
        <v-card dark color="primary">
          <v-avatar :tile="tile" :size="avatarSize" color="grey lighten-4">
            <img src="./../assets/avatar.jpg" alt="avatar">
          </v-avatar>
          <v-card-text
            class="px-0"
          >Webエンジニアとして活動しています。「とにかくやってみる」というスタンス。廃材やジャンク品を用いたDIYなど「利用できるものはなんでも使う！」工夫して乗り越える考え方が得意です。晴れた休日はMacBookを片手に、近所の広い公園で自転車をこいだり散歩をします。</v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs6>
        <v-card dark color="primary">
          <v-card-text class="px-0">
            <div>生年月日</div>
            <div>1993/01/10</div>
            <div>生年月日</div>
            <div>1993/01/10</div>
            <div>生年月日</div>
            <div>1993/01/10</div>
            <div>生年月日</div>
            <div>1993/01/10</div>
            <div>生年月日</div>
            <div>1993/01/10</div>
            <div>生年月日</div>
            <div>1993/01/10</div>
            <div>生年月日</div>
            <div>1993/01/10</div>
          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>
<script>
export default {
  data() {
    return {
      tile: false,
      avatarSize: 200,
    }
  },
}
</script>
