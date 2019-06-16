<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <Accounting msg="why is that grid not working"/>
  </div>
</template>

<script>
import Accounting from "./components/Accounting";

export default {
  name: "App",
  components: {
    Accounting
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
