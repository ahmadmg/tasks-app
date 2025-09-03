<script lang="ts" setup>
import { ref } from "vue";
import TaskForm from './components/TaskForm.vue'
const message = ref("Tasks App");
</script>

<template>
  <main>
    <h1>{{ message }}</h1>
  <TaskForm />
  </main>
</template>

<style >
main {
  padding: 2rem;
  text-align: center;
}
.button-container {
  display: flex;
  justify-content: center;
}
</style>
