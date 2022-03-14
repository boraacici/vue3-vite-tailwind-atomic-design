<script setup>
import UserAvatar from "../atoms/UserAvatar.vue";
import PageHeading from "../atoms/PageHeading.vue";
</script>

<template>
  <div class="flex items-center justify-center h-14 px-4">
    <div class="inline-flex items-center h-full w-8 mr-2 basis-12">
      <UserAvatar />
    </div>
    <div class="flex-grow">
      <PageHeading />
    </div>
  </div>
</template>
