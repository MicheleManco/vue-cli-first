<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <title msg="La mia prima app con Vue CLI!"></title>
  </div>
</template>

<script>
import title from './components/title.vue'

export default {
  name: 'App',
  components: {
    title
  }
}
</script>

<style lang="scss">
</style>
