<script setup>
import { defineProps } from 'vue'
defineProps({
  count: {
    type: Number,
    required: true,
  },
});
</script>

<template>
  <button @click="count++">{{count}}</button>
</template>

<style scoped>
button {
    background-color:green;
    padding: 1em;
}
</style>
