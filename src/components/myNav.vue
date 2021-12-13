<template>
  <nav>
      <div class="container">
          <img src="../assets/img/logo.png" alt="">
        <div>
            <ul>
                <li v-for="link, i in links" :key="i">{{links.text}}</li>
            </ul>
        </div>
        <div class="buttons">
            <div class="new">new</div>
            <button>schedule a workout</button>
            <i class="fas fa-shopping-cart"></i>
            <i class="fas fa-search"></i>
        </div>
      </div> 
  </nav>
</template>

<script>

export default {
  name: 'myNav',
  props: {
   links: Array,
  },
}
</script>

<style lang="scss">
nav{
    display: flex;
    height: 80px;
    background: black;
    color: grey;
    .container {
        display: flex;
        align-items: center;
        justify-content: space-between;
        width: 80%;
        margin: 0 auto;
        .buttons{
            width: 30%;
            display: flex;
            justify-content: space-around;
        }
        .new {
             display: flex;
            align-items: center;
            justify-content: center;
            background: yellow;
            width: 40px;
            font-size: 12px;
        }
    }
}

</style>
