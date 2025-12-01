<script setup>
import { ref } from 'vue'
const count = ref(0)
</script>
<template>
  <div class="min-h-screen bg-gradient-to-br from-gray-900 to-gray-800 flex items-center justify-center">
    <div class="text-center">
      <h1 class="text-5xl font-bold text-white mb-4">PPES</h1>
      <p class="text-gray-400 mb-8 max-w-md">PPES est une application qui permet de gérer les assemblées générales des PPE en Suisse</p>
      <div class="bg-gray-800/50 rounded-2xl p-8 border border-gray-700">
        <p class="text-4xl text-white mb-6">{{ count }}</p>
        <button @click="count++" class="px-8 py-3 bg-emerald-500 hover:bg-emerald-600 text-white font-semibold rounded-xl transition-colors">Click me!</button>
      </div>
      <p class="mt-12 text-gray-500 text-sm">Créé avec ❤️ par Nexoria</p>
    </div>
  </div>
</template>