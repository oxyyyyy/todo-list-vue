<template>
  <div class="todoInput">
    <input v-model="todoInputText" type="text">
    <p>{{todoInputText}}</p>
  </div>
</template>

<script>
export default {
  name: "todoInput",
  data() {
    return { todoInputText: "" };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
