<template>
  <div class="bg-white px-4 md:mx-0">
    <div class="max-w-6xl mx-auto py-20">
      <HeaderText :data="data" />
      <div class="grid grid-cols-3 gap-10 mt-16">
        <div class="md:block relative w-full hidden h-[320px]">
          <div class="absolute bg-black/90 inset-y-0 left-0 w-16"></div>

          <div class="absolute inset-y-0 left-8 flex items-center">
            <img
              class="h-64 w-full object-cover filter grayscale duration-300 transition-all ease-out hover:grayscale-0 hover:scale-105"
              src="/images/lion-6.jpg"
              alt=""
            />
          </div>
        </div>
        <div class="col-span-3 md:col-span-2 divide-y px-10 md:px-0">
          <p class="font-medium py-10 text-gray-600">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil nemo
            neque voluptate tempora velit cum non, fuga vitae architecto
            delectus sed maxime rerum impedit aliquam obcaecati, aut excepturi
            iusto laudantiu
          </p>
          <p class="text-gray-500 py-10">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil nemo
            neque voluptate tempora velit cum non, fuga vitae architecto
            delectus sed maxime rerum impedit aliquam obcaecati, aut excepturi
            iusto laudantiu
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import HeaderText from "./HeaderText.vue";

const data = {
  title: "About",
  subtitle: "Don't be busy, be productive",
};
</script>

<style lang="scss" scoped></style>
