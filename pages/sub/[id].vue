<script lang="ts" setup>
const visible = ref(false);

setTimeout(() => {
  visible.value = true;
}, 200);
</script>

<template>
  <div v-if="visible">
    <h1>Level 01/Page 01</h1>
    <input type="text">
  </div>
</template>

<style scoped>

</style>