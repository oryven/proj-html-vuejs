<template>
  <section class="slogan">
    <div class="container-services">
      <div class="services1">
        <!-- <img src="../assets/img/service6-2x.jpg" alt=""> -->
        <div class="container-text">
          <h5>crossfit workout</h5>
          <div>push your limits</div>
        </div>
      </div>
      <div class="services2">
        <!-- <img src="../assets/img/box1-2x.jpg" alt=""> -->
        <div class="container-text">
          <h5>crossfit workout</h5>
          <div>push your limits</div>
        </div>
      </div>
      <div class="services3">
        <!-- <img src="../assets/img/box3-2x.jpg" alt=""> -->
        <div class="container-text">
          <h5>crossfit workout</h5>
          <div>push your limits</div>
        </div>
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
  height: 400px;
  .container-services {
    width: 80%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    .services1 {
      background-image: url("../assets/img/service6-2x.jpg");
      background-size: cover;
      background-repeat: no-repeat;
      width: 300px;
      margin-top: -50px;
    }
    .services2 {
      background-image: url("../assets/img/box1-2x.jpg");
      background-size: cover;
      background-repeat: no-repeat;
      filter: grayscale(1);
      width: 300px;
      margin-top: -50px;
    }
    .services3 {
      background-image: url("../assets/img/box3-2x.jpg");
      background-size: cover;
      background-repeat: no-repeat;
      width: 300px;
      height: 300px;
      margin-top: -50px;
    }
    .container-text {
      padding-top: 100px;
    }
  }
 
}

</style>