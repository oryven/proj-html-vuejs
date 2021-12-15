<template>

    <section class="container-playLists">
      <div class="text-playLists">
        <div>Featured Playlists</div>
        <div>View all videos <i class="fas fa-chevron-right"></i></div>
      </div>
      
      <div class="row">
        <div class="item" v-for="element, i in playLists" :key="i">
          <img :src="require(`../assets/img/${element.image}`)" :alt="element.title">
          <h5>{{element.title}}</h5>
          <div>{{element.text}}</div>
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
  }
  img {
  width: 300px ;
  border-radius: 0 0 10% 0;
  }
}

</style>