<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <router-link to="/helloworld">helloworld</router-link>
    <router-link to="/">Hello</router-link>
  </div>
</template>

<script>
import Hello from './components/Hello'

export default {
  name: 'App',
  components: {
    Hello
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
  margin-top: 60px;
}
</style>
