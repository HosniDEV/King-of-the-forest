<template>
  <div class="bg-white py-20 px-4 md:mx-0">
    <div class="max-w-6xl mx-auto">
      <HeaderText :data="data" />
      <div class="grid grid-cols-3 mt-10 gap-10">
        <div
          class="col-span-3 md:col-span-2 grid grid-cols-1 sm:grid-cols-2 gap-x-5 gap-y-16"
        >
          <CardServices
            title="web development"
            paragraph="Graphic design is the process of visual communication and problem-solving using one or more of typography, photography and illustration."
          >
            <LinkIcon
              class="size-20 text-gray-500 group-hover:text-yellow-600 hover:text-yellow-600 duration-300 transition-all ease-in-out"
            />
          </CardServices>
          <CardServices
            title="web development"
            paragraph="Graphic design is the process of visual communication and problem-solving using one or more of typography, photography and illustration."
          >
            <LightBulbIcon
              class="size-20 text-gray-500 group-hover:text-yellow-600 hover:text-yellow-600 duration-300 transition-all ease-in-out"
            />
          </CardServices>
          <CardServices
            title="Graphic Design"
            paragraph="Graphic design is the process of visual communication and problem-solving using one or more of typography, photography and illustration."
          >
            <RocketLaunchIcon
              class="size-20 text-gray-500 group-hover:text-yellow-600 hover:text-yellow-600 duration-300 transition-all ease-in-out"
            />
          </CardServices>
          <CardServices
            title="Web Design"
            paragraph="Graphic design is the process of visual communication and problem-solving using one or more of typography, photography and illustration."
          >
            <ShareIcon
              class="size-20 text-gray-500 group-hover:text-yellow-600 hover:text-yellow-600 duration-300 transition-all ease-in-out"
            />
          </CardServices>
        </div>
        <div class="hidden md:flex justify-end relative h-[320px]">
          <div class="bg-black/90 w-16"></div>
          <div class="absolute inset-y-0 right-8 flex items-center">
            <img
              class="h-72 filter grayscale duration-300 transition-all ease-out hover:grayscale-0 hover:scale-105"
              src="/images/lion-2.jpg"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import CardServices from "./CardServices.vue";
import { LinkIcon } from "@heroicons/vue/24/outline";
import { LightBulbIcon } from "@heroicons/vue/24/outline";
import { RocketLaunchIcon } from "@heroicons/vue/24/outline";
import { ShareIcon } from "@heroicons/vue/24/outline";
import HeaderText from "./HeaderText.vue";

const data = {
  title: "Services",
  subtitle: "Don't be busy, be productive",
};
</script>

<style lang="scss" scoped></style>
