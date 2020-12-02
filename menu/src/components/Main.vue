<template>
  <div class="container back">
      <div class="wrapper">
          <div style="position:absolute; z-index: 2">
            <h1>Полезная еда за несколько минут</h1>
            <h3>Мы облегчаем ежедневное употребление фруктов и овощей, необходимых каждому!</h3>
            <a href="">Оформить заказ</a>
          </div>
        <img src="@/assets/background.jpg" alt="">
      </div>
  </div>
</template>

<script>

</script>

<style scoped>
  .wrapper{
    display: flex;
    justify-content: center;
    align-items: center;
  }
  img{
    position: relative;
    top: 200px;
  }

  h1{
    font-family: Nunito;
    font-size: 50px;
    font-style: normal;
    font-weight: 400;
    line-height: 57px;
    letter-spacing: 0em;
  }

  h3{
    font-size: 22px;
    font-style: normal;
    font-weight: 300;
    line-height: 27px;
    letter-spacing: 0em;
  }

  a{
    height: 60px;
    width: 229px;
    padding: 20px;
    font-size: 16px;
    font-style: normal;
    font-weight: 500;
    line-height: 20px;
    letter-spacing: 0em;
    text-align: center;
    background: #52B030;
    box-shadow: 0px 6px 16px rgba(38, 87, 20, 0.56);
    border-radius: 50px;
    text-decoration: none;
    color: white;
    position: relative;
    top: 50px;
  }
</style>