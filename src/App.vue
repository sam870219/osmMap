<template>
  <div id="app">
    <osmMap msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import osmMap from './components/osmMap.vue';

export default {
  name: 'App',
  components: {
    osmMap,
  },
};
</script>

<style lang="scss">
*{
    padding:0;
    margin:0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}
</style>
