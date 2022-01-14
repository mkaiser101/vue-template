<template>
  <div class="home">
    <IntroBlock/>
    <ParalaxIntro/>
    <Test/>
    <VerticalDivider/>
    <img alt="Vue logo" src="../assets/logo.png">
  </div>
</template>

<script>
// @ is an alias to /src

import ParalaxIntro from '@/components/ParalaxIntro.vue'
import VerticalDivider from '@/components/VerticalDivider.vue'
import Test from '@/components/Test.vue'
import IntroBlock from '@/components/IntroBlock.vue'

export default {
  name: 'Home',
  components: {
    ParalaxIntro,
    VerticalDivider,
    Test,
    IntroBlock
  }
}
</script>
