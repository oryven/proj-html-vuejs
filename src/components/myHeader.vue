<template>
  <header>
      <div class="container">
          <img src="../assets/img/logo.png" alt="">
        <nav>
            <ul>
                <li v-for="link, i in links" :key="i">{{links.text}}</li>
            </ul>
        <i class="fas fa-phone"></i>
      </nav>
      </div> 
  </header>
</template>

<script>

export default {
  name: 'myHeader',
  props: {
   links: Array,
  },
}
</script>

<style lang="scss">
header{
    height: 80px;
    background: black;
    color: grey;
    .container {
        width: 80%;
        margin: 0 auto;
    }
}

</style>
