<template>
  <div id="app">
    <Title/>
    <Immagine/>
  </div>
</template>

<script>
import Title from './components/titolo.vue'
import Immagine from './components/hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    Immagine
  }
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>
