<script setup lang="ts">
definePageMeta({
  scrollToTop: true
})

const colorMode = useColorMode()

const scrollTop = () => {
  scrollTo({left: 0, top: 0, behavior: 'smooth'})
}


</script>

<template>
  <div class="container mx-auto mb-24 mt-40">
    <section id="home" class="flex justify-between mt-20">
      <div class="w-1/2">
        <p class="text-2xl font-bold text-gray-600">Olá, meu nome é</p>
        <p class="text-4xl font-bold my-12">Urich Oliveira</p>
        <p class="text-2xl font-bold text-gray-600">Tenho 25 anos, moro no interior de São Paulo
          e atuo como programador fullstack <span class="animate-pulse">(mais puxado pro backend 🤣)</span></p>
      </div>
      <img src="~/public/images/giphy.gif" alt="Coding" class="rounded-xl h-[420px]">
    </section>
    <p id="skills" class="text-2xl font-bold text-gray-600 mt-28">Skills</p>
    <section class="flex justify-between mt-4 gap-4">
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
    <p id="experience" class="text-2xl font-bold text-gray-600 mt-28">Experiência Profissional</p>
    <section class="flex flex-wrap mt-4 gap-2">
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
          <p class="text-xl font-medium pt-6">Criava soluções através de APIs, usando C# (.NET e Entity Framework).</p>
        </div>
        <img src="~/public/images/nava.png" alt="" class="rounded-2xl h-32">
      </div>
      <div class="w-full flex justify-between border p-6 rounded-md">
        <div class="w-1/2">
          <p class="text-xl font-bold">Programador Backend Júnior @ QITECH</p>
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
            Jun/2021 - Out/2022
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
          <p class="text-xl font-medium pt-6">Criava soluções através de APIs/Automações usando Python (FastAPI,
            Falcon).Trabalhei diretamente na área de LaaS e BaaS.</p>
        </div>
        <img src="~/public/images/qitech.png" alt="" class="rounded-2xl h-32">
      </div>
      <div class="w-full flex justify-between border p-6 rounded-md">
        <div class="w-1/2">
          <p class="text-xl font-bold">Programador Backend Trainee @ HARPO</p>
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
            Mar/2020 - Jun/2021
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
          <p class="text-xl font-medium pt-6">Apoiei desenvolvimentos internos em Electron, Vue.js, Flask. Além de
            desenvolver uma skill da Alexa (B2C).</p>
        </div>
        <img src="~/public/images/harpo.png" alt="" class="rounded-2xl h-32">
      </div>
    </section>
    <p id="projects" class="text-2xl font-bold text-gray-600 mt-28">Projetos</p>
    <section class="grid grid-cols-2 mt-4 gap-4">
      <img src="~/public/images/giphy.gif" alt="Coding" class="rounded-xl h-[420px]">
      <div class="w-1/2">
        <h2 class="text-4xl font-bold">Polygon Store</h2>
        <p class="text-xl font-medium mt-2">Uma plataforma para compra de gift cards.</p>
        <p class="text-xl font-medium mt-4 flex gap-4">
          <span
              class="inline-flex items-center rounded-md bg-green-400 px-4 py-1 text-lg font-medium text-white ring-1 ring-inset ring-gray-500/10">Nuxt</span>
          <span
              class="inline-flex items-center rounded-md bg-black px-2 py-1 text-lg font-medium text-white ring-1 ring-inset ring-gray-500/10">Nextjs</span>
          <span
              class="inline-flex items-center rounded-md bg-cyan-700 px-2 py-1 text-lg font-medium text-white ring-1 ring-inset ring-gray-500/10">Prisma</span>
        </p>
      </div>
    </section>
    <p id="blog" class="text-2xl font-bold text-gray-600 mt-28">Blog</p>
    <section class="flex justify-center mt-4 gap-4">
      <h1 class="text-2xl font-bold animate-pulse">Em construção...</h1>
    </section>
    <p id="contact" class="text-2xl font-bold text-gray-600 mt-28">Contato</p>
    <p class="text-md font-bold text-gray-600 mt-12">Não hesite em trocar uma ideia. <br>Você pode me encontrar através
      dos links abaixo, ou preenchendo o formulário.</p>
    <section class="flex justify-between mt-4 gap-4">
      <div class="w-1/2">
        <div class="inline-flex rounded-md shadow-sm mb-4" role="group">
          <button type="button"
                  class="inline-flex items-center px-4 py-2 text-sm font-medium text-gray-900 bg-white border border-gray-200 rounded-l-lg hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-2 focus:ring-blue-700 focus:text-blue-700 dark:bg-gray-700 dark:border-gray-600 dark:text-white dark:hover:text-white dark:hover:bg-gray-600 dark:focus:ring-blue-500 dark:focus:text-white"
                  @click="navigateTo('https://www.linkedin.com/in/urich-oliveira/', {external: true})"
          >
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
              <path fill="currentColor"
                    d="M19 3a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14m-.5 15.5v-5.3a3.26 3.26 0 0 0-3.26-3.26c-.85 0-1.84.52-2.32 1.3v-1.11h-2.79v8.37h2.79v-4.93c0-.77.62-1.4 1.39-1.4a1.4 1.4 0 0 1 1.4 1.4v4.93h2.79M6.88 8.56a1.68 1.68 0 0 0 1.68-1.68c0-.93-.75-1.69-1.68-1.69a1.69 1.69 0 0 0-1.69 1.69c0 .93.76 1.68 1.69 1.68m1.39 9.94v-8.37H5.5v8.37h2.77Z"/>
            </svg>
          </button>
          <button type="button"
                  class="inline-flex items-center px-4 py-2 text-sm font-medium text-gray-900 bg-white border border-gray-200 rounded-r-md hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-2 focus:ring-blue-700 focus:text-blue-700 dark:bg-gray-700 dark:border-gray-600 dark:text-white dark:hover:text-white dark:hover:bg-gray-600 dark:focus:ring-blue-500 dark:focus:text-white"
                  disabled
          >
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
              <path fill="currentColor"
                    d="M12.04 2c-5.46 0-9.91 4.45-9.91 9.91c0 1.75.46 3.45 1.32 4.95L2.05 22l5.25-1.38c1.45.79 3.08 1.21 4.74 1.21c5.46 0 9.91-4.45 9.91-9.91c0-2.65-1.03-5.14-2.9-7.01A9.816 9.816 0 0 0 12.04 2m.01 1.67c2.2 0 4.26.86 5.82 2.42a8.225 8.225 0 0 1 2.41 5.83c0 4.54-3.7 8.23-8.24 8.23c-1.48 0-2.93-.39-4.19-1.15l-.3-.17l-3.12.82l.83-3.04l-.2-.32a8.188 8.188 0 0 1-1.26-4.38c.01-4.54 3.7-8.24 8.25-8.24M8.53 7.33c-.16 0-.43.06-.66.31c-.22.25-.87.86-.87 2.07c0 1.22.89 2.39 1 2.56c.14.17 1.76 2.67 4.25 3.73c.59.27 1.05.42 1.41.53c.59.19 1.13.16 1.56.1c.48-.07 1.46-.6 1.67-1.18c.21-.58.21-1.07.15-1.18c-.07-.1-.23-.16-.48-.27c-.25-.14-1.47-.74-1.69-.82c-.23-.08-.37-.12-.56.12c-.16.25-.64.81-.78.97c-.15.17-.29.19-.53.07c-.26-.13-1.06-.39-2-1.23c-.74-.66-1.23-1.47-1.38-1.72c-.12-.24-.01-.39.11-.5c.11-.11.27-.29.37-.44c.13-.14.17-.25.25-.41c.08-.17.04-.31-.02-.43c-.06-.11-.56-1.35-.77-1.84c-.2-.48-.4-.42-.56-.43c-.14 0-.3-.01-.47-.01Z"/>
            </svg>
          </button>
        </div>
        <img src="~/public/images/giphy_2.gif" alt="Coding" class="rounded-xl h-[420px]">
      </div>
      <div class="w-1/2">
        <div class="grid grid-cols-1 gap-x-6 gap-y-2">
          <div class="sm:col-span-3">
            <label for="first-name" class="block text-md font-medium leading-6 text-gray-900">Nome</label>
            <div class="mt-2">
              <input type="text" name="first-name" id="first-name" autocomplete="given-name"
                     class="px-2 block w-1/2 rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-1 focus:ring-inset focus:ring-indigo-600 sm:text-md sm:leading-6">
            </div>
          </div>
          <div class="sm:col-span-3">
            <label for="first-name" class="block text-md font-medium leading-6 text-gray-900">Email</label>
            <div class="mt-2">
              <input type="text" name="first-name" id="first-name" autocomplete="given-name"
                     class="px-2 block w-1/2 rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-1 focus:ring-inset focus:ring-indigo-600 sm:text-md sm:leading-6">
            </div>
          </div>
          <div class="sm:col-span-3">
            <label for="first-name" class="block text-md font-medium leading-6 text-gray-900">Celular</label>
            <div class="mt-2">
              <input type="text" name="first-name" id="first-name" autocomplete="given-name"
                     class="px-2 block w-1/2 rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-1 focus:ring-inset focus:ring-indigo-600 sm:text-md sm:leading-6">
            </div>
          </div>
          <div class="col-span-full">
            <label for="about" class="block text-md font-medium leading-6 text-gray-900">Mensagem</label>
            <div class="mt-2">
              <textarea id="about" name="about" rows="3"
                        class="px-2 block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-1 focus:ring-inset focus:ring-indigo-600 sm:text-md sm:leading-6"></textarea>
            </div>
            <!--            <p class="mt-3 text-md leading-6 text-gray-600">Write a few sentences about yourself.</p>-->
          </div>
        </div>
        <div class="mt-6 flex items-center justify-start gap-x-6">
          <button type="submit"
                  class="w-40 rounded-md bg-indigo-600 px-3 py-2 text-md font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">
            Enviar
          </button>
        </div>
      </div>
    </section>
    <button
        type="button"
        data-te-ripple-init
        data-te-ripple-color="light"
        class="!fixed bottom-5 right-5 rounded-full bg-cyan-900 p-3 text-xs font-medium uppercase leading-tight text-white
        shadow-md transition duration-150 ease-in-out hover:bg-cyan-700 hover:shadow-lg focus:bg-cyan-700 focus:shadow-lg
        focus:outline-none focus:ring-0 active:bg-cyan-800 active:shadow-lg"
        @click="scrollTop"
        id="btn-back-to-top">
      <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fas"
          class="h-4 w-4"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 448 512">
        <path
            fill="currentColor"
            d="M34.9 289.5l-22.2-22.2c-9.4-9.4-9.4-24.6 0-33.9L207 39c9.4-9.4 24.6-9.4 33.9 0l194.3 194.3c9.4 9.4 9.4 24.6 0 33.9L413 289.4c-9.5 9.5-25 9.3-34.3-.4L264 168.6V456c0 13.3-10.7 24-24 24h-32c-13.3 0-24-10.7-24-24V168.6L69.2 289.1c-9.3 9.8-24.8 10-34.3.4z"></path>
      </svg>
    </button>
  </div>
</template>

<style scoped>

</style>
