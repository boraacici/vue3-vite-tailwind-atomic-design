<script setup>
defineProps({
  title: { type: String, default: "Home" },
});
</script>

<template>
  <h1 class="text-lg font-bold">
    {{ title }}
  </h1>
</template>
