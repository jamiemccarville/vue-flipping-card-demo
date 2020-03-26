<template>
  <div id="app">
    <flipping-cards></flipping-cards>
  </div>
</template>

<script>
import flippingCards from "./components/flippingCards.vue";

export default {
  name: "App",
  components: {
    flippingCards
  }
};
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
