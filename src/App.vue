<template>
  <div id="app">
    <todoInput />
    <todoList />
  </div>
</template>

<script>
import todoInput from "./components/todoInput.vue";
import todoList from "./components/todoList.vue";

export default {
  name: "app",
  components: {
    todoInput,
    todoList
  }
};
</script>

<style>
#app {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
</style>
