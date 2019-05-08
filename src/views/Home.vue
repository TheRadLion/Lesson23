<template>
  <div class="home">
    <mainheader></mainheader>
    <mainbody></mainbody>
    <mainfooter></mainfooter>
  </div>
</template>

<script>
import mainheader from "@/components/mainheader.vue"
import mainbody from "@/components/mainbody.vue"
import mainfooter from "@/components/mainfooter.vue"

export default {
  name: 'home',
  components: {
    mainheader,
    mainbody,
    mainfooter
  }
};
</script>
