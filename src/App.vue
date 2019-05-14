<template>
  <div id="app">
    <HelloWorld msg="Vue.js Directives"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld
  }
};
</script>

<style>
body {
  background-color: rgb(147, 147, 241);
  font-family: "Lucida Sans Unicode", "Lucida Grande", sans-serif;
  min-width: 811px;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
