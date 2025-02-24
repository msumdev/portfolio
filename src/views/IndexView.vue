<template>
  <section id="main-content">
    <div class="text-4xl">
      <p>Hello!</p>
      <p class="text-blue-400 font-bold">I make and break things.</p>
    </div>

    <p class="text-neutral-500 w-full max-w-[60%]">I'm a software engineer based in the United Kingdom with experience across a variety of projects and programming languages. I specialize in building, modernizing, and maintaining backends, ensuring scalable, efficient, and high-performing systems.</p>
  </section>
  
  <section id="professional-work" class="pt-8">
    <p class="text-neutral-400"><i class="fa-solid fa-arrow-down mr-4"></i> Professional Work</p>

    <CardComponent />
  </section>
</template>

<script>
import CardComponent from '@/components/CardComponent.vue'

export default {
  components: {
    CardComponent
  }
}
</script>

