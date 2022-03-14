<script setup>
import { reactive } from "vue";

defineProps({
  placeholder: { type: String, default: "What's Happening?" },
});

const state = reactive({ inputText: "" });

function input(e) {
  state.inputText = e.currentTarget.innerText;
}
</script>

<template>
  <div class="relative py-3 border-b">
    <div
      contenteditable="true"
      class="focus-visible:outline-none text-black"
      @focusin="focusIn"
      @input="input"
    ></div>
    <span
      v-if="state.inputText.length === 0"
      class="absolute top-0 py-3 text-zinc-600"
      >{{ placeholder }}</span
    >
  </div>
</template>
