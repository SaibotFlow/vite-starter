<script setup>
import {  ref, 
          onMounted,onUpdated, 
          onUnmounted, 
          onBeforeMount, 
          onBeforeUnmount, 
          onBeforeUpdate
        } 
from 'vue';


/* 
 *  Lifecycle Hooks 
 *  Check for more: https://vuejs.org/api/composition-api-lifecycle.html
 */

//After
onMounted(()=>{
})

onUpdated(() => {
  
})

onUnmounted(() => {
  
})

//Before
onBeforeUnmount(() => {
  
}),

onBeforeMount(() => {
  
})

onBeforeUpdate(() => {
  
})


//Properties with Type
defineProps({
  msg: String
})

//Bindable Variables
const count = ref(0)

</script>

  <!--HTML Stuff-->
<template>
  <p class="lead">CompTemplate: {{ msg }}</p>
</template>

<!-- CSS Stuff -->
<style scoped>
 
</style>
