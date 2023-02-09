<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <KitamuraShopSearch
      cart-api-url="https://aws-cart-api-kitamura.shimaumaprint.com"
      token="d35121b621635e44e18b015f268651d8c8bb36e1b1bc1accde3c2bdef1f28c90"
    />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import KitamuraShopSearch from "@shimauma-print-inc/kitamura-shop-search";

console.log(KitamuraShopSearch);

export default {
  name: "App",
  components: {
    HelloWorld,
    KitamuraShopSearch,
  },
};
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
