<template>
  <div>
    <Navbar />
    <RouterView />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import router from './router';

export default{
  components: {
    Navbar
  }
}

</script>

<style>

</style>
