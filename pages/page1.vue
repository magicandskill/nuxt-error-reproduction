<script setup lang="ts">
const click = async () => {
  window.location.href = '/page2'
}
</script>

<template>
  <div>
    <h1>Page 1</h1>
    <button @click="click">Go to Page 2</button>
  </div>
</template>
