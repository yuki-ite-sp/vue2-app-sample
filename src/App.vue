<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <LibSample />
  </div>
</template>

<script>
import '@yuki-ite-sp/vue2-lib-sample/dist/LibSample.css'
import HelloWorld from './components/HelloWorld.vue'
import LibSample from '@yuki-ite-sp/vue2-lib-sample'

export default {
  name: 'App',
  components: {
    HelloWorld,
    LibSample
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
