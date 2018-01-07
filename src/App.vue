<template>
  <div id="app">
    <my-head/>
    <router-view/>
  </div>
</template>

<script>
  import MyHead from './components/MyHead'

  export default {
    components: {MyHead},
    name: 'app'
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    /*margin-top: 60px;*/
  }
</style>
