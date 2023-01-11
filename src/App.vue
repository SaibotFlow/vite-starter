<script setup>

//Import Component
import CompTemplate from './components/CompTemplate.vue'
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap-icons/font/bootstrap-icons.css"
import "bootstrap";
</script>

<template>
  <h1 class="display-1">
      AppVue 
      <i class="bi bi-emoji-sunglasses"></i>
  </h1>
  <CompTemplate msg="Data coming from App.vue" />
</template>

<style scoped>

</style>
