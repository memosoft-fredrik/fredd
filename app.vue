<template>
  <div class="bg-gradient-to-br from-slate-700 to-slate-800">
    <div
      class="container mx-auto h-screen text-center flex items-center justify-center text-slate-100 font-thin"
    >
      <div>
        <FredHome
          class="text-blue-400 text-center text-[400px] drop-shadow-[0_10px_80px_rgba(147,197,253,0.15)]"
          alt="Discover Fredd"
        />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import FredHome from '~/assets/svg/fredd-icon.svg';

useSeoMeta({
  title: 'fredd.no',
  ogTitle: 'fredd.no',
  description: 'This is my site, currently learning Docker',
  ogDescription: 'This is my site, currently learning Docker',
  ogImage: 'https://fredd.no/og-image.jpg',
  twitterCard: 'summary_large_image',
})
</script>
