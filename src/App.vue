<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav>
      <RouterLink to="/" style="font-family: 'Salsa', cursive;
; font-size: 25px; font-weight: 600; text-decoration: underline; color: black">TODO NOW</RouterLink>
    <div class="kanan">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/todo">To Do</RouterLink>
    </div>
  </nav>
  <RouterView />
</template>
