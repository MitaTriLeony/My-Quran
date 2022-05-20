<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "@/components/HelloWorld.vue";
</script>

<template>
  <header style="text-align: center">
    <img
      alt="quran logo"
      class="logo"
      src="@/assets/myquran.png"
      width="200"
      height="200"
    />

    <div class="wrapper">
      <HelloWorld msg="My Qur'an" />
      <nav class="card-header">
        <RouterLink to="/" class="text-success btn btn-outline-dark me-3">Home</RouterLink>
        <RouterLink to="/about" class="text-success btn btn-outline-dark">About</RouterLink>
      </nav>
    </div>
  </header>
  <RouterView />
</template>
