<template>
  <NativeLabel />
  <AriaLabel />
</template>

<script>
import NativeLabel from './components/NativeLabel.vue'
import AriaLabel from './components/AriaLabel.vue'

export default {
  name: 'App',
  components: {
    NativeLabel,
    AriaLabel
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
