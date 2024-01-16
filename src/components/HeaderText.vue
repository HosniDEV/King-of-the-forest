<template>
  <div class="text-center -space-y-6">
    <h1
      class="text-5xl sm:tex-6xl md:text-7xl uppercase tracking-widest font-black text-gray-200 text-200"
    >
      {{ data.title }}
    </h1>
    <p class="tracking-wide text-xl capitalize text-gray-500">
      {{ data.subtitle }}
    </p>
  </div>
</template>

<script setup>
defineProps({
  data: Object,
});
</script>

<style lang="scss" scoped></style>
