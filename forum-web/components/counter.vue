<script setup>
  let count = ref(0)
  let reset = ref(
    function(val){
      this.count = val
    }
  )
</script>

<template>
  <div>
    <button @click="count++">{{count}}</button>
    <button @click="reset(0)">reset</button>
  </div>
</template>