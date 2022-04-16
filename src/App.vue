<template>
  <div class="flex min-h-screen  bg-gray-900">
    <SideBar></SideBar>
    <router-view></router-view>
  </div>
</template>

<script setup>
import SideBar from './components/SideBar.vue'
</script>