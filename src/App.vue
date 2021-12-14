<template>
  <div id="app">
    <myNav :links="links"/>
    <myHeader/>
    <slogan/>
    <channel/>
    <playLists :playLists="playLists"/>
  </div>
</template>

<script>
import myNav from './components/myNav.vue'
import myHeader from './components/myHeader.vue'
import slogan from './components/slogan.vue'
import channel from './components/channel.vue'
import playLists from './components/playLists.vue'


export default {
  name: 'App',
  components: {
    myNav,
    myHeader,
    slogan,
    playLists,
    channel
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
        ],

      playLists : [
        {
          image: "video2-2x.jpg",
          title: "Thighs & glute workout",
          text: "increase your mobility."
        },
        {
          image: "video7-2x.jpg",
          title: "lift, firm & perk out",
          text: "Feel youg again."
        },
        {
          image: "video9-2x.jpg",
          title: "Slim & trim your waist",
          text: "Shed those extra pounds"
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
