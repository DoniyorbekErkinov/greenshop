<script setup>
import Navbar from './components/Navbar/index.vue'
</script>
<template>
  <div class="h-screen w-screen flex flex-col items-center bg-white">
    <div class="2xl:w-[1500px] h-full px-28 border border-slate-100">
      <Navbar/>
      <NuxtPage />
    </div>
  </div>
</template>
<style scoped>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
</style>
