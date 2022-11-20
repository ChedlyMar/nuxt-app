<template>
  <div>
    <div class="grid grid-cols-4 gap-5">
      <div v-for="p in products" :key="p.id">
        <NuxtLink :to="`/catalog/${p.id}`">{{ p.title }}</NuxtLink>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: "catalog",
});

//  fetch the products
const { data: products } = await useFetch("https://fakestoreapi.com/products");
</script>

<style scoped>
</style>