<template>
  <div class="w-full h-screen text-white flex flex-col items-center">
  <div class="w-full h-[10vh] flex justify-center items-center bg-slate-500">

    <TopNavigation></TopNavigation>
  </div>
  <div class="w-full h-[90vh] flex justify-center items-center">
    <div class="w-full h-[50vh] text-white bg-slate-500 3xl:bg-black 3xl:w-[50%] 3xl:h-[50vh] transition flex justify-center items-center">
      <h1>Vue-JS 2 starter template</h1>
    </div>
  </div>
  </div>
</template>

<script setup>
import TopNavigation from "./components/TopNavigation.vue";

</script>

<style lang="scss" scoped>

</style>