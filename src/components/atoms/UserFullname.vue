<script setup>
defineProps({
  fullname: {
    type: String,
    default: "bora.acici",
  },
});
</script>

<template>
  <span class="font-bold text-sm">{{ fullname }}</span>
</template>
