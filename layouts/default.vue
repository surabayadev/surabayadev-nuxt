<script setup>
const route = useRoute()
</script>

<template>
  <div class="font-poppins">
    <Html>
      <Title>{{ route.meta.title }}</Title>
    </Html>

    <div class="flex flex-col h-screen">

      <MainNavbar />

      <!-- <FooterSection/> -->

      <slot />
    </div>
  </div>
</template>