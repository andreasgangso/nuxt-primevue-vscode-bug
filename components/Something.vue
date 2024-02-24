<script setup lang="ts">
import { ref } from "vue";
const thing = ref("thing");
</script>

<template>
  <div>Some {{ thing }}</div>
</template>
