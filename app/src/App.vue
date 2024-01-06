<template>
  <div>
    <Navbar />
    <RouterView />
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';
import router from './router';

export default{
  components: {
    Navbar
  }
}

</script>

<style>

</style>
