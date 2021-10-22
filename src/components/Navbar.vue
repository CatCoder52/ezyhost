<template>
<section>
  <!-- desktop nav -->
    <nav class="hidden sm:hidden md:hidden lg:block">
      <div class="flex justify-between items-center py-3 px-40 ">
      <div><Logo/></div>
        <ul
          class="
            list-none
            grid grid-rows-1 grid-flow-col
            gap-4
            lg:gap-10
           
          "
        >
          <a href="/" class="hover:text-purple-600 focus:text-purple-600">
            <li class='link'>Home</li>
          </a>
          <a href="#pricing" class="hover:text-purple-600 focus:text-purple-600">
            <li class='link'>Pricing</li>
          </a>
          <a href="#support" class="hover:text-purple-600 focus:text-purple-600">
            <li class='link'>Support</li>
          </a>
        </ul>
        
        <div class="flex gap-3">
          <button
            type="button"
            class="
              inline-flex
              items-center
              px-6
              py-2
              border border-transparent
              text-base
              font-medium
              rounded-full
              text-purple-100
              bg-purple-500
              shadow-lg
              hover:bg-purple-600
              hover:shadow-none
              focus:outline-none
              focus:ring-2
              focus:ring-offset-2
              focus:ring-purple-600
            "
          >
            Login
          </button>

        </div>
      </div>
      <div class="border-b border-gray-100" />
    </nav>
    <!-- mobile nav -->
    <nav class="block md:block lg:hidden sm:block">
      <div class="container py-3 mx-auto">
        <div class="flex justify-between md:px-40 px-20 items-center">

          <!-- left section -->
          <div class="flex justify-between items-center w-full">
            <a
              href="#"
              class="
                text-gray-800 text-xl
                font-bold
                hover:text-gray-700
                md:text-2xl
                
              "
              ><Logo /></a
            >
            
            <!-- click btn -->
            <div class="lg:hidden block">
              <button
                type="button"
                class="
                  text-gray-500
                  hover:text-gray-600
                  focus:text-gray-600 focus:outline-none
                  mt-2
                "
                @click="isOpen = !isOpen"
              >
                <svg viewBox="0 0 24 24" class="h-6 w-6 fill-current" :class="{ 'block': !isOpen, 'hidden': isOpen }">
                  <path
                    d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
                  ></path>
                </svg>
                <svg
:class="{ 'block': isOpen, 'hidden': !isOpen }"  class="h-6 w-6 fill-current" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
</svg>
              </button>
            </div>
          </div>

      </div>
<!-- right section -->
                      <div
              class="flex-col gap-6 mt-3 md:flex-col md:mt-0  w-3/4 shadow py-8 mx-auto"
              :class="isOpen ? 'flex menu-drop' : 'hidden'"
            >
              <a href="#" class="text-blue-800 text-sm hover:font-bold ml-10"
                >Home</a
              >
              <a href="#" class="text-blue-800 text-sm hover:font-bold ml-10"
                >Companies</a
              >
              <a href="#" class="text-blue-800 text-sm hover:font-bold ml-10"
                >Contact</a
              >
                <!-- btns -->
                <div class="flex gap-3 ml-10">
           <button
            type="button"
            class="
              inline-flex
              items-center
              px-6
              py-2
              border border-transparent
              text-base
              font-medium
              rounded-full
              text-purple-100
              bg-purple-500
              shadow-lg
              hover:shadow-none
              hover:bg-purple-600
              focus:outline-none
              focus:ring-2
              focus:ring-offset-2
              focus:ring-purple-600
            "
          >
            Login
          </button>

                    </div>
            </div>
        </div>
      </div>
      <div class="border-b border-gray-100" />
    </nav>
</section>
</template>

<script>
import Logo from './Logo.vue'
export default {
  components : {
  Logo
  },
  data() {
    return { isOpen: false }
  },
}
</script>

<style>
</style>