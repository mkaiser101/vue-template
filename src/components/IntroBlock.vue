<template>
    <v-app>
      <v-img
      max-height="700"
      :src="image1.src"
      ></v-img>
    </v-app>
</template>


<script>
  export default {
    data () {
      return {
        image1: {
          src: require('../assets/yoga_mountain.jpeg')
        },
        image2: {
          src: require('../assets/yoga_duncans_knob.png')
        }
      }
    }
  }
</script>