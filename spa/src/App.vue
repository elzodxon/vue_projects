<template>
  <div id="app">
    <Navbar/>
    <router-view/>
  </div>
</template>

<script>
  import Navbar from './components/Navbar'
  export default {
    name: 'App',
    components:{
      Navbar
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
}
.container{
  max-width: 1440px;
  margin: 0 auto;
}
</style>
