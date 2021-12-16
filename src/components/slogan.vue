<template>
  <section class="slogan">
    <div class="container-services">
      <div id="img1" class="services">
        <div class="container-text">
          <div class="rule"></div>
          <h3>Crossfit workout</h3>
          <h4>push your limits</h4>
        </div>
      </div>
      <div id="img2" class="services">
        <div class="container-text">
          <div class="rule"></div>
          <h3>New gym apparel</h3>
          <h4>push your limits</h4>
        </div>
      </div>
      <div id="img3" class="services">
        <div class="container-text">
          <div class="rule"></div>
          <h3>Team training</h3>
          <h4>push your limits</h4>
        </div>
      </div>
    </div>

    <div class="text">
      <p>"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic dolor recusandae sunt neque! Repudiandae alias laudantium eius exercitationem molestias necessitatibus, aspernatur harum saepe nam at. Earum sapiente aliquid itaque autem?"</p>
      <div class="rule"></div>
      <div class="container-avatar">
        <div class="avatar">
          <img src="../assets/img/avatar-1-2x.jpg" alt="">
        </div>
        <span>Brad Jonson </span>
        <span> Las vegas</span>
      </div>
    </div>
  </section>
</template>

<script>

export default {
  name: 'slogan',
 
}
</script>

<style lang="scss">
.slogan{
  background: rgb(2,0,36);
  background: linear-gradient(126deg, rgba(2,0,36,1) 0%, rgba(9,11,121,1) 48%, rgba(255,0,0,1) 100%);
  height: 600px;
  .container-services {
    width: 80%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    margin-bottom: 70px;
    #img1 {
      background-image: url("../assets/img/service6-2x.jpg");
    }
    #img2 {
      background-image: url("../assets/img/box1-2x.jpg");
    }
    #img3 {
      background-image: url("../assets/img/box3-2x.jpg");
    }
    .services {
      background-size: cover;
      background-repeat: no-repeat;
      width: 300px;
      height: 300px;
      margin-top: -50px;
      filter: brightness(80%);
      border-radius: 0 0 10% 0;
      h3 {
        color: white;
        margin-top:20px;
      }
      h4 {
        color: yellow;
      }
    }
    .container-text {
      height: 100%;
      padding: 200px 0 20px 20px;
      background: rgb(0,0,0);
      background: linear-gradient(0deg, rgba(0,0,0,0.34217436974789917) 40%, rgba(255,0,0,0) 90%);
      border-radius: 0 0 10% 0;
      .rule {
      width: 40px;
      border: 2px solid white;
      }
    }
  }
  .text {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    width: 50%;
    margin: 0 auto;
    color: white;
    p {
      font-size: 22px;
    }
    .rule {
      width: 40px;
      border: 2px solid yellow;
      margin: 20px 0;
    }
    .container-avatar {
      display: flex;
      align-items: center;
      span {
        margin-right: 5px;
      }
    }
    .avatar {
      width: 50px;
      margin-right: 20px;
      img {
        width: 100%;
        border-radius: 100%;
      }
    }
  }
}

</style>