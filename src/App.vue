<script setup>
import LandingItem from "./components/LandingItem.vue";
import NabarItem from "./components/NabarItem.vue";
import FooterItem from "./components/FooterItem.vue";
import HeaderItem from "./components/HeaderItem.vue";
import ServicesItem from "./components/ServicesItem.vue";
import PortifolioItem from "./components/PortifolioItem.vue";
import AboutItem from "./components/AboutItem.vue";
import ContactItem from "./components/ContactItem.vue";
</script>

<template>
  <div class="bg-gray-100">
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
