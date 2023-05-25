<template>
  <div>
    <div class="py-20 bg-[#EBFEEB]/40">
      <div class="px-2 md:px-0 container max-w-6xl mx-auto">
        <h2
          class="text-3xl font-bold text-center underline decoration-4 underline-offset-4 decoration-sbydev-secondary mb-10">
          Our Teams
        </h2>

        <TeamsTeamList />
      </div>
    </div>
    <FooterSection />
  </div>
</template>

<script setup>
// This will also work in `<script setup>`
definePageMeta({
  layout: 'default',
  title: 'SurabayaDev - Teams',
});
</script>
