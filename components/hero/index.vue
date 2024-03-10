<script setup>
import Header from "./Header.vue";
</script>

<template>
  <div class="relative">
    <Header />
    <section class="w-full grid grid-cols-1 md:grid-cols-2 items-center p-5 sm:p-20 my-2">
      <div class="space-y-3">
        <div
          class="font-volkhov font-bold text-5xl md:text-6xl lg:text-8xl text-[#181E4B]"
        >
          <div class="flex space-x-3">
            <div>Soy Normy DMorales
                </div>
            <div class="relative">
              <g mask="url(#mask0_1_121)">  
              </g>
            </div>
          </div>
          <div>“Servir es mi pasión y dejar huella es mi misión”</div>
        </div>
        <div class="flex items-center space-x-3">
          <button type="button" aria-label="Find out more"
            class="block bg-[#69506c] text-white p-3 text-sm font-poppins rounded-md"
          >
            Descubre todos mis cursos y capacitaciones aqui!
          </button>
          <button type="button" aria-label="Play demo" class="font-poppins flex mt-5">
            <svg
              class="w-20"
              viewBox="0 0 112 112"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g filter="url(#filter0_d_1_131)">
                <circle cx="56" cy="41" r="26" fill="#69506c" />
              </g>
              <path
                d="M64 42.5L52.75 48.9952L52.75 36.0048L64 42.5Z"
                fill="white"
              />
              <defs>
                <filter
                  id="filter0_d_1_131"
                  x="0"
                  y="0"
                  width="112"
                  height="112"
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
                  <feOffset dy="15" />
                  <feGaussianBlur stdDeviation="15" />
                  <feColorMatrix
                    type="matrix"
                    values="0 0 0 0 0.87451 0 0 0 0 0.411765 0 0 0 0 0.317647 0 0 0 0.3 0"
                  />
                  <feBlend
                    mode="normal"
                    in2="BackgroundImageFix"
                    result="effect1_dropShadow_1_131"
                  />
                  <feBlend
                    mode="normal"
                    in="SourceGraphic"
                    in2="effect1_dropShadow_1_131"
                    result="shape"
                  />
                </filter>
              </defs>
            </svg>
            <p class="mt-5">Aqui tienes una muestra de mi trabajo</p>
          </button>
        </div>
      </div>
      <div>
        <nuxt-picture
          src="/images/Normy.JPG"
          width="1000"
          height="1000"
          alt="Normy portada"
        />
        <svg
          class="absolute top-0 right-0 w-[35rem] -z-10"
          viewBox="0 0 704 724"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
        <!-- aqui va el colorcito de la nubecita de la pagina -->
          <path
            d="M22.3069 222C-18.0931 153.2 5.4736 13.3333 22.3069 -48L701.807 -149L766.307 122.5L727.807 723.5C649.14 724.5 473.707 717 401.307 679C310.807 631.5 351.807 555 276.807 515C201.807 475 244.807 369.5 218.807 329.5C192.807 289.5 72.8069 308 22.3069 222Z"
            fill="#69506c"
          />
        </svg>
      </div>
    </section>
  </div>
</template>
