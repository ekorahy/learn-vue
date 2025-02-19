<script setup>
import { ref, reactive } from 'vue'

const counter = reactive({
  count: 0,
})
counter.count++

const message = ref('Hello World!')
</script>

<template>
  <h1>{{ message.split('').reverse().join('') }}</h1>
  <span>{{ counter.count }}</span>
</template>
