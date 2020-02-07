<template>
  <div id="test2">
    <div class="search-content">
      <h2>何かしら教えてくれる人達</h2>
    </div>
	<v-layout row wrap>
   <v-flex><v-card
     width="400px"
	 class="ma-3 pa-6"
    >
     <v-img
    	src="https://lh3.googleusercontent.com/proxy/z1ijK-L7Jsg8L1yDJ544E98bymbuJBVTLesl0KKZK1anRqKASwrgkIhtRX6ZUEI4O-tINSaQSlRWdyFZEpGBdw4nqzBm4cmtn14dT-acm73cwBfe"
      ></v-img>
      <v-card-title>エネオス</v-card-title>
      <v-card-subtitle>ガソリンの専門家</v-card-subtitle>
      <v-card-text>私はガソリンに関しては誰より詳しいそして日本のガソリン界においてはトップシェアである。しかしガソリンは間も無くつきそうである。</v-card-text>
    </v-card></v-flex>
    <v-flex><v-card
     width="400px"
	 class="ma-3 pa-6"
    >
      <v-img
    	src="https://www.noe.jxtg-group.co.jp/card_cps/cps_common/images/cps_p01_p06.jpg"
      ></v-img>
      <v-card-title>エネオス</v-card-title>
      <v-card-subtitle>ガソリンの専門家</v-card-subtitle>
      <v-card-text>私はガソリンに関しては誰より詳しいそして日本のガソリン界においてはトップシェアである。しかしガソリンは間も無くつきそうである。</v-card-text>
    </v-card></v-flex>
	</v-layout>
  </div>
</template>
<script lang="ts">
import {
  Component,
  Vue,
} from "nuxt-property-decorator";
@Component
export default class Test2 extends Vue {
  drawer: boolean = true;
}
</script>
