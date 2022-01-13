<template>
  <div class="home">
    <HelloWorld msg="Welcome to this Website"/>
    <img alt="JSLogo" src="../assets/logo3.png">
    <img alt="Vuelogo" src="../assets/logo.png">
    <img alt="NodeLogo" src="../assets/logo2.png">
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
<style scoped>
img {
  margin-left: 60px;
}
</style>
