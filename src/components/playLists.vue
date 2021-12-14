<template>
    <section class="playLists">
      <div v-for="element, i in playLists" :key="i">
        <img :src="require(`../assets/img/${element.image}`)" :alt="element.title">
        <h5>{{element.title}}</h5>
        <div >{{element.text}}</div>
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


</style>