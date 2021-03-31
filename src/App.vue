<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <tina>
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Tina from "./components/Tina.vue";
export default {
  name: "App",
  components: {
    HelloWorld,
    Tina,
  },
};
</script>
