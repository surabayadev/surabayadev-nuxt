<template>
  <div class="grid grid-cols md:grid-cols-4 gap-4">
    <div
      class="flex flex-col border rounded-lg overflow-hidden"
      v-for="team in teams">
      <!-- <a href="#" class="flex mb-2 hover:opacity-70"> -->
      <!-- src={{ team.image }} -->
      <!-- </a> -->
      <img
        :src="team.image"
        class="object-fill hover:opacity-70"
        :alt="team.name + ' ' + team.role" />
      <div class="flex flex-col p-2 pb-6 bg-white">
        <a
          href=""
          class="text-lg mb-4 font-medium text-sbydev-primary hover:underline hover:opacity-70 line-clamp-2">
          {{ team.name }}
        </a>
        <div class="flex flex-col items-start space-y-2 text-sm">
          <span class="flex items-center gap-2">
            <UserCircleIcon class="w-5 h-5" />
            <span>
              {{ team.role }}
            </span>
          </span>
          <span class="flex items-center gap-2">
            <!-- <ClockIcon class="w-5 h-5" /> -->
            <!-- <span>16:00 - 18:00</span> -->
          </span>
          <a
            href="#"
            class="flex items-center gap-2 text-sbydev-primary underline hover:opacity-70">
            <!-- <VideoCameraIcon class="w-5 h-5" /> -->
            <!-- <span>Meeting Link</span> -->
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import {
  CalendarIcon,
  ClockIcon,
  UserCircleIcon,
  VideoCameraIcon,
} from '@heroicons/vue/outline';

export default {
  components: { CalendarIcon, ClockIcon, VideoCameraIcon, UserCircleIcon },
  data() {
    return {
      teams: [
        {
          image: 'https://shorturl.at/crIU6',
          name: 'Fatoni',
          role: 'Founder',
        },
        {
          image: 'https://shorturl.at/crzAT',
          name: 'Antoni',
          role: 'Founder',
        },
        {
          image: 'https://shorturl.at/qX034',
          name: 'Aryangga',
          role: 'Founder',
        },
        {
          image: 'https://shorturl.at/abNRT',
          name: 'Sawitry',
          role: 'Community Manager',
        },
        //
      ],
    };
  },
};
</script>

<style></style>
