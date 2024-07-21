<template>
  <summary>{{ summaryTitle }}</summary>
</template>

<script setup>
const { summaryTitle } = defineProps(["summaryTitle"]);
</script>

<style scoped>
summary {
  font-size: 1.3rem;
}
</style>
