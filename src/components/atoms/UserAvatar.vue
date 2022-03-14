<script setup>
defineProps({
  src: {
    type: String,
    default: () =>
      new URL("@/assets/images/user-avatar.jpg", import.meta.url).href,
  },
  alt: { type: String, default: "User avatar" },
});
</script>

<template>
  <img src="@/assets/images/user-avatar.jpg" :alt="alt" class="rounded-full" />
</template>
