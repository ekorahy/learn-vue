<script setup>
import { ref } from 'vue'

const text = ref('')
</script>

<template>
  <input type="text" v-model="text" placeholder="Type here" />
  <p>{{ text }}</p>
</template>
