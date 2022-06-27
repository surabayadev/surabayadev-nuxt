<template>
  <div>
    <MainHero />

    <!-- Sponsor -->
    <div class="py-20 bg-[#EBFEEB]/40">
      <div class="px-2 md:px-0 container max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center underline decoration-4 underline-offset-4 decoration-sbydev-secondary mb-10">
          Sponsor
        </h2>
        <SponsorList />
      </div>
    </div>

    <!-- About Us -->
    <div class="py-20">
      <div class="px-2 md:px-0 container max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center underline decoration-4 underline-offset-4 decoration-sbydev-secondary mb-10">
          Tentang Kami
        </h2>
        <div class="flex flex-col gap-8">
          <p class="text-lg">SurabayaDev adalah komunitas IT yang membantu meningkatkan dan memanfaatkan potensi pegiat IT di seluruh Indonesia khususnya di kota Surabaya dalam bidang Teknologi, guna mendukung, untuk mewujudkan suatu kondisi yang saling melengkapi dalam rangka peningkatan keahlian, dan semangat kerjasama.</p>
          <img src="/images/about-1.png" class="rounded-lg" alt="SurabayaDev Tentang Kami">
        </div>
      </div>
    </div>

    <!-- Latest Event -->
    <div class="py-20 bg-[#EBFEEB]/40">
      <div class="px-2 md:px-0 container max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-left underline decoration-4 underline-offset-4 decoration-sbydev-secondary mb-10">
          Kegiatan Terbaru
        </h2>
        <div class="flex flex-col md:flex-row space-y-2 md:space-y-0 justify-between mb-10">
          <div class="text-lg">
            <span>Kegiatan yang dilakukan setiap sebulan sekali di kota Surabaya.</span>
            <span class="font-semibold">&nbsp; (Coming Soon)</span>
          </div>
          <a href="#" class="text-sbydev-primary font-medium underline hover:opacity-70">
            Cari tahu lebih lanjut &rarr;
          </a>
        </div>

        <Events.EventList />
      </div>
    </div>

    <!-- Latest Blog -->
    <div class="py-20">
      <div class="px-2 md:px-0 container max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-left underline decoration-4 underline-offset-4 decoration-sbydev-secondary mb-10">
          Blog Terbaru
        </h2>
        <div class="flex flex-col md:flex-row space-y-2 md:space-y-0 justify-between mb-10">
          <div class="text-lg">
            <span>Kami biasa menulis artikel setiap minggunya.</span>
            <span class="font-semibold">&nbsp; (Coming Soon)</span>
          </div>
          <a href="#" class="text-sbydev-primary font-medium underline hover:opacity-70">
            Lihat lebih banyak &rarr;
          </a>
        </div>
        <Blogs.BlogList />
      </div>
    </div>

    <FooterSection />
  </div>
</template>

<script setup>
// This will also work in `<script setup>`
definePageMeta({
  layout: "default",
  title: 'SurabayaDev - Beranda'
});
</script>