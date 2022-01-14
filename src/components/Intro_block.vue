<template>
    <v-app>
   <v-carousel>
      <v-carousel-item
        v-for="(item,i) in items"
        :key="i"
        :src="item.src"
      ></v-carousel-item>
    </v-carousel>
    </v-app>
</template>


<script>
  export default {
    data () {
      return {
        items: [
          {
            src: require('../assets/logo.png')
          },
          {
            src: require('../assets/distortedtree.jpg')
          },
          {
            src: require('../assets/logo.png')
          },
          {
            src: require('../assets/distortedtree.jpg')
          }
        ]
      }
    }
  }
</script>