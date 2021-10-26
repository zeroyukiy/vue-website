<template>
  <div class="container">
    <h1>{{ msg }}</h1>

    <input type="button" class="btn btn-colored" value="Click Here" />
    <input type="button" class="btn btn-success" value="Click Here">
    <input type="button" class="btn btn-danger" value="Click Here">
    <input type="button" class="btn btn-default" value="Click Here">
    <input type="button" class="btn btn-awesome" value="Click Here">
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>