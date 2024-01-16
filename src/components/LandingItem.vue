<template>
  <div class="relative overflow-hidden">
    <div
      class="grid place-items-center w-full v-[100vh - 66px] bg-[url('/images/lion-1.jpg')] bg-cover bg-no-repeat filter grayscale duration-300 transition-all ease-out hover:grayscale-0 inset-0"
    >
      <div
        class="text-center space-y-6 text-white tracking-wider flex flex-col items-center"
      >
        <h1 class="text-5xl font-bold text-gray-100 uppercase">
          <span class="text-yellow-600">King</span> of the forest
        </h1>
        <p class="w-2/3 text-center leading-10 tracking-widest text-2xl">
          It's better to be a lion for a day than a sheep all your life
        </p>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.w-full {
  height: calc(100vh - 66px);
}
</style>
>
