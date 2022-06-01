<script setup>
  let count = ref(0)
  let reset = ref(
    function(){
      this.count = 0
    }
  )
</script>

<template>
  <div>
    <button @click="count++">{{count}}</button>
    <button @click="reset">reset</button>
  </div>
</template>