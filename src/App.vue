<script setup>
import { ref } from 'vue'
import ChildComp from './components/ChildComp.vue'

const msg = ref('from parent')
</script>

<template>
  <ChildComp
    ><p>Message: {{ msg }}</p></ChildComp
  >
</template>
