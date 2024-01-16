<template>
  <div
    class="py-20 text-center space-y-10 px-4 md:mx-0 flex flex-col items-center"
  >
    <HeaderText :data="data" />
    <div class="space-y-3">
      <h1
        class="text-3xl -tracking-wider font-medium uppercase text-gray-500 hover:text-yellow-600"
      >
        Feel free to drop us a line at:
      </h1>
      <div>
        <a
          href="mailto:contact.hosnii@gmail.com"
          class="hover:text-yellow-700 text-gray-500"
          >contact.hosnii@gmail.com</a
        >
      </div>
      <div>
        <span class="font-medium text-xl">Find me in social media:</span>
        <div class="mt-4 text-center space-x-2">
          <a
            href="#"
            class="capitalize hover:text-blue-600 duration-300 ease-in-out transition-all"
            >Facebook</a
          >
          <a
            href="#"
            class="capitalize hover:text-blue-800 duration-300 ease-in-out transition-all"
            >Tinkedin</a
          >
          <a
            href="#"
            class="capitalize hover:text-blue-400 duration-300 ease-in-out transition-all"
            >Twitter</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import HeaderText from "./HeaderText.vue";

const data = {
  title: "Contact Me",
  subtitle: "We are born to create",
};
</script>

<style lang="scss" scoped></style>
