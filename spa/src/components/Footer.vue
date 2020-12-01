<template>
  <div class="container">
      <div class="wrapper">
          <div class="wrapper-first">
            <img src="../assets/logo.png" alt="" height="45"  width="45">
            <h3>Vue Project</h3>
          </div>
          <div class="wrapper-second">
            <a href="https://vuejs.org/">Documentations</a>
          </div>

      </div>
  </div>
</template>

<script>

export default {
  components:{

  }
}

</script>

<style scoped>
  .wrapper{
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .wrapper-first{
    display: flex;
    align-items: center;
  }
  .wrapper-second a{
    text-decoration: none;
    color: black;

  }
</style>