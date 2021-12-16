<template>

    <section class="container-playLists">
      <div class="text-playLists">
        <div>Featured Playlists</div>
        <a href="">View all videos <i class="fas fa-chevron-right"></i></a>
      </div>
      
      <div class="row">
        <div class="item" v-for="element, i in playLists" :key="i">
          <img :src="require(`../assets/img/${element.image}`)" :alt="element.title">
          <h5>{{element.title}}</h5>
          <h6>{{element.text}}</h6>
        </div>
      </div>
    </section>
</template>

<script>

export default {
  name: 'playLists',
    props: {
    playLists: Array,
  }
}
</script>

<style lang="scss">
.container-playLists {
  width: 80%;
  margin: 0 auto;
  .row, .text-playLists {
    display: flex;
    justify-content: space-between;
    text-align: center;
    margin: 20px 0;
    a {
      text-decoration: none;
      color: grey;
      font-size: 12px;
    }
    h5 {
      margin: 20px 0 10px 0;
    }
    h6 {
      color:rgb(26, 84, 243);
    }
  }
  img {
  width: 300px ;
  border-radius: 0 0 10% 0;
  }
}

</style>