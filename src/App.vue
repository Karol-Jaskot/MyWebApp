<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Karol Jaskot"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  theme: {
    dark: true
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
  background:  #333;
  color: white;
  min-width: 100%;
  min-height: 2000px;
  margin: 0px;
  padding: 0px;
}
</style>
