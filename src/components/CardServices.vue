<template>
  <div class="flex space-x-4 items-start group">
    <slot></slot>
    <div>
      <h1 class="text-xl font-medium mb-4 capitalize text-gray-600">
        {{ title }}
      </h1>
      <p class="font-normal text-gray-500">
        {{ paragraph }}
      </p>
    </div>
  </div>
</template>

<script setup>
defineProps(["title", "paragraph"]);
</script>

<style lang="scss" scoped></style>
