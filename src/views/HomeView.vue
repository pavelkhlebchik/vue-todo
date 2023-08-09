<script setup lang="ts">
</script>

<template>
  <button class="add">
    Add Todo</button>
  <TodoList />
</template>

<style lang="scss" scoped>
@import '../assets/mixins.scss';

.show {
  background-color: transparent;
  border: none;
  color: #ffffff;
  cursor: pointer;
  font-size: getRem(28);
  margin-top: getRem(45);
  margin-bottom: getRem(40);
  text-decoration: underline;
}

.add,
.random {
  background-color: #0f64a3;
  border: none;
  border-radius: getRem(35);
  color: #ffffff;
  cursor: pointer;
  font-size: getRem(28);
  padding-top: getRem(20);
  padding-right: getRem(70);
  padding-bottom: getRem(20);
  padding-left: getRem(70);
  margin-bottom: getRem(40);
}

.add:hover,
.random:hover {
  text-decoration: underline;
}

.show:hover {
  text-decoration: none;
}
</style>