<template>
  <div id="app">
    <Navbar/>
    <Main/>
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Main from './components/Main'

export default {
  name: 'App',
  components: {
    Navbar,
    Main
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


.container{
  max-width: 1440px;
  margin: 0 auto;
  padding: 20px;
}
</style>
