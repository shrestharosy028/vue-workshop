<template>
  <div id="app">
    <hello-world></hello-world>
    <!-- <HelloWorld/> -->
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
export default {
  name: "app",
  components: {
    HelloWorld
  }
};
</script>

<style lang="scss">
@import "./styles/main.scss";

#app {
  margin-top: 60px;
}
</style>
