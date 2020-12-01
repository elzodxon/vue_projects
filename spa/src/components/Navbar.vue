<template>
  <div>
    <div class="container">
      <h1>Elzodxon</h1>
      <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link> |
        <router-link to="/blog">Blog</router-link> |
        <router-link to="/portfolio">Portfolio</router-link>
      </div>
    </div>

  </div>
</template>

<script>

</script>

<style scoped>

.container{
  display: flex;
  align-items: center;
  justify-content: space-between;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>