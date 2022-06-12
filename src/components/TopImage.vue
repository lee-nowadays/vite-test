<template lang="pug">
#top-image
  img(src="@/assets/logo.png")
  //- img(src="../assets/logo2.png")
  //- img(:src="img")
</template>

<!-- <script>
import { ref } from 'vue'
export default {
  setup () {
    const img = ref(new URL('../assets/logo2.png', import.meta.url).href)
    return {
      img
    }
  }
}
</script> -->

<script setup>
import { ref } from 'vue'
// const img = ref(new URL('../assets/logo2.png', import.meta.url).href)
</script>
