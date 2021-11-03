<template>
  <div class="hello">
    <h1>Hello from {{ name }} !!</h1>
    <h2>Welcome to my Vue JS Chessboard ...</h2>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    name: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: #007;
  font-size: 35px;
}
h2 {
  color: #070;
  font-size: 30px;
}
ul {
  list-style-type: none;
  padding: 0;
}
</style>
