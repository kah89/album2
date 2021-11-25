<template>
  <div id="app">
    <Header/>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld/> -->
    <Home/>
    <Fotos21/>
    <Footer/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue';
import Header from './components/Header.vue';
import Home from './components/Home.vue';
import Fotos21 from './components/Fotos21.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Home,
    Fotos21,
    Footer,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
