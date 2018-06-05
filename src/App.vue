<template>
  <div id="app">
    <Nav />    
    <HelloWorld msg="Yo dude, Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Nav from './components/Nav.vue'
import './scss/main.scss'

// eslint-disable-next-line
// console.log(process.env.VUE_APP_A_SECRET_KEY)


export default {
  name: 'app',
  components: {
    Nav,
    HelloWorld
  }
}
</script>

<style>


/* #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0;
} */
</style>
