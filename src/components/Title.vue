<template>
  <div class="hello">
    <h1>Ciao!</h1>
    <p>La mia prima app Vue CLI!</p>
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
<style scoped lang="scss">
h1 {
  font-size: 5rem;
  background-color: rgb(65 184 131);
}

p {
  margin-top: 20px;
}
</style>
