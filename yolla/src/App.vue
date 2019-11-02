<template>
  <div id="app">
    
    <Header class="Header" />
    <AccaountBody class="AccaountBody" />
    <BackToTop class="BackToTop" />

        <Carosel class="Carosel" />

        <Footer class="Footer" />


       


    
  </div>


</template>

<script>
import Header from './components/Header.vue'
import AccaountBody from './components/AccaountBody.vue'
import BackToTop from './components/BackToTop.vue'

import Carosel from './components/Carosel.vue'

import Footer from './components/Footer.vue'


 


export default {
  name: 'app',
  components: {
    
   Header,
   AccaountBody,
   BackToTop,
   Carosel,
   Footer

     
    

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0 auto;
  background-color: rgb(197, 197, 197);
}

</style>

