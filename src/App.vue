<template>
  <div id="app">
    <Header />
    <img src="./assets/logo.png" alt="Vue logo">
     
    <Section />
    <img src="https://www.venetoformazione.it/wp-content/webp-express/webp-images/uploads/2020/11/ottimizzare-immagini-display-retina.jpg.webp" alt="">

   
    
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Section from '@/components/Section.vue';


export default {
  name: 'App',
  components: {
    Header,
    Section,
  }
}
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
