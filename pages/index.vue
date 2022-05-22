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
          <div class="mt-2 w-72">
            <img class="h-80 w-72 object-cover rounded-xl"
              src="https://s3-alpha-sig.figma.com/img/c51d/5a17/7bc91c636c83e3e675d2b87a71fb6edd?Expires=1653868800&Signature=EzscYfMvDrSKxKxWb-MMlMvxDcBFucx70TJ7PLCbwbDLzS~OHa-YsE8VMJfpe1Fj~RjB72qS9DjZVYXM3l6cfvxKcX-f8a3WRyQV5Y42yo5m-O432pcETIMnOrn8ddf6HLIoGzQtikv-Skh0adFPHk9GHtxpscrBbgTlIwFdFnawCKR6td7dm542wIFLyeFJyQuobQYg6hE7Egk8ilvV-5W~zKIaF6CxO6Y3fg4Ik6Xkix3G9CjjVfStnGB~IfYm2yn97r~64ptO8eQMR7Fc-28WpnX-RmGwIrr~qIOxi5divSkBy8sF~LPgxCosiiVh2XeeCS5uhyP7X8LO5xgClg__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
              alt="event">
            <h3 class="capitalize font-bold mt-4 mb-2 text-xl">mengenal design thinking lebih dekat</h3>
            <div class="flex flex-col gap-2">
              <div class="flex gap-2">
                <IconsCalendar class="h-4 text-blue-400" />
                <p class="text-sm">24 Mei 2022</p>
              </div>
              <div class="flex gap-2">
                <IconsClock class="h-4 text-blue-400" />
                <p class="text-sm">16.00 - 18.00 PM</p>
              </div>
              <div class="flex gap-2">
                <IconsVidio class="h-4 text-blue-400" />
                <p class="text-sm uppercase">zoom meeting</p>
              </div>
              <button class="px-4 py-2 mt-4 bg-sbydev-primary rounded-md text-white">Lihat Detail</button>
            </div>
          </div>
          <div class="mt-2 w-72">
            <img class="h-80 w-72 object-cover rounded-xl"
              src="https://s3-alpha-sig.figma.com/img/c51d/5a17/7bc91c636c83e3e675d2b87a71fb6edd?Expires=1653868800&Signature=EzscYfMvDrSKxKxWb-MMlMvxDcBFucx70TJ7PLCbwbDLzS~OHa-YsE8VMJfpe1Fj~RjB72qS9DjZVYXM3l6cfvxKcX-f8a3WRyQV5Y42yo5m-O432pcETIMnOrn8ddf6HLIoGzQtikv-Skh0adFPHk9GHtxpscrBbgTlIwFdFnawCKR6td7dm542wIFLyeFJyQuobQYg6hE7Egk8ilvV-5W~zKIaF6CxO6Y3fg4Ik6Xkix3G9CjjVfStnGB~IfYm2yn97r~64ptO8eQMR7Fc-28WpnX-RmGwIrr~qIOxi5divSkBy8sF~LPgxCosiiVh2XeeCS5uhyP7X8LO5xgClg__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
              alt="event">
            <h3 class="capitalize font-bold mt-4 mb-2 text-xl">mengenal design thinking lebih dekat</h3>
            <div class="flex flex-col gap-2">
              <div class="flex gap-2">
                <IconsCalendar class="h-4 text-blue-400" />
                <p class="text-sm">24 Mei 2022</p>
              </div>
              <div class="flex gap-2">
                <IconsClock class="h-4 text-blue-400" />
                <p class="text-sm">16.00 - 18.00 PM</p>
              </div>
              <div class="flex gap-2">
                <IconsVidio class="h-4 text-blue-400" />
                <p class="text-sm uppercase">zoom meeting</p>
              </div>
              <button class="px-4 py-2 mt-4 bg-sbydev-primary rounded-md text-white">Lihat Detail</button>
            </div>
          </div>
          <div class="mt-2 w-72">
            <img class="h-80 w-72 object-cover rounded-xl"
              src="https://s3-alpha-sig.figma.com/img/c51d/5a17/7bc91c636c83e3e675d2b87a71fb6edd?Expires=1653868800&Signature=EzscYfMvDrSKxKxWb-MMlMvxDcBFucx70TJ7PLCbwbDLzS~OHa-YsE8VMJfpe1Fj~RjB72qS9DjZVYXM3l6cfvxKcX-f8a3WRyQV5Y42yo5m-O432pcETIMnOrn8ddf6HLIoGzQtikv-Skh0adFPHk9GHtxpscrBbgTlIwFdFnawCKR6td7dm542wIFLyeFJyQuobQYg6hE7Egk8ilvV-5W~zKIaF6CxO6Y3fg4Ik6Xkix3G9CjjVfStnGB~IfYm2yn97r~64ptO8eQMR7Fc-28WpnX-RmGwIrr~qIOxi5divSkBy8sF~LPgxCosiiVh2XeeCS5uhyP7X8LO5xgClg__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
              alt="event">
            <h3 class="capitalize font-bold mt-4 mb-2 text-xl">mengenal design thinking lebih dekat</h3>
            <div class="flex flex-col gap-2">
              <div class="flex gap-2">
                <IconsCalendar class="h-4 text-blue-400" />
                <p class="text-sm">24 Mei 2022</p>
              </div>
              <div class="flex gap-2">
                <IconsClock class="h-4 text-blue-400" />
                <p class="text-sm">16.00 - 18.00 PM</p>
              </div>
              <div class="flex gap-2">
                <IconsVidio class="h-4 text-blue-400" />
                <p class="text-sm uppercase">zoom meeting</p>
              </div>
              <button class="px-4 py-2 mt-4 bg-sbydev-primary rounded-md text-white">Lihat Detail</button>
            </div>
          </div>
          <div class="mt-2 w-72">
            <img class="h-80 w-72 object-cover rounded-xl"
              src="https://s3-alpha-sig.figma.com/img/c51d/5a17/7bc91c636c83e3e675d2b87a71fb6edd?Expires=1653868800&Signature=EzscYfMvDrSKxKxWb-MMlMvxDcBFucx70TJ7PLCbwbDLzS~OHa-YsE8VMJfpe1Fj~RjB72qS9DjZVYXM3l6cfvxKcX-f8a3WRyQV5Y42yo5m-O432pcETIMnOrn8ddf6HLIoGzQtikv-Skh0adFPHk9GHtxpscrBbgTlIwFdFnawCKR6td7dm542wIFLyeFJyQuobQYg6hE7Egk8ilvV-5W~zKIaF6CxO6Y3fg4Ik6Xkix3G9CjjVfStnGB~IfYm2yn97r~64ptO8eQMR7Fc-28WpnX-RmGwIrr~qIOxi5divSkBy8sF~LPgxCosiiVh2XeeCS5uhyP7X8LO5xgClg__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
              alt="event">
            <h3 class="capitalize font-bold mt-4 mb-2 text-xl">mengenal design thinking lebih dekat</h3>
            <div class="flex flex-col gap-2">
              <div class="flex gap-2">
                <IconsCalendar class="h-4 text-blue-400" />
                <p class="text-sm">24 Mei 2022</p>
              </div>
              <div class="flex gap-2">
                <IconsClock class="h-4 text-blue-400" />
                <p class="text-sm">16.00 - 18.00 PM</p>
              </div>
              <div class="flex gap-2">
                <IconsVidio class="h-4 text-blue-400" />
                <p class="text-sm uppercase">zoom meeting</p>
              </div>
              <button class="px-4 py-2 mt-4 bg-sbydev-primary rounded-md text-white">Lihat Detail</button>
            </div>
          </div>

        </div>

      </div>
    </PartialsLandingSection>

    <PartialsLandingSection>
      <div class="container mx-auto">
        <div class="flex justify-center flex-col gap-4 mb-10">
          <h2 class="font-bold text-4xl text-center">Blog</h2>
          <p class="text-xl text-center">Kegiatan yang dilakukan setiap bulan dari komunitas SurabayaDev</p>
        </div>
        <div class="grid grid-cols-4 gap-4">
          <div class="shadow-xl rounded-md bg-gray-100 px-4 py-3 w-96">
            <img class="rounded-2xl h-80 w-96 object-cover"
              src="https://s3-alpha-sig.figma.com/img/7258/42f6/bb8d5d2ff678ab331ec590e039dcdbd2?Expires=1653868800&Signature=SwUfOjXwtfFd9Crv2--nhZQ-RCTJGSJb~Z6DtD1WH2N9hNe9nFfescST7UmKniZYzyoff9hVNPESEsuBrzYG5lm8yFgNygCkJqQCuFnlaeTkfzfvJrXU5EZUPrkDF~6AJoGtkn5LpjRZxwEn6cJ~H2oRJGYskFzLSnQgCSP8Ki0GG-t1L0SVae5TlBlRLSEY7Kwrtz0pY3aykKCBSzonOqQp~pYZHjnYgEjPbWfurvMjbGOlXOcqCjNPUPt-ZM07-M~qQrv4z2lk6ju3lxICNYPCDOtd57XgxXtXDcPrHSgsKaccYSN5Thby01IlgH6hb~JBm2jjM3uQIifY6OUQNQ__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
              alt="">
            <h3 class="my-4 text-2xl font-bold capitalize mb-11">introduction web 3</h3>
            <div class="bg-gray-200 rounded-xl px-4  py-2 capitalize inline-block mb-4 ">
              web developer
            </div>
            <div class="bg-gray-200 rounded-xl px-4 py-2 capitalize inline-block mb-4">
              technology
            </div>
          </div>
          <div class="shadow-xl rounded-md bg-gray-100 px-4 py-3 w-96">
            <img class="rounded-2xl h-80 w-96 object-cover"
              src="https://s3-alpha-sig.figma.com/img/7258/42f6/bb8d5d2ff678ab331ec590e039dcdbd2?Expires=1653868800&Signature=SwUfOjXwtfFd9Crv2--nhZQ-RCTJGSJb~Z6DtD1WH2N9hNe9nFfescST7UmKniZYzyoff9hVNPESEsuBrzYG5lm8yFgNygCkJqQCuFnlaeTkfzfvJrXU5EZUPrkDF~6AJoGtkn5LpjRZxwEn6cJ~H2oRJGYskFzLSnQgCSP8Ki0GG-t1L0SVae5TlBlRLSEY7Kwrtz0pY3aykKCBSzonOqQp~pYZHjnYgEjPbWfurvMjbGOlXOcqCjNPUPt-ZM07-M~qQrv4z2lk6ju3lxICNYPCDOtd57XgxXtXDcPrHSgsKaccYSN5Thby01IlgH6hb~JBm2jjM3uQIifY6OUQNQ__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
              alt="">
            <h3 class="my-4 text-2xl font-bold capitalize mb-11">introduction web 3</h3>
            <div class="bg-gray-200 rounded-xl px-4  py-2 capitalize inline-block mb-4 ">
              web developer
            </div>
            <div class="bg-gray-200 rounded-xl px-4 py-2 capitalize inline-block mb-4">
              technology
            </div>
          </div>
          <div class="shadow-xl rounded-md bg-gray-100 px-4 py-3 w-96">
            <img class="rounded-2xl h-80 w-96 object-cover"
              src="https://s3-alpha-sig.figma.com/img/7258/42f6/bb8d5d2ff678ab331ec590e039dcdbd2?Expires=1653868800&Signature=SwUfOjXwtfFd9Crv2--nhZQ-RCTJGSJb~Z6DtD1WH2N9hNe9nFfescST7UmKniZYzyoff9hVNPESEsuBrzYG5lm8yFgNygCkJqQCuFnlaeTkfzfvJrXU5EZUPrkDF~6AJoGtkn5LpjRZxwEn6cJ~H2oRJGYskFzLSnQgCSP8Ki0GG-t1L0SVae5TlBlRLSEY7Kwrtz0pY3aykKCBSzonOqQp~pYZHjnYgEjPbWfurvMjbGOlXOcqCjNPUPt-ZM07-M~qQrv4z2lk6ju3lxICNYPCDOtd57XgxXtXDcPrHSgsKaccYSN5Thby01IlgH6hb~JBm2jjM3uQIifY6OUQNQ__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
              alt="">
            <h3 class="my-4 text-2xl font-bold capitalize mb-11">introduction web 3</h3>
            <div class="bg-gray-200 rounded-xl px-4  py-2 capitalize inline-block mb-4 ">
              web developer
            </div>
            <div class="bg-gray-200 rounded-xl px-4 py-2 capitalize inline-block mb-4">
              technology
            </div>
          </div>
          <div class="shadow-xl rounded-md bg-gray-100 px-4 py-3 w-96">
            <img class="rounded-2xl h-80 w-96 object-cover"
              src="https://s3-alpha-sig.figma.com/img/7258/42f6/bb8d5d2ff678ab331ec590e039dcdbd2?Expires=1653868800&Signature=SwUfOjXwtfFd9Crv2--nhZQ-RCTJGSJb~Z6DtD1WH2N9hNe9nFfescST7UmKniZYzyoff9hVNPESEsuBrzYG5lm8yFgNygCkJqQCuFnlaeTkfzfvJrXU5EZUPrkDF~6AJoGtkn5LpjRZxwEn6cJ~H2oRJGYskFzLSnQgCSP8Ki0GG-t1L0SVae5TlBlRLSEY7Kwrtz0pY3aykKCBSzonOqQp~pYZHjnYgEjPbWfurvMjbGOlXOcqCjNPUPt-ZM07-M~qQrv4z2lk6ju3lxICNYPCDOtd57XgxXtXDcPrHSgsKaccYSN5Thby01IlgH6hb~JBm2jjM3uQIifY6OUQNQ__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
              alt="">
            <h3 class="my-4 text-2xl font-bold capitalize mb-11">introduction web 3</h3>
            <div class="bg-gray-200 rounded-xl px-4  py-2 capitalize inline-block mb-4 ">
              web developer
            </div>
            <div class="bg-gray-200 rounded-xl px-4 py-2 capitalize inline-block mb-4">
              technology
            </div>
          </div>
        </div>
      </div>
    </PartialsLandingSection>

  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
