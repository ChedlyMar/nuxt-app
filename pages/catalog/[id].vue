<template>
  <div>
    <h1>catalog with id {{ id }} works !</h1>
  </div>
</template>

<script setup lang="ts">
const { id } = useRoute().params;
</script>

<style scoped>
</style>