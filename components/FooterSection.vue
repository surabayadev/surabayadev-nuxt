<template>
  <div>
    <div class="py-10 md:py-16 bg-sbydev-primary/95 text-white">
      <div class="px-2 md:px-0 container max-w-6xl mx-auto">
        <div class="flex flex-col md:flex-row space-y-10 md:space-y-0 justify-between mb-10">
          <div class="flex-1">
            <h4 class="text-xl font-medium mb-6">Kontak Kami</h4>
            <div class="flex flex-col space-y-4">
              <a href="mailto:pr.surabayadev@gmail.com" class="flex items-center gap-3 hover:underline">
                <InboxIcon class="w-5 h-5" />
                <span>pr.surabayadev@gmail.com</span>
              </a>
              <a href="https://wa.me/+6281242313432" class="flex items-center gap-3 hover:underline">
                <PhoneIcon class="w-5 h-5" />
                <span>0812-4231-3432</span>
              </a>
            </div>
          </div>
          
          <div class="flex-1">
            <h4 class="text-xl font-medium mb-6">Follow Sosial Media Kami</h4>
            <div class="flex flex-col items-start space-y-4">
              <a href="https://facebook.com/surabayadev" target="_blank" class="flex items-center gap-3 hover:underline">
                <CubeIcon class="w-5 h-5" />
                <span>facebook.com/surabayadev</span>
              </a>
              <a href="https://twitter.com/surabayadev" target="_blank" class="flex items-center gap-3 hover:underline">
                <CubeIcon class="w-5 h-5" />
                <span>twitter.com/surabayadev</span>
              </a>
              <a href="https://instagram.com/surabayadev" target="_blank" class="flex items-center gap-3 hover:underline">
                <CubeIcon class="w-5 h-5" />
                <span>instagram.com/surabayadev</span>
              </a>
              <a href="https://t.me/surabayadev" target="_blank" class="flex items-center gap-3 hover:underline">
                <CubeIcon class="w-5 h-5" />
                <span>t.me/surabayadev</span>
              </a>
            </div>
          </div>

          <div class="flex-1 flex flex-col items-center justify-center space-y-6">
            <img src="/logo.png" alt="">
            <div class="space-y-4 text-center">
              <p class="text-lg italic font-semibold">"Learn Better Together"</p>
              <p>Built with ❤️ by your Friends</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="py-4 md:py-6 bg-sbydev-primary">
      <div class="px-2 md:px-0 container max-w-6xl mx-auto text-center md:text-right text-gray-200">
        Copyright &copy; SurabayaDev 2022
      </div>
    </div>
  </div>
</template>

<script>
import { InboxIcon, PhoneIcon, CubeIcon } from '@heroicons/vue/outline'

export default {
  components: {
    InboxIcon, PhoneIcon, CubeIcon
  }
}
</script>

<style>

</style>