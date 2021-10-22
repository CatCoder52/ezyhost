<template>
  <section>
  <h1 class="text-center text-3xl lg:text-4xl font-bold font-heading mb-18 md:mb-24 ">Why Choose Us</h1>
    <div class="relative mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl">
      <div class="absolute inset-0">
        <div class="absolute inset-y-0 z-0 w-full h-full lg:w-3/4"></div>
      </div>
      <div class="relative">
        <div class="grid gap-12 row-gap-8 lg:grid-cols-2">
          <div class="grid gap-12 row-gap-5 md:grid-cols-2 md:order-1 order-2">
            <div class="relative">
              <svg
                viewBox="0 0 52 24"
                fill="#7160fb"
                class="absolute animate-ping top-0 left-0 z-0 w-32 -mt-8 -ml-16 text-blue-gray-100 lg:w-32 lg:-mt-12"
              >
                <defs>
                  <pattern
                    id="d06ca312-d4ed-465f-ad18-fb0c0f92b6f1"
                    x="0"
                    y="0"
                    width=".135"
                    height=".30"
                  >
                    <circle cx="1" cy="1" r=".7"></circle>
                  </pattern>
                </defs>
                <rect
                  fill="url(#d06ca312-d4ed-465f-ad18-fb0c0f92b6f1)"
                  width="52"
                  height="24"
                ></rect>
              </svg>
              <div class="relative">
                <div
                  class="flex items-center justify-center w-10 h-10 mb-3 rounded-full bg-teal-accent-400"
                >
                  <svg
                    class="w-8 h-8 text-teal-900"
                    stroke="#f59e0b"
                    viewBox="0 0 52 52"
                  >
                    <polygon
                      stroke-width="3"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      fill="none"
                      points="29 13 14 29 25 29 23 39 38 23 27 23"
                    ></polygon>
                  </svg>
                </div>
                <h6 class="mb-2 font-semibold leading-5">
                  The quick, brown fox jumps over a lazy dog
                </h6>
                <p class="text-sm text-gray-900">
                  Baseball ipsum dolor sit amet cellar rubber win hack tossed.
                  Slugging catcher slide bench league.
                </p>
              </div>
            </div>
            <div>
              <div
                class="flex items-center justify-center w-10 h-10 mb-3 rounded-full bg-teal-accent-400"
              >
                <svg
                  class="w-8 h-8 text-teal-900"
                  stroke="#f59e0b"
                  viewBox="0 0 52 52"
                >
                  <polygon
                    stroke-width="3"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    fill="none"
                    points="29 13 14 29 25 29 23 39 38 23 27 23"
                  ></polygon>
                </svg>
              </div>
              <h6 class="mb-2 font-semibold leading-5">
                A flower in my garden, a mystery
              </h6>
              <p class="text-sm text-gray-900">
                They urge you to put down your sword and come join the winners.
              </p>
            </div>
            <div>
              <div
                class="flex items-center justify-center w-10 h-10 mb-3 rounded-full bg-teal-accent-400"
              >
                <svg
                  class="w-8 h-8 text-teal-900"
                  stroke="#f59e0b"
                  viewBox="0 0 52 52"
                >
                  <polygon
                    stroke-width="3"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    fill="none"
                    points="29 13 14 29 25 29 23 39 38 23 27 23"
                  ></polygon>
                </svg>
              </div>
              <h6 class="mb-2 font-semibold leading-5">
                Skate ipsum dolor sit amet, alley oop
              </h6>
              <p class="text-sm text-gray-900">
                If one examines precultural libertarianism, one is faced with a
                choice: either accept rationalism.
              </p>
            </div>
            <div>
              <div
                class="flex items-center justify-center w-10 h-10 mb-3 rounded-full bg-teal-accent-400"
              >
                <svg
                  class="w-8 h-8 text-teal-900"
                  stroke="#f59e0b"
                  viewBox="0 0 52 52"
                >
                  <polygon
                    stroke-width="3"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    fill="none"
                    points="29 13 14 29 25 29 23 39 38 23 27 23"
                  ></polygon>
                </svg>
              </div>
              <h6 class="mb-2 font-semibold leading-5">
                The first mate and his Skipper too will
              </h6>
              <p class="text-sm text-gray-900">
                Those options are already baked in with this model shoot me an
                email clear blue water.
              </p>
            </div>
          </div>
          <div class="md:order-2 order-1 mt-10 md:mt-0">
            <Whyart
              class="object-cover w-full h-56 sm:h-96"
              
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Whyart from './Whyart.vue'
export default {
  components: {
    Whyart,
  },
}
</script>

<style></style>
