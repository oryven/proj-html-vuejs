<template>
  <div id="app">
    <myNav :links="links"/>
    <myHeader/>
  </div>
</template>

<script>
import myNav from './components/myNav.vue'
import myHeader from './components/myHeader.vue'

export default {
  name: 'App',
  components: {
    myNav,
    myHeader
  },

  data(){
    return {
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
            badge: "new"
          }
        ]
    }
  }
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
