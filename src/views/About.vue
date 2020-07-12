<template>
  <div class="about">
     <Header />
    <main>
     <AtozpayAbout />
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
import AtozpayAbout from '@/components/AtozpayAbout';
import Footer from '@/components/Footer.vue';
import Launcher from '@/components/Launcher.vue';


export default {
  name: 'About',
  components: {
    Header,
    AtozpayAbout,
    Footer,
    Launcher
  }
}
</script>