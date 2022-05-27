<template>
  <div>
    <PartialsLandingSection>
      <div class="container mx-auto">
        <PartialsHero />
      </div>
    </PartialsLandingSection>

    <PartialsLandingSection>
      <div class="container mx-auto">
        Section Sponsor
      </div>
    </PartialsLandingSection>

    <PartialsLandingSection>
      <div class="container mx-auto">
        About US
      </div>
    </PartialsLandingSection>

    <PartialsLandingSection>
      <div class="container mx-auto">
        <h2 class="text-3xl font-bold capitalize text-sbydev-primary">Kegiatan <span
            class="border-b-4 border-sbydev-primary">terbaru</span></h2>
        <div class="flex justify-between">
          <p class="my-4">Kegiatan yang dilakukan setiap sebulan sekali di kota Surabaya</p>
          <a href="#" class="text-sbydev-primary flex items-center gap-1">Cari tau lebih lanjut
            <IconsArrowRight class="h-6" />
          </a>
        </div>

        <div class="grid grid-cols-4">
          <EventCard  v-for="(item, index) in [0, 1, 2, 3]" :key="index" :event-data="item" />
        </div>

      </div>
    </PartialsLandingSection>

    <PartialsLandingSection>
      <div class="container mx-auto">
        <div class="flex justify-center flex-col gap-4 mb-10">
          <h2 class="font-bold text-4xl text-center">Blog</h2>
          <p class="text-xl text-center">Kegiatan yang dilakukan setiap bulan dari komunitas SurabayaDev</p>
        </div>
        <div class="grid grid-cols-4 gap-x-14">
          <BlogCard  v-for="(item, index) in [0, 1, 2, 3]" :key="index" :event-data="item"  />
        </div>
      </div>
    </PartialsLandingSection>

  </div>
</template>

<script>

export default {
    name: "IndexPage",
}
</script>
