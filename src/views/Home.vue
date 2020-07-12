<template>
  <div class="home">
    <Header />
    <main>
      <Atozpay />
      <Atozgo />
      <Atozagen />
      <Atozcreate />
      <Testimonies />
    </main>
    <Footer />
    <Launcher />
  </div>
</template>

<script>
// @ is an alias to /src
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'


import Header from '@/components/Header.vue';
import Atozpay from '@/components/Atozpay.vue';
import Atozgo from '@/components/Atozgo.vue';
import Atozagen from '@/components/Atozagen.vue';
import Atozcreate from '@/components/Atozcreate.vue';
import Testimonies from '@/components/Testimonies.vue';
import Footer from '@/components/Footer.vue';
import Launcher from '@/components/Launcher.vue';

export default {
  name: 'Home',
  components: {
    Header,
    Atozpay,
    Atozgo,
    Atozagen,
    Atozcreate,
    Testimonies,
    Footer,
    Launcher
  }
}
</script>
