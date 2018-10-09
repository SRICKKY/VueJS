<template>
  <div id="app">
    <Navbar />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <AnotherComponent anothermsg="This is from AnotherComponent" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AnotherComponent from './components/AnotherComponent'
import Navbar from './components/Navbar'

import '../node_modules/materialize-css/dist/css/materialize.min.css'
import '../node_modules/materialize-css/dist/js/materialize.min.js'
import '../node_modules/jquery/dist/jquery.min.js'

export default {
  name: 'app',
  components: {
    HelloWorld,
    // Navbar,
    AnotherComponent,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
