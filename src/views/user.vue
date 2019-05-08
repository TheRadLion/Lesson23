<template>
  <div class="about">
    <userheader></userheader>
    <userpage></userpage>
    <mainfooter></mainfooter>
  </div>
</template>

<script>

import userheader from "@/components/userheader.vue"
import userpage from "@/components/userpage.vue"
import mainfooter from "@/components/mainfooter.vue"

export default {
  name: "user",
  components: {
    userheader,
    userpage,
    mainfooter
  }
};

</script>


