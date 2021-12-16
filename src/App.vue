<template>
  <div id="app">
    <myNav :links="links"/>
    <myHeader/>
    <slogan/>
    <channel/>
    <playLists :playLists="playLists"/>
    <mailingList/>
    <services/>
    <myArticle :articles="articles"/>
    <slogan2/>
    <partners/>
    <myVideo/>
    <myFooter :linksFooter="linksFooter"/>
  </div>
</template>

<script>
import myNav from './components/myNav.vue'
import myHeader from './components/myHeader.vue'
import slogan from './components/slogan.vue'
import channel from './components/channel.vue'
import playLists from './components/playLists.vue'
import mailingList from './components/mailingList.vue'
import services from './components/services.vue'
import myArticle from './components/myArticle.vue'
import slogan2 from './components/slogan2.vue'
import partners from './components/partners.vue'
import myVideo from './components/myVideo.vue'
import myFooter from './components/myFooter.vue'

export default {
  name: 'App',
  components: {
    myNav,
    myHeader,
    slogan,
    playLists,
    channel,
    mailingList,
    services,
    myArticle,
    slogan2,
    partners,
    myVideo,
    myFooter
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

      playLists: [
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
      ],

      articles: [
        {
          image: "blog4-2x-400x258.jpg",
          title: "The best protein shake",
          text: "By admin | Novembre 15 2021.."
        },
        {
          image: "blog1-2x-400x258.jpg",
          title: "Ultimate cardio workout",
          text: "By admin | Novembre 15 2021."
        },
        {
          image: "blog3-2x.jpg",
          title: "New juice available now",
          text: "By admin | Novembre 15 2021."
        }
      ],

      linksFooter: [
          {
            text: "The best protein shake",
            url: "*",
          },
          {
            text: "ultimate cardio workout",
            url: "*",      
          },
          {
            text: "new juices avabible now",
            url: "*",     
          },
          {
            text: "Tips to find training parteners ",
            url: "*",        
          },
          {
            text: "20 best healty recipes",
            url: "*",    
          }
        ]
    }
  }
}
 
</script>

<style lang="scss">
#app {
  font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
