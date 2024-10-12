<template>
  <div class="min-h-[calc(100vh-150px)]">
    <div class="text-[hsl(0,0%,7%)] container m-auto gap-4 grid md:grid-cols-4 md:grid-rows-6">
      <div class="bg-[hsl(31,66%,93%)] md:row-span-3 h-[280px] rounded p-5 text-[30px]">
        <p class="w-[100px] font-semibold leading-6 pt-6 pb-3">
          Create and schedule content
          <span class="text-[hsl(256,67%,59%)] italic">quicker.</span>
        </p>
        <img src="/images/illustration-create-post.webp" alt="Create Post">
      </div>
      <div class="flex flex-col items-center  font-bold text-white bg-[hsl(256,67%,59%)] md:col-span-2 md:row-span-2 rounded p-10">
        <p class="text-[30px]">
          Social Media <span class="text-[hsl(39,100%,71%)]">10x</span>
        </p>
        <p class="text-[30px]">
          <span class="italic">Faster</span> with AI
        </p>
        <img class="w-[120px]" src="/images/illustration-five-stars.webp" alt="Illustration Five Stars">
        <p class="text-[10px] font-normal">
          Over 4,000 5-star reviews
        </p>
      </div>
      <div class="bg-[hsl(254,88%,90%)] md:row-span-4 rounded p-5 overflow-hidden">
        <p class="font-bold text-[20px] pb-[10px]">
          Schedule to social media.
        </p>
        <img class="pb-[10px]" src="/images/illustration-schedule-posts.webp" alt="Illustration Schedule Posts">
        <p class="text-[13px] font-semibold">
          Optimize post timings to publish content at the perfect time for your audience.
        </p>
      </div>
      <div class="bg-[hsl(0,0%,100%)] md:row-span-2 rounded">
        <img src="/images/illustration-multiple-platforms.webp" alt="Illustration Multiple Platforms">
        <p>
          Manage multiple accounts and platforms.
        </p>
      </div>
      <div class="bg-[hsl(39,100%,71%)] md:row-span-2 rounded">
        <p>
          Maintain a consistent posting schedule.
        </p>
      </div>
      <div class="bg-[hsl(39,100%,71%)] md:row-span-3 rounded">
        <p>
          Write your content using AI.
        </p>
      </div>
      <div class="bg-[hsl(0,0%,100%)] md:row-span-2 rounded">
        <p>
          >56% faster audience growth
        </p>
      </div>
      <div class="bg-[hsl(256,67%,59%)] md:row-span-2 md:col-span-2 rounded">
        <p>
          Grow followers with non-stop content.
        </p>
      </div>
    </div>
    <div>
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge">Frontend Mentor</a>.
      Coded by <a href="#">Your Name Here</a>.
    </div>
  </div>
</template>

<script setup lang="ts">
import { useHead } from 'nuxt/app'

useHead({
  title: 'Bento Grid',
  link: [
    { rel: 'icon', href: '/images/favicon-32x32.ico', type: 'image/x-icon' },
    { rel: 'apple-touch-icon', href: '/images/favicon-32x32.png' } // Opcional para dispositivos Apple
  ],
  meta: [
    { name: 'description', content: 'Desafio Frontend Mentor Bento Grid usando Nuxtjs 3 e Sidebase' },
    { property: 'og:title', content: 'Bento Grid' },
    { property: 'og:description', content: 'Desafio Frontend Mentor Bento Grid usando Nuxtjs 3 e Sidebase' },
    { property: 'og:image', content: '/assets/images/favicon-32x32.png' }
  ]
})
</script>
