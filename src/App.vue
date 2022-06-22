<script setup>
import Navbar from './/components/Navbar.vue'
import Hero from './components/Hero.vue'
import About from './components/About.vue'
import Developer from './components/Developer.vue'
import ContactHeader from './components/ContactHeader.vue'
import ContactForum from './components/ContactForum.vue'
import Footer from './components/Footer.vue'
</script>

<template>
<Navbar></Navbar>
<main>
<Hero></Hero>
<About></About>
<Developer></Developer>
<ContactHeader></ContactHeader>
<ContactForum></ContactForum>
<Footer></Footer>
</main>
  <Header msg="Hello Vue 3 + Vite" />
</template>

<style>
/* width */
::-webkit-scrollbar {
  width: 10px;
}

/* Track */
::-webkit-scrollbar-track {
  background: #000000; 
}
 
/* Handle */
::-webkit-scrollbar-thumb {
  background: #888; 
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #555; 
}
</style>
