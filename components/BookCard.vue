<script setup>
const payForBook = () => {
  alert('Payment process initiated!');
};
</script>

<template>
  <div class="max-w-md bg-white rounded-lg shadow-md p-4">
    <figure class="border-2 hover:border-emerald-500 hover:opacity-95 bg-black rounded">
      <img src="assets/img/chave.png" alt="Book Cover" class="w-full h-[16rem] object-contain shadow-md">
    </figure>
    <div class="p-6">
      <h1 class="text-2xl font-light tracking-wide">Lohan and the Cipher Tournament</h1>
      <br>
      <p class="text-gray-700 mb-6 tracking-wide">
        I wrote this young adult book to showcase the fascinating world of cryptography, which is filled with suspense, mystery, and adventures that inspire readers to explore the world of codes and ciphers. It's a read for anyone who enjoys intellectual challenges and the thrill of cryptographic discoveries.
      </p>
      <button 
        @click="payForBook" 
        class="w-full px-4 py-2 
        bg-yellow-400 hover:bg-yellow-500
        text-slate-700 text-xl font-bold 
        border border-yellow-500 rounded-md mb-4">
        Buy Now ($39)
      </button>
      <NuxtLink to="/books/first" class="block w-full">
        <button 
          class="
            w-full px-4 py-2
            bg-blue-100 hover:bg-blue-200
            text-slate-700 text-xl font-bold 
            border border-slate-400 rounded-md
          ">
          Read a Sample/Synopsis
        </button>
      </NuxtLink>
    </div>
  </div>
</template>