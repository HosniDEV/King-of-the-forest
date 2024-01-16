<template>
  <div class="py-20 max-w-6xl mx-auto space-y-20">
    <HeaderText :data="data" />
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-5">
      <div class="bg-white overflow-hidden">
        <img
          class="aspect-video object-cover w-full filter grayscale duration-300 transition-all ease-out hover:grayscale-0 hover:scale-105"
          src="/images/lion-3.jpg"
          alt=""
        />
        <div class="py-6 px-6">
          <h1 class="text-lg font-medium text-gray-600">Project Here</h1>
          <p class="text-sm text-gray-500 font-normal mt-2">
            My creative ability is very difficult to measure because it can
            manifest in so many surprising and.
          </p>
        </div>
      </div>
      <div class="bg-white overflow-hidden">
        <img
          class="aspect-video object-cover w-full filter grayscale duration-300 transition-all ease-out hover:grayscale-0 hover:scale-105"
          src="/images/lion-4.jpg"
          alt=""
        />
        <div class="py-6 px-6">
          <h1 class="text-lg font-medium text-gray-600">Project Here</h1>
          <p class="text-sm font-normal mt-2 text-gray-500">
            My creative ability is very difficult to measure because it can
            manifest in so many surprising and.
          </p>
        </div>
      </div>
      <div class="bg-white overflow-hidden">
        <img
          class="aspect-video object-cover w-full filter grayscale duration-300 transition-all ease-out hover:grayscale-0 hover:scale-105"
          src="/images/lion-5.jpg"
          alt=""
        />
        <div class="py-6 px-6">
          <h1 class="text-lg font-medium text-gray-600">Project Here</h1>
          <p class="text-sm font-normal mt-2 text-gray-500">
            My creative ability is very difficult to measure because it can
            manifest in so many surprising and.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import HeaderText from "./HeaderText.vue";
const data = {
  title: "Portfolio",
  subtitle: "If you do it right, it will last forever.",
};
</script>

<style lang="scss" scoped></style>
