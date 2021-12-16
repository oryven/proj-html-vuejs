<template>
  <div class="container-channel">
    <div class="video">
        <div class="play"><i class="fas fa-play"></i></div>
    </div>
    <div class="text-channel">
        <h4>Tune up your workouts</h4>
        <h2>The best health &amp; fitness <br> advice online</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Maxime aliquid rerum culpa voluptates error.</p>
        <button><i class="fab fa-youtube"></i> Visit my youtube channel</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'channel',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.container-channel {
display: flex;
margin-bottom: 50px;
.video {
    background-image: url("../assets/img/service15-2x.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    width: 45%;
    height: 500px;
    margin-top: -30px;
    display: flex;
    justify-content: center;
    align-items: center;
    filter: brightness(80%);
    border-radius: 0 0 5% 0;
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
    .text-channel {
      width: 45%;
      padding: 80px 0 80px 80px;
      h4 {
        color:rgb(36, 121, 201);
        margin: 0px 0 20px 0;
      }
      p {
        color: gray;
        margin: 20px 0;
      }
      button {
        background-color: red; /* Green */
        border: none;
        border-radius: 20px;
        color: white;
        padding: 10px 20px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 12px;
        cursor: pointer;
      }
      button:hover {
        background: white;
        color: black;
        border: 2px solid red;
      }
    }    
}

</style>
