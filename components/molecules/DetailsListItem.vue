<template>
  <li>
    <input type="checkbox" id="{{id}}" />
    <label for="{{id}}">{{ title }}</label>
  </li>
</template>

<script setup>
const { id, title } = defineProps(["id", "title"]);
</script>

<style scoped>
input:hover {
  cursor: pointer;
}
</style>
