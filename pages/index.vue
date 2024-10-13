<template>
  <div class="min-h-[calc(100vh-150px)]">
    <div class="text-[hsl(0,0%,7%)] container m-auto gap-4 grid md:grid-cols-4 md:grid-rows-6">
      <div class="flex flex-col items-center justify-center font-bold text-white bg-[hsl(256,67%,59%)] rounded p-10 md:col-start-2 md:col-end-4 md:row-start-1 md:row-end-3">
        <p class="text-[30px] text-center w-[300px] sm:w-[200px] sm:leading-7">
          Social Media <span class="text-[hsl(39,100%,71%)]">10x</span>
          <span class="italic"> Faster</span> with AI
        </p>
        <img class="w-[120px] pt-4" src="/images/illustration-five-stars.webp" alt="Illustration Five Stars">
        <p class="text-[10px] font-normal">
          Over 4,000 5-star reviews
        </p>
      </div>

      <div class="bg-[hsl(0,0%,100%)] rounded p-5 md:col-start-2 md:col-end-3 md:row-start-3 md:row-end-5">
        <img class="sm:w-[100%]" src="/images/illustration-multiple-platforms.webp" alt="Illustration Multiple Platforms">
        <p class="pt-7  font-semibold leading-5 text-[25px] md:text[20px]">
          Manage multiple accounts and platforms.
        </p>
      </div>

      <div class="bg-[hsl(39,100%,71%)] rounded pt-6 pl-6 pr-6 md:col-start-3 md:col-end-4 md:row-start-3 md:row-end-5">
        <p class="w-100 md:w-40 font-semibold text-[24px] leading-5">
          Maintain a consistent posting schedule.
        </p>
        <div class="md:h-[112px] overflow-hidden">
          <img class="mt-[54px]" src="/images/illustration-consistent-schedule.webp" alt="Illustration Consistent Schedule">
        </div>
      </div>

      <div class="bg-[hsl(254,88%,90%)] rounded p-5 overflow-hidden md:col-start-4 md:col-end-5 md:row-start-1 md:row-end-5">
        <p class="font-bold text-[20px] pb-[10px]">
          Schedule to social media.
        </p>
        <div class="w-[400px]">
          <img class="pb-[10px] h-[220px] w-[220px]" src="/images/illustration-schedule-posts.webp" alt="Illustration Schedule Posts">
        </div>
        <p class="text-[13px] font-normal">
          Optimize post timings to publish content at the perfect time for your audience.
        </p>
      </div>

      <div class="bg-[hsl(256,67%,59%)] rounded flex p-4 items-center md:col-start-3 md:col-end-5 md:row-start-5 md:row-end-7">
        <img class="w-[208px] h-max" src="/images/illustration-grow-followers.webp" alt="Illustration Grow Followers">
        <p class="text-white font-bold text-[18px]">
          Grow followers with non-stop content.
        </p>
      </div>

      <div class="bg-[hsl(0,0%,100%)] rounded p-5 flex flex-col justify-aroun md:col-start-2 md:col-end-3 md:row-start-5 md:row-end-7">
        <p class="text-[12px]">
          <span class="text-[45px] font-bold">>56%</span> faster audience growth
        </p>
        <img src="/images/illustration-audience-growth.webp" alt="Illustration Audience Growth">
      </div>

      <div class="bg-[hsl(31,66%,93%)] rounded p-5 text-[30px] md:col-start-1 md:col-end-2 md:row-start-1 md:row-end-4">
        <p class="w-[100px] font-semibold leading-6 pt-6 pb-3">
          Create and schedule content
          <span class="text-[hsl(256,67%,59%)] italic">quicker.</span>
        </p>
        <img src="/images/illustration-create-post.webp" alt="Create Post">
      </div>

      <div class="bg-[hsl(39,100%,71%)] rounded p-5 flex flex-col justify-between md:col-start-1 md:col-end-2 md:row-start-4 md:row-end-7">
        <p class="text-[25px] font-semibold leading-6">
          Write your content using AI.
        </p>
        <img src="/images/illustration-ai-content.webp" alt="Illustration Ai Content">
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
