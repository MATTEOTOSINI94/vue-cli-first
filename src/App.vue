<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <titolo title="La mia prima app con Vue CLI "/>
    <Jumbo/>
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import titolo from './components/title.vue'
import Jumbo from './components/jumbo.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    titolo,
    Jumbo,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>


