<template>
  <div class="container">
      <div class="row">
        <div class="blog-post">
          <img src="https://picsum.photos/300/300" alt="">
          <h2>Saytdagi 1-blog post</h2>
          <p>Create a beautiful blog that fits your style. Choose from a selection of easy-to-use templates – all with flexible layouts and hundreds of background images – or design something new.</p>
          <div class="extra-inform">
            <h5>Author: <span>Elzodxon Sharofaddinov</span></h5>
            <time datetime="2020-01-12">01.12.2020</time>
          </div>
          <Button>Read More</Button>
        </div>
        <div class="blog-post">
          <img src="https://picsum.photos/300/300" alt="">
          <h2>Saytdagi 1-blog post</h2>
          <p>Create a beautiful blog that fits your style. Choose from a selection of easy-to-use templates – all with flexible layouts and hundreds of background images – or design something new.</p>
          <div class="extra-inform">
            <h5>Author: <span>Elzodxon Sharofaddinov</span></h5>
            <time datetime="2020-01-12">01.12.2020</time>
          </div>
          <Button>Read More</Button>
        </div>
        <div class="blog-post">
          <img src="https://picsum.photos/300/300" alt="">
          <h2>Saytdagi 1-blog post</h2>
          <p>Create a beautiful blog that fits your style. Choose from a selection of easy-to-use templates – all with flexible layouts and hundreds of background images – or design something new.</p>
          <div class="extra-inform">
            <h5>Author: <span>Elzodxon Sharofaddinov</span></h5>
            <time datetime="2020-01-12">01.12.2020</time>
          </div>
          <Button>Read More</Button>
        </div>
        <div class="blog-post">
          <img src="https://picsum.photos/300/300" alt="">
          <h2>Saytdagi 1-blog post</h2>
          <p>Create a beautiful blog that fits your style. Choose from a selection of easy-to-use templates – all with flexible layouts and hundreds of background images – or design something new.</p>
          <div class="extra-inform">
            <h6>Author: <span>Elzodxon Sharofaddinov</span></h6>
            <time datetime="2020-01-12">01.12.2020</time>
          </div>
          <Button>Read More</Button>
        </div>
      </div>
  </div>
</template>

<script>

</script>

<style scoped>

  .row{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
  }
  .blog-post{
    padding: 20px;
  }

  .extra-inform{
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  button{
    background:  #42b983;
    border: none;
    color: white;
    font-weight: bold;
    padding: 5px 10px;
  }

  @media screen and (max-width: 650px ){
      .row{
        grid-template-columns: 1fr;
      }
  }

  @media screen and (max-width: 968px ){
    .row{
      grid-template-columns: 1fr 1fr;
    }
  }

  @media screen and (max-width: 1350px ){
    .row{
      grid-template-columns: 1fr 1fr 1fr;
    }
  }
</style>