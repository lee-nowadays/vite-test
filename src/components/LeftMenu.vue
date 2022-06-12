<template lang="pug">
#left-menu
  h1 社團介紹
  table
    tr(v-for="club in clubs")
      td {{ club }}
</template>

<script setup>
import { reactive } from 'vue'

const clubs = reactive([
  '吉他社', '熱舞社', '棒球社', '羽球社', '足球社', '童軍社'
])
</script>

<!-- <script>
import { reactive } from 'vue'
export default {
  setup () {
    const clubs = reactive([
      '吉他社', '熱舞社', '棒球社', '羽球社', '足球社', '童軍社'
    ])
    return {
      clubs
    }
  }
}
</script> -->
