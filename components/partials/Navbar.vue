<template>
  <div class="py-4 bg-sbydev-primary text-white">
    <div class="container max-w-6xl mx-auto flex items-center justify-between">
      <a href="/" class="hover:opacity-50">
        <img src="/logo.png" alt="SurabayaDev">
      </a>

      <div class="flex items-center space-x-6 text-lg">
        <NuxtLink to="/" class="pb-1 border-b-2 border-transparent hover:border-white">
          Beranda
        </NuxtLink>
        <NuxtLink to="/events" class="pb-1 border-b-2 border-transparent hover:border-white">
          Event
        </NuxtLink>
        <NuxtLink to="/blog" class="pb-1 border-b-2 border-transparent hover:border-white">
          Blog
        </NuxtLink>
        <NuxtLink to="/merchandise" class="pb-1 border-b-2 border-transparent hover:border-white">
          Merchandise
        </NuxtLink>
        <NuxtLink to="/about" class="pb-1 border-b-2 border-transparent hover:border-white">
          Tentang Kami
        </NuxtLink>
      </div>

      <div>
        <button type="button" class="bg-sbydev-secondary hover:bg-yellow-400 text-white py-3 px-8 rounded-full font-semibold">
          Login
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>