<template>
  <div class="todoList">
    <todoItem />
  </div>
</template>

<script>
import todoItem from "./todoItem.vue";

export default {
  name: "todoList",
  components: {
    todoItem
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
