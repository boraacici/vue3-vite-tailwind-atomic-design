<script setup>
import HomeButton from "@/components/molecules/HomeButton.vue";
</script>

<template>
  <nav
    class="fixed bottom-0 w-full h-14 flex justify-evenly gap-x-2 py-2 border-t bg-white sm:hidden"
  >
    <HomeButton
      tabindex="1"
      class="rounded-full p-1 hover:bg-gray-300"
    ></HomeButton>
    <HomeButton
      tabindex="2"
      class="rounded-full p-1 hover:bg-gray-300"
    ></HomeButton>
    <HomeButton
      tabindex="3"
      class="rounded-full p-1 hover:bg-gray-300"
    ></HomeButton>
    <HomeButton
      tabindex="4"
      class="rounded-full p-1 hover:bg-gray-300"
    ></HomeButton>
  </nav>
</template>
