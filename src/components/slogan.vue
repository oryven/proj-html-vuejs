<template>
  <section class="slogan">
    <div class="container-services">
      <div id="img1" class="services">
        <div class="container-text">
          <div class="rule"></div>
          <h5>crossfit workout</h5>
          <div>push your limits</div>
        </div>
      </div>
      <div id="img2" class="services">
        <div class="container-text">
          <div class="rule"></div>
          <h5>crossfit workout</h5>
          <div>push your limits</div>
        </div>
      </div>
      <div id="img3" class="services">
        <div class="container-text">
          <div class="rule"></div>
          <h5>crossfit workout</h5>
          <div>push your limits</div>
        </div>
      </div>
    </div>

    <div class="text">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic dolor recusandae sunt neque! Repudiandae alias laudantium eius exercitationem molestias necessitatibus, aspernatur harum saepe nam at. Earum sapiente aliquid itaque autem?</p>
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
  height: 500px;
  .container-services {
    width: 80%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
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
    }
    .container-text {
      padding: 200px 0 0 20px;
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
    .rule {
      width: 40px;
      border: 2px solid yellow;
    }
    .container-avatar {
      display: flex;
      align-items: center;
    }
    .avatar {
      width: 50px;
      img {
        width: 100%;
        border-radius: 100%;
      }
    }
  }
}

</style>