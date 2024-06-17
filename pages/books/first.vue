<script setup>
const payForBook = () => {
  alert('Payment process initiated!');
};

const readSample = () => {
  window.open('path/to/sample.pdf', '_blank');
};
</script>

<template>
  <div class="container mx-auto p-10 max-w-2xl">
    <header class="text-center mb-8">
      <figure class="flex justify-center hover:opacity-95 rounded">
        <img src="assets/img/chave.png" alt="Book Cover" class="w-auto h-auto max-h-96 border-2 hover:border-emerald-500">
      </figure>
    </header>

    <div class="flex justify-center space-x-4 mb-8">
      <button 
        @click="payForBook" 
        class="px-4 py-2 
        bg-yellow-400 hover:bg-yellow-500
        text-slate-700 text-xl font-bold 
        border border-yellow-500 rounded-md">
        Buy Now ($39)
      </button>
      <button 
        @click="readSample"
        class="px-4 py-2
        bg-blue-100 hover:bg-blue-200
        text-slate-700 text-xl font-bold 
        border border-slate-400 rounded-md">
        Read Sample PDF
      </button>
    </div>

    <section class="text-gray-700 tracking-wide mb-8">
      <h2 class="text-2xl font-bold mb-4">Synopsis</h2>
      <p class="mb-4">
        Lohan and his friends are invited to participate in the exciting Cipher Tournament, organized by a renowned fictional TV channel. This competition brings together the brightest young cryptographers in the world, aged between 12 and 18, challenging them to decipher complex codes and create their own unbreakable ciphers. Divided into teams, the participants face challenges that test not only their cryptanalytic skills but also their creativity and teamwork abilities.
      </p>
      <p class="mb-4">
        Throughout the tournament, Lohan and his team employ a wide range of cryptographic techniques, from the classic Caesar cipher to more advanced methods like the Trithemius cipher.
      </p>
      <p class="mb-4">
        This story highlights the importance of teamwork, honesty and passion for knowledge, as the young protagonists try to triumph in a competition that demands the utmost of their intellectual and cryptographic abilities.
      </p>
    </section>

    <section>
      <h2 class="text-2xl font-bold mb-4">Table of Contents</h2>
      <ul class="list-disc pl-4">
        <li>Chapter 1: Prelude</li>
        <li>Chapter 2: Invitation</li>
        <li>Chapter 3: Towards Terebi Spiel</li>
        <li>Chapter 4: Voyage's End</li>
        <li>Chapter 5: First Pre Match</li>
        <li>Chapter 7: First Match</li>
        <li>Chapter 8: Second Pre Match</li>
        <li>Chapter 9: Second Match</li>
        <li>Chapter 10: Pre Semifinal</li>
        <li>Chapter 11: Semifinal</li>
        <li>Chapter 12: Pre Final</li>
        <li>Chapter 13: Final</li>
        <li>Chapter 14: Banquet</li>
      </ul>
    </section>
  </div>
</template>