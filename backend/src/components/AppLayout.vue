<template>
    <div class="min-h-full flex">
      <!-- Sidebar -->

      <Sidebar />
      <!-- Sidebar-->

      <div class="flex-1">
        <TopHeader></TopHeader>
        <!-- Header -->
        <header class="h-8 shadow bg-white">
          Header
        </header>
        <!-- Content -->
        <main>
          <router-view></router-view>
        </main>
        <!-- Content -->
      </div>
    </div>
  </template>

  <script setup>
import Sidebar from "./Sidebar.vue";
import TopHeader from "./TopHeader.vue";

  const { title } = defineProps({
    title: String,
  });
  </script>

  <style scoped>
  /* Ensure the layout spans the entire screen */
  </style>
