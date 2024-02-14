<template>
  <div class="bg-gradient-to-br from-slate-700 to-slate-800">
    <div
      class="container mx-auto h-screen text-center flex items-center justify-center text-slate-100 font-thin"
    >
      <div>
        <FredHome
          class="text-blue-400 text-center text-[400px] hover:text-blue-400/80 hover:text-[390px] drop-shadow-[0_10px_80px_rgba(147,197,253,0.15)] ease-in-out duration-200"
          alt="Discover Fredd"
        />
        <h1 class="font-thin text-4xl pt-12">Fredd.no</h1>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import FredHome from '~/assets/svg/fredd-icon.svg';
</script>
