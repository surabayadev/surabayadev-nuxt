<template>
  <div class="grid grid-cols md:grid-cols-4 gap-4">
    <div
      class="flex flex-col border rounded-lg overflow-hidden bg-white"
      v-for="team in teams">
      <img
        :src="team.image"
        class="object-fill hover:opacity-70"
        :alt="team.name + ' ' + team.role" />
      <div class="flex flex-col p-2 pb-6">
        <div class="flex justify-start">
          <a
            :href="team.linkedin"
            class="text-lg mb-4 font-medium text-sbydev-primary hover:underline hover:opacity-70 line-clamp-2">
            {{ team.name }}
          </a>
        </div>
        <div class="flex flex-col items-start space-y-2 text-sm">
          <span class="flex items-center gap-2">
            <UserCircleIcon class="w-5 h-5" />
            <span>
              {{ team.role }}
            </span>
          </span>
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
  BadgeCheckIcon,
} from '@heroicons/vue/outline';

export default {
  components: {
    CalendarIcon,
    ClockIcon,
    VideoCameraIcon,
    UserCircleIcon,
    BadgeCheckIcon,
  },
  data() {
    return {
      teams: [],
    };
  },
  mounted() {
    fetch('./components/Teams/teamData.json')
      .then((response) => response.json())
      .then((data) => {
        this.teams = data;
      })
      .catch((error) => {
        console.error('Error:', error);
      });
  },
};
</script>

<style></style>
