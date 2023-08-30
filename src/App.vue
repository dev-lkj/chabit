<template>
  <!-- <Header /> -->
  <Main />
  <Footer />
</template>

<script>
// import Header from './components/HeaderPage.vue';
import Main from './components/MainPage.vue';
import Footer from './components/FooterPage.vue';
import 'reset-css';


export default {
  name: 'App',
  components: {
    // Header,
    Main,
    Footer,


  }
}
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width:100vw;
  position: relative;
}

</style>
