<template>
  <div id="app">
    <HeroJumbotron/>
    <firstTitle msg="La prima app con Vue Cli"/>
    
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import firstTitle from './components/title.vue'
import HeroJumbotron from './components/HeroJumbotron.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    firstTitle,
    HeroJumbotron
    
    
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
