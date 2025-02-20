<script setup>
import JSConfetti from 'js-confetti'

const confetti = new JSConfetti()

function showConfetti() {
  confetti.addConfetti()
}

showConfetti()
</script>

<template>
  <div class="confetti-container">
    <h1 @click="showConfetti">🎉 Congratulation</h1>
  </div>
</template>

<style>
.confetti-container {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

h1 {
  cursor: pointer;
}
</style>
