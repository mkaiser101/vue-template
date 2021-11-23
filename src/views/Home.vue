<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <ParalaxIntro/>
    <VerticalDivider/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import ParalaxIntro from '@/components/ParalaxIntro.vue'
import VerticalDivider from '@/components/VerticalDivider.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    ParalaxIntro,
    VerticalDivider
  }
}
</script>
