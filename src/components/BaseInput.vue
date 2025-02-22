<template>
  <input
    v-model="model"
    type="text"
    placeholder="Add a new task..."
    class="w-full px-4 py-3 border border-gray-300 rounded-lg"
  />
</template>

<script setup>
const model = defineModel()
</script>

<style lang="scss" scoped></style>
