<script setup lang="ts">
import About from './components/About.vue';
import Profile from './components/Profile.vue';
import Projects from './components/Projects.vue';
</script>

<template>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <div class="overflow-y-hidden h-full p-14 bg-gray-800 text-white">
    <div class="w-full max-w-screen-lg mx-auto px-4 m-auto block md:flex justify-between">
      <Profile />
      <main>
        <About />
        <Projects />
      </main>
    </div>
  </div>
</template>

<style scoped></style>
