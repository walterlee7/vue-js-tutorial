<template>
  <div id="title">
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#title {
  background-color: rgb(212, 212, 212);
  border-radius: 15px;
  text-align: center;
  margin: 1em;
  padding: 0.5em;
  left: 0;
  right: 0;
  margin-left: auto;
  margin-right: auto;
  width: 30%;
  font-weight: bold;
  font-size: 22px;
}
</style>
