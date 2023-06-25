<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <div class="content"><h1 class="title">Prueba</h1></div>
</template>
<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style lang="scss">
.content {
  background: gray;
  .title {
    color: red;
    font-size: 12px;
  }
}
</style>
