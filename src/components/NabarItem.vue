<template>
  <nav class="bg-white border border-b border-collapse py-4 px-4 md:px-0">
    <div class="max-w-6xl mx-auto flex justify-between items-center">
      <img class="size-10" src="@/assets/logo.svg" alt="" />
      <div class="relative">
        <Bars3CenterLeftIcon
          class="size-6 rotate-180 cursor-pointer"
          @click="show = !show"
        />
        <div
          v-show="show"
          class="absolute bg-gray-200 rounded-md w-40 right-0 flex flex-col divide-y divide-gray-100 z-20 top-6 overflow-hidden duration-300 transition-transform"
        >
          <a
            href="#services"
            class="px-5 py-2 text-black hover:translate-x-1 duration-300 transition-transform"
            >Services</a
          >
          <a
            href="#portifolio"
            class="px-5 py-2 text-black hover:translate-x-1 duration-300 transition-transform"
            >Portifolio</a
          >
          <a
            href="#about"
            class="px-5 py-2 text-black hover:translate-x-1 duration-300 transition-transform"
            >About</a
          >
          <a
            href="#contact"
            class="px-5 py-2 text-black hover:translate-x-1 duration-300 transition-transform"
            >Contact</a
          >
        </div>
      </div>
    </div>
  </nav>
</template>

<script setup>
import { Bars3CenterLeftIcon } from "@heroicons/vue/24/solid";
import { ref } from "vue";
const show = ref(false);
</script>

<style lang="scss" scoped></style>
