<script setup>
// No need for any script logic for now.
</script>

<template>
  <div class="max-w-sm bg-white rounded-lg mr-4">
    <img src="https://placehold.co/600x400" alt="Book Cover" class="w-full h-24 object-cover shadow-lg">
    <div class="p-6">
      <p class="text-gray-700 mb-4">
        This is a brief description of my book. It provides an overview of the content and what readers can expect.
      </p>
      <button 
        @click="buyNow" 
        class="w-full px-4 py-2 
        bg-[#ffd54f] hover:bg-yellow-300/100
        text-slate-700 text-xl font-bold 
        border border-yellow-500 rounded-md mb-4">
        Buy Now ($89)
      </button>
      <button 
        @click="readSample" 
        class="
          w-full px-4 py-2
          bg-blue-100 hover:bg-blue-200
          text-slate-700 text-xl font-bold 
          border border-slate-400 rounded-md
        ">
        Read Synopsis
      </button>
    </div>
  </div>
</template>