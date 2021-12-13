<template>
  <nav>
      <div class="container">
          <img src="../assets/img/logo.png" alt="">
        <div>
            <ul>
                <li v-for="link, i in links" :key="i">{{link.text}} <span class="new" v-if="link.badge">{{link.badge}}</span></li>
            </ul>
        </div>
        <div class="buttons">
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
        ul li {
            display: inline-block;
            list-style: none;
            margin-left: 20px ;
        }
        .buttons{
            width: 30%;
            display: flex;
            justify-content: space-around;
        }
        .new {
            background: yellow;
            width: 40px;
            font-size: 12px;
            padding: 5px;
        }
    }
}

</style>
