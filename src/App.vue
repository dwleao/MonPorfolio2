<script setup>
import TopMenu from './components/TopMenu.vue';
import Card from './components/Card.vue';
import AboutMe from './components/AboutMe.vue';
import Experiences from './components/Experiences.vue';
import Projects from './components/Projects.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <header>
    <TopMenu/>
  </header>

  <main>
    <Card/>
  <AboutMe/>
  <Experiences/>
  <Projects/>
  <Contact/>
  <Footer/>
  </main>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300..700&display=swap');
</style>
