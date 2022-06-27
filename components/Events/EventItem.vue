<template>
  <div class="flex flex-col border rounded-lg overflow-hidden">
    <a href="#" class="flex h-60 md:h-72 mb-2 hover:opacity-70">
      <img src="/images/event-1.jpeg" class="object-cover" alt="SurabayaDev Event">
    </a>
    <div class="flex flex-col p-2 pb-6 bg-white">
      <a href="" class="text-lg mb-4 font-medium text-sbydev-primary hover:underline hover:opacity-70 line-clamp-2">
        Mengenal Design Thinking lebih dekat
      </a>
      <div class="flex flex-col items-start space-y-2 text-sm">
        <span class="flex items-center gap-2">
          <CalendarIcon class="w-5 h-5" />
          <span>24 Mei 2022</span>
        </span>
        <span class="flex items-center gap-2">
          <ClockIcon class="w-5 h-5" />
          <span>16:00 - 18:00</span>
        </span>
        <a href="#" class="flex items-center gap-2 text-sbydev-primary underline hover:opacity-70">
          <VideoCameraIcon class="w-5 h-5" />
          <span>Meeting Link</span>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import { CalendarIcon, ClockIcon, VideoCameraIcon } from '@heroicons/vue/outline'

export default {
  components: { CalendarIcon, ClockIcon, VideoCameraIcon }
}
</script>

<style>

</style>