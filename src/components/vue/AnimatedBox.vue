<script setup>
import { ref } from "vue";
import { useMotion } from "@vueuse/motion";

const boxRef = ref(null);

// Apply motion
useMotion(boxRef, {
  initial: { opacity: 0, y: 50 },
  enter: { opacity: 1, y: 0, transition: { duration: 1.5 } },
  hover: { scale: 1.5, rotate: 5 },
});
</script>

<template>
    <div ref="boxRef" class="w-50 h-50 bg-blue-500 text-white flex items-center justify-center rounded-lg shadow-lg cursor-pointer">
      Hover Me!
    </div>
  </template>
