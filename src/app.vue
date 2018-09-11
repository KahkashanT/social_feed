
<template>
<div>
  <div>
    <navbar></navbar>
   </div>
    
    <div>
    <textbar></textbar>
    </div>

    <div>
    <detail></detail>
    
    </div>

    <div>
    <wallpaper></wallpaper>
    </div>

    <div>
    <counter></counter>
    </div>

    <div>
    <emoji></emoji>
    </div>

    <div>
    <downNav></downNav>
    </div>
</div>
</template>

<script>

import  navbar from './nav.vue';
import  textbar from './textbar.vue';
import  detail from './detail.vue';
import  wallpaper from './wallpaper.vue';
import  counter from './counter.vue';
import  emoji from './emoji.vue';
import  downNav from './downNav.vue';
export default {
  components:{
navbar,
textbar,
detail,
wallpaper,
counter,
emoji,
downNav
},
}
</script>

