<template>
  <div id="app">
    <ShopMain />
  </div>
</template>

<script>
import ShopMain from './components/ShopMain.vue';

export default {
  name: 'App',
  components: {
    ShopMain,
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
