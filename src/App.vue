<template>
  <div id="app">
    <CesiumScene />
  </div>
</template>

<script>
import CesiumScene from './components/CesiumScene.vue'

export default {
  name: 'App',
  components: {
    CesiumScene
  }
}
</script>

<style scoped>
html, body, #app {
  height: 100%;
  width: 100%;
  margin: 0;
  padding: 0;
  overflow: hidden;
}
</style>
