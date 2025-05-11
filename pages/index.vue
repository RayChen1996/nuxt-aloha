<template>
  <div></div>
</template>

<script setup lang="ts">
import { onMounted } from "vue";
import { useSeoMeta } from "nuxt/app";

useSeoMeta({
  title: "ALOHA",
  description: "",
});
// onMounted(() => {
//   AOS.init({
//     duration: 800,
//     once: false,
//   });
// });
</script>
