<script setup lang="ts">
const click = async () => {
  window.location.href = '/page1'
}
</script>

<template>
  <div>
    <h1>Page 2</h1>
    <button @click="click">Go to Page 1</button>
  </div>
</template>
