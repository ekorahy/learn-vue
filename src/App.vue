<script setup>
import { ref } from 'vue'

const awesome = ref(true)

function toggle() {
  awesome.value = !awesome.value
}
</script>

<template>
  <button @click="toggle">Toggle</button>
  <p v-if="awesome">Vue is awesome!</p>
  <p v-else>Oh no😢</p>
</template>
