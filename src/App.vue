<template>
  <div id="app">
    <img width="40" src="./assets/logo.png" />
    <HelloWorld name="hyperbotauthor" />
    <ChessboardExt> </ChessboardExt>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

import { ChessboardExt } from "@publishvue/vue3complib";

export default {
  name: "App",
  components: {
    HelloWorld,
    ChessboardExt,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  text-align: center;
}
</style>
