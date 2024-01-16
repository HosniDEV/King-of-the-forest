<script setup>
import LandingItem from "./components/LandingItem.vue";
import NabarItem from "./components/NabarItem.vue";
import FooterItem from "./components/FooterItem.vue";
import HeaderItem from "./components/HeaderItem.vue";
import ServicesItem from "./components/ServicesItem.vue";
import PortifolioItem from "./components/PortifolioItem.vue";
import AboutItem from "./components/AboutItem.vue";
import ContactItem from "./components/ContactItem.vue";
import { ChevronUpIcon } from "@heroicons/vue/24/outline";
import { ref, onMounted, onUnmounted } from "vue";

const showScrollButton = ref(true);
const handleScroll = () => {
  showScrollButton.value = window.scrollY > 200; // Adjust the scroll position threshold as needed
};
const scrollToTop = () => {
  window.scrollTo({
    top: 0,
    behavior: "smooth",
  });
};
onMounted(() => {
  window.addEventListener("scroll", handleScroll);
});

// Remove the scroll event listener when the component is destroyed
onUnmounted(() => {
  window.removeEventListener("scroll", handleScroll);
});
</script>

<template>
  <div class="" id="main">
    <button
      v-show="showScrollButton"
      @click="scrollToTop"
      class="fixed bg-black/90 rounded-full p-2 text-white bottom-4 right-4"
    >
      <ChevronUpIcon class="size-6 animate-bounce" />
    </button>
    <NabarItem />
    <LandingItem />
    <main>
      <HeaderItem />
      <ServicesItem id="services" />
      <PortifolioItem id="portifolio" />
      <AboutItem id="about" />
      <ContactItem id="contact" />
    </main>
    <FooterItem />
  </div>
</template>
