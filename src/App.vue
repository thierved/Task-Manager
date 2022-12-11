<template>
  <div class="app">
    <div class="container">
      <TheHeader />
      <TaskList />
    </div>
  </div>
</template>

<script setup>
import TheHeader from './components/TheHeader.vue';
import './assets/base.css'
import TaskList from './components/TaskList.vue';

</script>

<style scoped>
.app {
  height: 100vh;
  padding-top: 2rem;
  background: linear-gradient(rgba(22, 46, 44, 0.8), rgba(51, 51, 51, .8)), url('./assets/images/bg-img.jpg');  
  background-size: cover;
  background-position: center;  
}

.container {
  max-width: 80%;
  min-height: 80vh;
  margin: 0 auto;
}

</style>
