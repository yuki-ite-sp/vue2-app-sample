<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <TestKitamuraShopSearch />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TestKitamuraShopSearch from '@shimauma-print-inc/test-kitamura-shop-search'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TestKitamuraShopSearch
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
