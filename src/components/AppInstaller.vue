<script setup lang="ts">
  import { ref } from 'vue'

  const message = ref('Hello')
  
  function updateMessage(){
    message.value = "Hello from vue!"
  }
</script>

<template>
  <h1 class="installer_header">Datavzrd Installer</h1>
  <div>{{ message }}</div>
  <button @click="updateMessage">Change</button>
</template>
