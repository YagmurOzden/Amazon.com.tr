<template>
    <div class="login">
        <Header />
        <AccaountBody />
        <BackToTop/>
        <Footer />
    </div>
</template>

<script>
import Header from '@/components/Header.vue'
import AccaountBody from '@/components/AccaountBody.vue'
import BackToTop from '@/components/BackToTop.vue'
import Footer from '@/components/Footer.vue'

export default {
    name:'login',
    components:{
        Header,
          AccaountBody,
        BackToTop,
      
        Footer
    }
}
</script>