<template>
  <div id="app">
    <Header />
    <main id="main">
      <router-view />
    </main>
    <Footer />
  </div>
</template>

<script>

import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import './assets/styles.css';

export default {
  components: {
    Header,
    Footer
  }
}
</script>
  

<style>



  

</style>
