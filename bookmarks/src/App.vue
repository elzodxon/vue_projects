<template>
  <div id="app">
    <Header/>
    <router-view/>

    <Footer/>

  </div>
</template>
<script>
  import Header from '@/components/header/Header'
  import Footer from '@/components/footer/Footer'
  export default {

    components: {Footer, Header}
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
</style>
