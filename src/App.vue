<template>
  <main class="container mx-auto text-neutral-100">
    <header>
      <div class="grid grid-cols-3 p-2 pt-6 pb-6">
        <div class="text-2xl font-bold">
          <span class="text-neutral-500">&#x3C;</span>
          <span>MSumDev</span>
          <span class="text-neutral-500">/&#x3E;</span>
        </div>
        <nav class="col-span-2 flex justify-end">
          <span class="mx-8 text-xl">
            <a href="https://github.com/msumdev" target="_blank"><i class="fa-brands fa-github mr-1"></i> msumdev</a>
          </span>
          <span class="mx-8 text-xl">
            <a href="mailto:hi@mcsportfolio.com"><i class="fa-solid fa-envelope mr-1"></i> hi<span class="text-neutral-500">@</span>mcsportfolio.com</a>
          </span>
          <span class="mx-8 text-xl">
            <a href="https://www.linkedin.com/in/msumdev/" target="_blank"><i class="fa-brands fa-linkedin mr-1"></i> Michael Sumner</a>
          </span> 
        </nav>
      </div>
    </header>

    <div id="main-content-container" class="p-2 pt-8">
      <RouterView />
    </div>
  </main>
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'
</script>
