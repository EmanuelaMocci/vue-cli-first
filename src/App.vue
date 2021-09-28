<template>
  <div id="app">
    <Title/>
    <Hero message="Testo ed immagine aggiunti tramite componente Hero."/>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Hero from './components/Hero.vue'
export default {
  name: 'App',
  components: {
    Title,
    Hero
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
