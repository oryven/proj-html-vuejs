<template>
  <div id="app">
    <myHeader :links="links"/>
  </div>
</template>

<script>
import myHeader from './components/myHeader.vue'

export default {
  name: 'App',
  components: {
    myHeader
  },
  links: [
      {
        text: "Home",
        url: "*",
      },
      {
        text: "Services",
        url: "*",      
      },
      {
        text: "About",
        url: "*",     
      },
      {
        text: "Videos",
        url: "*",        
      },
      {
        text: "Blog",
        url: "*",    
      },
      {
        text: "Store",
        url: "*",    
      }
   ]
}
 
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
