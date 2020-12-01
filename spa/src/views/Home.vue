<template>
  <div class="home">
    <Main/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Main from "../components/Main";
import Footer from "../components/Footer";
export default {
  name: 'Home',
  components: {
    Footer,
    Main
  }
}
</script>
