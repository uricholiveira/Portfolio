<script setup lang="ts">

const colorMode = useColorMode()

</script>

<template>
  <div class="container mx-auto mb-24 mt-40">
    <section id="home" class="flex justify-between mt-20">
      <div class="w-1/2">
        <p class="text-2xl font-bold text-gray-600">Olá, eu sou</p>
        <p class="text-4xl font-bold my-12">Urich Oliveira</p>
        <p class="text-2xl font-bold text-gray-600">Tenho 25 anos, moro no interior de São Paulo
          e atuo como Programador Backend/Fullstack</p>
      </div>
      <img src="~/public/images/giphy.gif" alt="Coding" class="rounded-xl h-[420px]">
    </section>
    <p class="text-2xl font-bold text-gray-600 mt-28">Skills</p>
    <section id="skills" class="flex justify-between mt-4 gap-4">
      <div class="w-full border p-6 rounded-md border-cyan-800 hover:bg-cyan-800 hover:text-white">
        <p class="text-2xl font-bold">Desenvolvimento de Software</p>
        <p class="text-xl font-medium pt-6">Experiência em funcional/OOP: Python, C#, Java, Java/Typescript.</p>
      </div>
      <div class="w-full border p-6 rounded-md border-orange-600 hover:bg-orange-600 hover:text-white">
        <p class="text-2xl font-bold">Observabilidade</p>
        <p class="text-xl font-medium pt-6">Monitoramento, Logs e Rastreamento.</p>
      </div>
      <div class="w-full border p-6 rounded-md border-green-600 hover:bg-green-600 hover:text-white">
        <p class="text-2xl font-bold text-center">Frontend</p>
        <p class="text-xl font-medium pt-6">Experiência usando: Vuejs, Nuxt, React, Next, e TailwindCSS.</p>
      </div>
    </section>
    <p class="text-2xl font-bold text-gray-600 mt-28">Experiência Profissional</p>
    <section id="skills" class="flex flex-wrap mt-4 gap-2">
      <div class="w-full flex justify-between border p-6 rounded-md">
        <div class="w-1/2">
          <p class="text-xl font-bold">Programador Backend Pleno @ NAVA</p>
          <div class="flex text-md font-bold mt-1 text-neutral-600">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                 class="-ml-1 text-blue-600">
              <g fill="currentColor">
                <path d="M8 9a1 1 0 1 0 0 2h8a1 1 0 1 0 0-2H8Z"/>
                <path fill-rule="evenodd"
                      d="M6 3a3 3 0 0 0-3 3v12a3 3 0 0 0 3 3h12a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3H6ZM5 18V7h14v11a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Z"
                      clip-rule="evenodd"/>
              </g>
            </svg>
            Out/2022 - Out/2023
          </div>
          <div class="flex text-md font-bold mt-2 text-neutral-600">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                 class="-ml-1 text-red-600">
              <g fill="currentColor" fill-rule="evenodd" clip-rule="evenodd">
                <path d="M16.272 10.272a4 4 0 1 1-8 0a4 4 0 0 1 8 0Zm-2 0a2 2 0 1 1-4 0a2 2 0 0 1 4 0Z"/>
                <path
                    d="M5.794 16.518a9 9 0 1 1 12.724-.312l-6.206 6.518l-6.518-6.206Zm11.276-1.691l-4.827 5.07l-5.07-4.827a7 7 0 1 1 9.897-.243Z"/>
              </g>
            </svg>
            Remoto
          </div>
          <p class="text-xl font-medium pt-6">Criando soluções através de APIs, usando C# (.NET e Entity Framework).</p>
        </div>
        <img src="~/public/images/nava.png" alt="" class="rounded-2xl h-32">
      </div>
      <div class="w-full flex justify-between border p-6 rounded-md">
        <div class="w-1/2">
          <p class="text-xl font-bold">Programador Backend Júnior @ QITECH</p>
          <p class="text-xl font-medium pt-6">Criando soluções através de APIs, usando Python (FastAPI, Falcon).</p>
        </div>
        <img src="~/public/images/qitech.png" alt="" class="rounded-2xl h-32">
      </div>
      <div class="w-full flex justify-between border p-6 rounded-md">
        <div class="w-1/2">
          <p class="text-xl font-bold">Programador Backend Trainee @ HARPO</p>
          <p class="text-xl font-medium pt-6">Criando soluções através de APIs, usando Python (FastAPI, Falcon).</p>
        </div>
        <img src="~/public/images/harpo.png" alt="" class="rounded-2xl h-32">
      </div>
    </section>
  </div>
</template>

<style scoped>

</style>
