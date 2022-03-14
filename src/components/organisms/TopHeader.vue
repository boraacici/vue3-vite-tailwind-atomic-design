<script setup>
import UserAvatar from "../atoms/UserAvatar.vue";
import PageHeading from "../atoms/PageHeading.vue";
</script>

<template>
  <header
    class="flex items-center justify-center h-14 px-4 backdrop-blur-md sticky top-0 bg-white bg-opacity-80 z-10"
  >
    <div class="inline-flex items-center h-full w-8 mr-2 basis-12">
      <UserAvatar class="sm:hidden" />
    </div>
    <div class="flex-grow">
      <PageHeading />
    </div>
  </header>
</template>
