<script setup>
import HomeButton from "@/components/molecules/HomeButton.vue";
</script>

<template>
  <nav
    class="fixed bottom-0 w-full h-14 flex justify-evenly gap-x-2 py-2 border-t"
  >
    <HomeButton class="rounded-full p-1 hover:bg-gray-300"></HomeButton>
    <HomeButton class="rounded-full p-1 hover:bg-gray-300"></HomeButton>
    <HomeButton class="rounded-full p-1 hover:bg-gray-300"></HomeButton>
    <HomeButton class="rounded-full p-1 hover:bg-gray-300"></HomeButton>
  </nav>
</template>
