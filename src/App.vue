<template>
  <div id="app">
    <img alt="scimmia che sorride" src="./assets/scimmiasorridente.jpg">
    <firstTitle msg="La prima app con Vue Cli"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import firstTitle from './components/title.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    firstTitle,
    
    
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
