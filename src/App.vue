<template>
  <div class="page-wrapper">
    <Header/>
    <Sidebar/><Technology/>
    <Footer/>
    
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Sidebar from "./components/Sidebar.vue";
import Footer from "./components/Footer.vue";
import Technology from "./components/Attractiveness/Technology.vue";
export default {
  name: "App",
  components: {
    Header,
    Sidebar,
    Footer,
    Technology,
  },
  data: function () {
  },
};
</script>

<style></style>
