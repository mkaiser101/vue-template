<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <ParalaxIntro/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import ParalaxIntro from '@/components/ParalaxIntro.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    ParalaxIntro
  }
}
</script>
