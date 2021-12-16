<template>
  <section class="slogan">
    <div class="container-slogan">
        <div>
          <h2>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum error, cupiditate esse ea obcaecati accusantium itaque ipsa rerum</h2>
          <div class="rule"></div>
          <p>"Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aliquam cupiditate temporibus voluptatem eum quidem sapiente molestiae molestias inventore cumque. Ea cupiditate dolores atque quo neque eos voluptate corrupti distinctio hic?"</p>
          <button>Buy Avada today <i class="fas fa-chevron-right"></i></button>
        </div> 
    </div>
  </section>
</template>

<script>
export default {
  name: 'slogan2',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.slogan {
    height: 500px;
    background-image: url("../assets/img/banner2-2x.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    .container-slogan {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100%;
        background: rgb(0,0,0);
        background: linear-gradient(0deg, rgba(0,0,0,0.5438550420168067) 60%, rgba(0,0,0,0) 100%);
        div {
            text-align: center;
            color: white;
            width: 50%;
            display: flex;
            flex-direction: column;
            align-items: center;
            .rule {
            margin: 20px 0;
            width: 40px;
            border: 2px solid yellow;
            }
            button {
            background-color: #3230a1;
            border: none;
            border-radius: 20px;
            color: white;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 12px;
            cursor: pointer;
            width: 150px;
            margin: 20px 0;
            }
            button:hover {
            background: crimson;
            }
        }
    }
}

</style>
