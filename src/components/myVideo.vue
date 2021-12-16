<template>
  <section class="video">
    <div class="container-video">
      <div>
        <div class="play"><i class="fas fa-play"></i></div>
        <h2>Crossfit workout ofthe day</h2>
        <h3>November 15th, 2019</h3>
        <a href="">View all videos <i class="fas fa-long-arrow-alt-right"></i></a>
      </div>
      
    </div>
  </section>
</template>

<script>
export default {
  name: 'video',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.video {
  height: 450px;
  background-image: url("../assets/img/banner14-2x.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  .container-video{
    height: 100%;
    background: rgb(20,27,148);
    background: linear-gradient(98deg, rgba(20,27,148,0.5046393557422969) 40%, rgba(145,20,20,0.4234068627450981) 90%);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
      div {
      display: flex;
      flex-direction: column;
      align-items: center;
      h2 {
        font-size: 30px;
        color: white;
        margin: 20px 0;
      }
      h3{
        color: yellow;
        margin: 20px 0 10px 0;
      }
      a {
        text-decoration: none;
        color: white;
      }
    }
    .play {
      display: flex;
      align-items: center;
      justify-content: center;
      background: white;
      color: teal;
      width: 50px;
      height: 50px;
      border-radius: 100%;
    }
  }
}
</style>
