<template>
  <div class="home">
    <Header></Header>
    <Slideshow></Slideshow>
    <Atozpay></Atozpay>
    <Atozgo></Atozgo>
    <Atozagen></Atozagen>
    <Atozcreate></Atozcreate>
    <Testimonies></Testimonies>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'


import Header from '@/components/Header.vue';
import Slideshow from '@/components/Slideshow.vue';
import Atozpay from '@/components/Atozpay.vue';
import Atozgo from '@/components/Atozgo.vue';
import Atozagen from '@/components/Atozagen.vue';
import Atozcreate from '@/components/Atozcreate.vue';
import Testimonies from '@/components/Testimonies.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'Home',
  components: {
    Header,
    Slideshow,
    Atozpay,
    Atozgo,
    Atozagen,
    Atozcreate,
    Testimonies,
    Footer
  }
}
</script>
