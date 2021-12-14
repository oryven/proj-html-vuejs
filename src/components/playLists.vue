<template>
    <section class="playLists">
      <img :src="require(`../assets/img/${playLists.image}`)" :alt="playLists.title">
      <h5 >{{playLists.title}}</h5>
      <div >{{playLists.text}}</div>
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


</style>