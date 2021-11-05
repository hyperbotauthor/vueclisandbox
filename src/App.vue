<template>
  <div id="app">
    <HelloWorld name="hyperbotauthor" />
    <div>
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
    <ChessboardExt style="margin-top: 5px"> </ChessboardExt>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

import { ChessboardExt } from "@publishvue/vue3complib";

export default {
  name: "App",
  mounted() {},
  components: {
    HelloWorld,
    ChessboardExt,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  flex-direction: column;
  align-items: center;
  display: flex;
}
</style>
