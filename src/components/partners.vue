<template>
  <section class="partners">
      <div class="container-partens">
          <div>
            <img src="../assets/img/sponsor-1-2x.png" alt="">
            <div class="rule"></div>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ipsam soluta sit inventore tempora sunt tempore expedita</p>
            <a href="*">Learn about crossfit <i class="fas fa-chevron-right"></i></a>
          </div>
          <div>
            <img src="../assets/img/sponsor-2-2x.png" alt="">
            <div class="rule"></div>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ipsam soluta sit inventore tempora sunt tempore expedita</p>
            <a href="*">Learn about crossfit <i class="fas fa-chevron-right"></i></a>
          </div>
          <div>
            <img src="../assets/img/sponsor-3-2x.png" alt="">
            <div class="rule"></div>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ipsam soluta sit inventore tempora sunt tempore expedita</p>
            <a href="*">Learn about crossfit <i class="fas fa-chevron-right"></i></a>
          </div>
          <div>
            <img src="../assets/img/sponsor-4-2x.png" alt=""> 
            <div class="rule"></div> 
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ipsam soluta sit inventore tempora sunt tempore expedita</p>  
            <a href="*">Learn about crossfit <i class="fas fa-chevron-right"></i></a>     
          </div>
      </div>
    
  </section>
</template>

<script>
export default {
  name: 'partners',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container-partens {
    width: 80%;
    margin: 100px auto;
    display: flex;
    div {
        width: 25%;
        text-align: center;
        color: grey;
        a {
          text-decoration: none;
          color: rgb(97, 96, 96);
        }
        p {
          margin: 20px 0;
        }
    }

    img {
        width: 200px;
    }
}

</style>
