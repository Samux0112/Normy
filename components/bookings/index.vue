<script setup></script>


<template>
  <footer class="p-5 sm:px-16 sm:py-6 mt-12">
    <div
      class="w-full text-center p-12 sm:p-0 space-y-4 sm:space-y-0 sm:grid sm:grid-cols-10 gap-20 md:gap-12 lg:gap-20"
    >
      <div class="col-span-2 space-y-3">
        <NuxtLink to="/" class="text-[#181E4B] font-medium text-5xl"
          >Normy DMorales.</NuxtLink
        >
        <p class="text-[#080809] text-xs font-light">
          “Servir es mi pasión y dejar huella es mi misión”
        </p>
      </div>
      <div class="col-span-6 grid grid-cols-1 sm:grid-cols-6">
        <div class="col-span-2 space-y-4">
          <p class="font-bold text-lg">Company</p>
          <div class="space-y-2">
            <NuxtLink to="/" class="block text-[#5E6282]">About</NuxtLink>
            <NuxtLink to="/" class="block text-[#5E6282]">Careers</NuxtLink>
            <NuxtLink to="/" class="block text-[#5E6282]">Mobile</NuxtLink>
          </div>
        </div>
        <div class="col-span-2 space-y-4">
          <p class="font-bold text-lg">Contact</p>
          <div class="space-y-2">
            <NuxtLink to="/" class="block text-[#5E6282]">Help/FAQ</NuxtLink>
            <NuxtLink to="/" class="block text-[#5E6282]">Press</NuxtLink>
            <NuxtLink to="/" class="block text-[#5E6282]">Affilates</NuxtLink>
          </div>
        </div>
        <div class="col-span-2 space-y-4">
          <p class="font-bold text-lg">More</p>
          <div class="space-y-2">
            <NuxtLink to="/" class="block text-[#5E6282]">Airlinefees</NuxtLink>
            <NuxtLink to="/" class="block text-[#5E6282]">Airline</NuxtLink>
            <NuxtLink to="/" class="block text-[#5E6282]"
              >Low fare tips</NuxtLink
            >
          </div>
        </div>
      </div>
      <div class="col-span-2 space-y-4">
        <p class="font-bold text-lg">Mis redes sociales</p>
        <div class="space-y-3 md:space-y-0 lg:space-y-3">
          <div class="flex items-center justify-center sm:justify-right">
            <svg
              width="61"
              height="61"
              viewBox="0 0 61 61"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g filter="url(#filter0_d_108_74)">
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M30.5 49C41.8218 49 51 39.8218 51 28.5C51 17.1782 41.8218 8 30.5 8C19.1782 8 10 17.1782 10 28.5C10 39.8218 19.1782 49 30.5 49Z"
                  fill="white"
                />
              </g>
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M33.1084 26.2445C32.7883 26.1432 32.4202 26.0757 32.0842 26.0757C31.6681 26.0757 30.7719 26.3626 30.7719 26.9195V28.2527H32.9003V30.4971H30.7719V36.6905H28.6275V30.4971H27.5713V28.2527H28.6275V27.122C28.6275 25.4176 29.3636 24 31.14 24C31.7481 24 32.8363 24.0338 33.4284 24.2531L33.1084 26.2445Z"
                fill="#080809"
              />
              <defs>
                <filter
                  id="filter0_d_108_74"
                  x="0"
                  y="0"
                  width="61"
                  height="61"
                  filterUnits="userSpaceOnUse"
                  color-interpolation-filters="sRGB"
                >
                  <feFlood flood-opacity="0" result="BackgroundImageFix" />
                  <feColorMatrix
                    in="SourceAlpha"
                    type="matrix"
                    values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                    result="hardAlpha"
                  />
                  <feOffset dy="2" />
                  <feGaussianBlur stdDeviation="5" />
                  <feColorMatrix
                    type="matrix"
                    values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.1 0"
                  />
                  <feBlend
                    mode="normal"
                    in2="BackgroundImageFix"
                    result="effect1_dropShadow_108_74"
                  />
                  <feBlend
                    mode="normal"
                    in="SourceGraphic"
                    in2="effect1_dropShadow_108_74"
                    result="shape"
                  />
                </filter>
              </defs>
            </svg>

            <nuxt-picture
              src="/images/Social.jpg"
              alt="instagram"
              width="45"
              height="45"
            />

            <svg
              width="61"
              height="61"
              viewBox="0 0 61 61"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            ></svg>
          </div>
        </div>
      </div>
    </div>
    <p class="text-center text-xs text-[#5E6282] mb-8 sm:mt-8">
      Hecho por Samdev!!,
      <NuxtLink to="" class="text-indigo-600">
        Highmark Tech Solution CO {{ new Date().getFullYear() }}
      </NuxtLink>
    </p>
  </footer>
</template>
