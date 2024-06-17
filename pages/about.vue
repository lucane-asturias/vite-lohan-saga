<script setup>
// No need for any script logic for now.
</script>

<template>
  <div class="container mx-auto p-10 max-w-2xl">
    <section class="mb-8">
      <img 
        src="https://lh3.googleusercontent.com/a/ACg8ocL0ytlG_Lm3DlTaKVayTyAFAq6RmRpUmi62ks6JCfT8Ocq_muYC=s288-c-no" 
        alt="Lucas Maciel" 
        class="my_photo w-52 h-52 rounded-full mx-auto"
      >
    </section>

    <section class="mb-8">
      <h1 class="text-2xl font-semibold mb-4 text-gray-800">About Me</h1>
      <p class="text-gray-700 text-base/7">
        Hello! My name is Lucas Maciel (pseudonym Lucane Asturias). I'm 23 years old at the time of writing and I'm a new author. 
        I created this site to host my first book, which I estimate will be the first in a trilogy.
      </p>
    </section>

    <section class="mb-8">
      <div class="space-y-2">
        <h2 class="text-2xl font-semibold mb-4 text-gray-800">Details</h2>
        <p class="text-gray-700">Email: <a href="mailto:baallucane@gmail.com" class="text-blue-500 hover:underline">baallucane@gmail.com</a> - my preferred contact method</p>
      </div>
    </section>

    <section class="mb-8">
      <div class="space-y-2">
        <h2 class="text-2xl font-semibold mb-4 text-gray-800">The first book</h2>
        
        <div class="max-w-sm bg-white rounded-lg mr-4 cursor-pointer">
          <figure class="w-40 h-40 border-2 hover:border-emerald-500 hover:opacity-95 bg-black rounded">
            <img 
              src="assets/img/chave.png" 
              alt="Book Cover"
              class="shadow-lg border border-gray-400 object-cover"
              title="Lohan and the Cipher Tournament"
            >
          </figure>
        </div>

      </div>
    </section>
  </div>
</template>

<style scoped>
.my_photo {
    border: 1px solid #b9b9b9;
    box-shadow: 0px 0px 30px 1px #aaa;
    border: 1px solid #999;
}
</style>