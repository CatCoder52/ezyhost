<template>
  <section class="bg-bn">
   
      <div class="flex flex-wrap items-center -mx-3">
        <div class="w-full lg:w-1/2 px-3 md:order-1 order-2">
          <div class="py-0 md:py-12">
              <img class="dotfly" src="../assets/dot.svg" alt="dot" />
            <div class="relative max-w-xl mx-auto lg:mx-0 mb-8 text-center lg:text-left">
              <h1 class="mb-4 font-bold">
                Powering up
                <strong class="text-blue-600">2M Websites</strong>
                On the internet
              </h1>
            
              <p>
                Hosting starting at $0.9, consectetur adipiscing elit. Sed
                luctus eget justo et iaculis. Quisque vitae nulla malesuada,
                auctor arcu vitae, luctus nisi.
              </p>
            </div>
            <div class="text-center relative lg:text-left">
              <a
                class="block sm:inline-block py-4 px-8 mb-4 sm:mb-0 sm:mr-3 text-xs text-white text-center font-semibold leading-none bg-blue-600 hover:bg-blue-700 rounded"
                href="#"
                >Packages</a
              ><a
                class="block sm:inline-block py-4 px-8 text-xs text-blueGray-500 hover:text-blueGray-600 text-center font-semibold leading-none bg-white border border-blueGray-200 hover:border-blueGray-300 rounded"
                href="#"
                >Documentation</a
              >
              <img class="rotateme" src="../assets/rotate.svg" alt="triangle" />
            </div>
          </div>
        </div>
        <div class="w-full lg:w-1/2 px-3 mb-12 lg:mb-0 md:order-2 order-1">
          <div class="flex items-center justify-center">
            <Rocket/>
          </div>
        </div>
      </div>

  </section>
</template>

<script>
import Rocket from './Rocket.vue'
export default {
  components: {
    Rocket,
  },
}
</script>

<style></style>
