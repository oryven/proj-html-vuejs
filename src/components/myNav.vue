<template>
  <nav>
      <div class="container">
          <img src="../assets/img/logo.png" alt="">
        <div>
            <ul>
                <li v-for="link, i in links" :key="i"><a href="">{{link.text}}</a> <span class="new" v-if="link.badge"> {{link.badge}}</span></li>
            </ul>
        </div>
        <div class="buttons">
            <button>schedule a workout</button>
            <a href=""><i class="fas fa-shopping-cart"></i></a>
            <a href=""><i class="fas fa-search"></i></a>
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
        ul {
            display: flex;
            align-items: center;
        }
        ul li {
            display: flex;
            align-items: center;
            list-style: none;
            margin-left: 20px ;
            a {
                text-decoration: none ;
                color: gray;
            }
            a:hover {
                color: white;
            }
        }
        .buttons{
            width: 30%;
            display: flex;
            align-items: center;
            justify-content: space-around;
            button {
                background-color: #3230a1; /* Green */
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
                background: crimson;
            }
        }
        .new {
            text-align: center;
            display: inline-block;
            background: yellow;
            width: 40px;
            font-size: 12px;
            border-radius: 2px;
            height: 20px;
            margin-left: 10px;
        }
    }
    a i {
        color: grey;
    }
    a i:hover {
        color:white
    }
}

</style>
