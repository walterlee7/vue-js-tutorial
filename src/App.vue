<template>
  <div id="app">
    <HelloWorld msg="Vue.js Directives"/>
    <div id="intro">
      <p>To use Vue.js directives, add this CDN inside the body element of your index.html file.</p>
      <p>Note: if you want to publish with Vue.js code, it is best to use the vue-cli template.</p>
      <pre id="intro-code">
            <code>
 development version of Vue.js:
 &lt;script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"&gt;&lt;/script&gt;

 production version of Vue.js:
 &lt;script src="https://cdn.jsdelivr.net/npm/vue"&gt;&lt;/script&gt;
            </code>
        </pre>
      <p style="margin-top: 0; margin-bottom: 0.5em;">
        For more info, visit the Vue.js site:
        <a
          href="https://vuejs.org/v2/guide/installation.html"
          target="_blank"
          rel="noopener noreferrer"
        >https://vuejs.org/v2/guide/installation.html</a>
      </p>
    </div>
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

#intro {
  background-color: rgb(78, 235, 235);
  border: 3px solid black;
  font-family: "Lucida Console", Monaco, monospace;
  text-align: center;
  margin: 1em;
  padding: 0.5em;
  left: 0;
  right: 0;
  margin-left: auto;
  margin-right: auto;
  width: 75%;
  font-size: 14px;
}

#intro-code {
  margin: 0;
  padding: 0;
}
</style>
