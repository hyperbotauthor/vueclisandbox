<template>
  <div id="app">
    <img width="40" src="./assets/logo.png" />
    <HelloWorld name="hyperbotauthor" />
    <div class="source">
      <a
        rel="noopener noreferrer"
        target="_blank"
        href="https://github.com/hyperbotauthor/vueclisandbox/tree/main/"
        >View Source Code on GitHub</a
      >
      |
      <a
        rel="noopener noreferrer"
        target="_blank"
        href="https://codesandbox.io/s/musing-edison-1uri7"
        >Develop in Code Sandbox</a
      >
    </div>
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
.source {
  margin-bottom: 10px;
}
</style>
