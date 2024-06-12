<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Menu msg=" "/>
  <Formulario msg="  "/>
  <BarraLateral msg=" "/>
  <Footer msg="Para saber mais sobre nós, utilize os links!!"/>
</template>

<script>

import Menu from './components/Menu.vue';
import Formulario from './components/Formulario.vue';
import BarraLateral from './components/BarraLateral.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Menu,
    Formulario,
    BarraLateral,
    Footer,
   }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: black;
  color: white;
  margin-top: 60px;
}
</style>
