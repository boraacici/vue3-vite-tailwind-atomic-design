<script setup>
import UserAvatar from "../atoms/UserAvatar.vue";
import UserFullname from "../atoms/UserFullname.vue";
import PostContent from "../atoms/PostContent.vue";
</script>

<template>
  <article class="border-t px-4 flex py-3 hover:bg-gray-100">
    <div class="inline-flex items-center h-full mr-2 basis-12 shrink-0">
      <UserAvatar />
    </div>
    <div>
      <UserFullname />
      <PostContent
        content="What two languages would you like to be fluent in?"
      />
    </div>
  </article>
</template>
