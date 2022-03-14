<script setup>
import UserAvatar from "../atoms/UserAvatar.vue";
import TextInput from "../atoms/TextInput.vue";
import PostButton from "../atoms/PostButton.vue";
</script>
<template>
  <div>
    <div class="flex">
      <UserAvatar width="48" class="mx-3 sm:block hidden" />
      <TextInput class="grow pl-4 sm:pl-0 max-w-full" />
    </div>
    <div class="mt-2 mr-2 mb-2 text-right">
      <PostButton />
    </div>
  </div>
</template>
