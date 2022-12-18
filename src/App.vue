<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="my-8 font-mono">
    <h1 class="text-center text-6xl font-bold mb-4 text-blue-500" @click="$router.push('/')">title("Bako's Blog")
    </h1>
    <p class="text-center text-3xl text-gray-500">desc("A blog with posts about stuff i guess")</p>
  </header>
  <RouterView />
</template>
