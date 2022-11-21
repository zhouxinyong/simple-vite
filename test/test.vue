<template>
  <div>{{ msg }}</div>
</template>

<script>
import { log } from './util.js'
export default {
  data() {
    return {
      msg: 'vite 0.7'
    }
  },
  mounted() {
    log()
  }
}
</script>

<style scoped>
div {
  color: red;
}
</style>