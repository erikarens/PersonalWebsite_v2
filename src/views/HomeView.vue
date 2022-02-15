<script lang="ts" setup>
import Header from "../components/Header.vue";
import About from "../components/About.vue";
import Milestones from "../components/Milestones.vue";
import Contact from "../components/Contact.vue";
import Footer from "../components/Footer.vue";
</script>

<template>
  <main>
    <Header />
    <About id="about" />
    <Milestones id="milestones" />
    <Contact id="contact" />
    <Footer />
  </main>
</template>
