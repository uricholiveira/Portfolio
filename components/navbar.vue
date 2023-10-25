<script setup lang="ts">
useHead({
  htmlAttrs: {
    class: 'scroll-smooth'
  },
})
const colorMode = useColorMode()

const isDark = computed({
  get() {
    return colorMode.value === 'dark'
  },
  set() {
    colorMode.preference = colorMode.value === 'dark' ? 'light' : 'dark'
  }
})
</script>

<template>
  <nav class="">
    <div class="max-w-screen-xl pt-8 flex flex-wrap items-center justify-between mx-auto text-lg font-medium">
      <NuxtLink to="/" class="items-center">
        <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white"></span>
      </NuxtLink>
      <div class="flex justify-end gap-10 items-center">
        <NuxtLink to="#home">Home</NuxtLink>
        <NuxtLink to="#skills">Skills</NuxtLink>
        <NuxtLink to="#experience">Experiência</NuxtLink>
        <NuxtLink to="#projects">Projetos</NuxtLink>
        <NuxtLink to="#blog">Blog</NuxtLink>
      </div>
      <div class="items-baseline">
        <NuxtLink to="#contact">Contato</NuxtLink>
      </div>
    </div>
  </nav>
</template>

<style scoped>

</style>
