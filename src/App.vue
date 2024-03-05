<script setup>
import TodoList from './components/TodoList.vue'
import ProductList from './components/ProductList.vue'
import todos from '../data/todos.json'
</script>

<template>
  <div class="w-full">
    <!-- <ProductList /> -->
    <TodoList :todos="todos" />
  </div>
</template>

<style scoped></style>
