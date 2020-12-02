<template>
  <div class="container">
      <div class="row">
        <ul class="menu-first">
          <li><a href="">Biz haqimizda</a></li>
          <li><a href="">Mahsulotlar</a></li>
          <li><a href="">Yordam</a></li>
        </ul>
        <img src="@/assets/Vector.png" alt="" class="logo">
        <ul class="menu-second">
          <li><a href="">Kirish</a></li>
          <li><a href="">Buyurtmani rasmiylashtirish</a></li>
        </ul>
      </div>
  </div>
</template>

<script>

</script>

<style scoped>
  a{
    text-decoration: none;
    color:rgba(0, 0, 0, 0.49);;
  }

  .row{
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  ul{
    display: flex;
  }
  ul li {
    margin-right: 60px;
    list-style: none;
    font-size: 18px;
  }

  ul li a{
    text-decoration: none;
    color:rgba(0, 0, 0, 0.49);;
  }
</style>