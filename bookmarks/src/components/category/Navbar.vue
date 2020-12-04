<template>
  <div>
    <ul>
<!--      <li>-->
<!--        <router-link to="/">00. All</router-link>-->
<!--      </li>-->
      <li>
        <router-link to="/">All</router-link>
      </li>
      <li>
        <router-link to="/category/inspiration">Inspiration</router-link>
      </li>
      <li>
        <router-link to="/category/empty">Empty</router-link>
      </li>

    </ul>
  </div>
</template>

<script>

</script>

<style scoped>

  ul {
    display: flex;
    justify-content: space-around;
  }
  ul li{
    list-style: none;
  }
</style>