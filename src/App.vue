<template>
<div id="app">
      <AvadaHeader/>
      <AvadaFooter/>
    </div>
  </template>
  
  <script>
  import AvadaHeader from './components/AvadaHeader.vue'
  import AvadaFooter from './components/AvadaFooter.vue'
  
  export default {
    name: 'App',
    components: {
      AvadaHeader,
      AvadaFooter
    }
  }
</script>

<style lang="scss" scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
