<template>
  <div id="app">
    <HelloWorld />
    <Body />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Body from './components/Body.vue'
import './assets/style.css'
export default {
  name: 'App',
  components: {
    Body,
    HelloWorld
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
