<template>
  <dev>
    <h1>API Test</h1>
    <p>Die Route 'api/test' liefert: {{ response.data }}</p>
  </dev>
</template>

<script setup>
  const response = await $fetch('/api/helloworld')
</script>