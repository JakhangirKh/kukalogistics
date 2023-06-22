<template>
  <Navbar />
  <Mainbar />
  <Servicebar/>
  <Aboutbar/>
  <Footerbar/>
</template>

<script>
import Aboutbar from './components/Aboutbar.vue';
import Footerbar from './components/Footerbar.vue';
import Mainbar from './components/Mainbar.vue'
import Navbar from './components/Navbar.vue'
import Servicebar from './components/Servicebar.vue';
export default {
  components: { Navbar, Mainbar, Servicebar, Aboutbar, Footerbar },

}
</script>

<style></style>