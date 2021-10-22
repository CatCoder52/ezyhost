<template>
  <div id="pricing">
    <div class="relative">
      <div
        aria-hidden="true"
        class="hidden absolute  w-full h-6 bottom-0 lg:block"
      ></div>

      <div
        class="relative max-w-2xl mx-auto pt-16 px-4 text-center sm:pt-30 sm:px-6 lg:max-w-7xl lg:px-8"
      >
        <strong class="text-4xl sm:text-6xl">
          <span class="block lg:inline">Simple pricing,</span>
          <span class="block lg:inline">no commitment.</span>
        </strong>
        <p class="mt-4 text-xl">
          Everything you need, nothing you don't. Pick a plan that best suits
          your business.
        </p>
      </div>

      <h2 class="sr-only">Plans</h2>

      <!-- Toggle -->
      <div class="relative mt-12 flex justify-center sm:mt-16">
        <div class="bg-blue-50 p-0.5 rounded-lg flex">
          <button
            type="button"
            class="relative bg-white py-2 px-6 border-purple-700 rounded-md shadow-sm text-sm font-medium text-purple-700 whitespace-nowrap hover:bg-purple-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-purple-700 focus:ring-white focus:z-10"
          >
            Monthly billing
          </button>
          <button
            type="button"
            class="ml-0.5 relative py-2 px-6 border border-transparent rounded-md text-sm font-medium text-purple-200 whitespace-nowrap hover:bg-purple-800 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-purple-700 focus:ring-white focus:z-10"
          >
            Yearly billing
          </button>
        </div>
      </div>

      <!-- Cards -->
      <div
        class="relative mt-8 max-w-2xl mx-auto px-4 pb-8 sm:mt-12 sm:px-6 lg:max-w-7xl lg:px-8 lg:pb-0"
      >
        <!-- Decorative background -->
        <div
          aria-hidden="true"
          class="hidden absolute top-4 bottom-6 left-8 right-8 inset-0 bg-purple-700 rounded-tl-lg rounded-tr-lg lg:block"
        ></div>

        <div class="relative space-y-6 lg:space-y-0 lg:grid lg:grid-cols-3">
          <div
            class="bg-purple-700 lg:bg-transparent py-6 px-6 pb-3 rounded-lg lg:px-8 lg:py-12"
          >
            <div>
              <h3
                class="text-white text-sm font-semibold uppercase tracking-wide"
              >
                Personal
              </h3>
              <div
                class="flex flex-col items-start sm:flex-row sm:items-center sm:justify-between lg:flex-col lg:items-start"
              >
                <div class="mt-3 flex items-center">
                  <p class="text-white text-4xl font-extrabold tracking-tight">
                    $5
                  </p>
                  <div class="ml-4">
                    <p class="text-white text-sm">USD / mo</p>
                    <p class="text-purple-200 text-sm">Billed yearly ($56)</p>
                  </div>
                </div>
                <a
                  href="#"
                  class="bg-white text-purple-600 hover:bg-purple-50 mt-6 w-full inline-block py-2 px-8 border border-transparent rounded-md shadow-sm text-center text-sm font-medium sm:mt-0 sm:w-auto lg:mt-6 lg:w-full"
                  >Buy Personal</a
                >
              </div>
            </div>
            <h4 class="sr-only">Features</h4>
            <ul
              role="list"
              class="border-purple-500 divide-purple-500 divide-opacity-75 my-7 border-t divide-y lg:border-t-0"
            >
              <li class="py-3 flex items-center">
                <!-- Heroicon name: solid/check -->
                <svg
                  class="text-purple-200 w-5 h-5 flex-shrink-0"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                    clip-rule="evenodd"
                  />
                </svg>
                <span class="text-white ml-3 text-sm font-medium"
                  >1 Gb Storage¹</span
                >
              </li>

              <li class="py-3 flex items-center">
                <!-- Heroicon name: solid/check -->
                <svg
                  class="text-purple-200 w-5 h-5 flex-shrink-0"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                    clip-rule="evenodd"
                  />
                </svg>
                <span class="text-white ml-3 text-sm font-medium"
                  >500 Mb RAM Memory¹</span
                >
              </li>

              <li class="py-3 flex items-center">
                <!-- Heroicon name: solid/check -->
                <svg
                  class="text-purple-200 w-5 h-5 flex-shrink-0"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                    clip-rule="evenodd"
                  />
                </svg>
                <span class="text-white ml-3 text-sm font-medium"
                  >1 Site (plus 1 Cloned site²)</span
                >
              </li>
            </ul>
              <small class="text-blue-200 inline-block">¹Total resource usage including site + database.</small>
              <small class="text-blue-200 inline-block">¹Shared resourced </small>
              <small class="text-blue-200 inline-block">²Cloned sites will use ezyhost subdomains only. </small>
          </div>

          <div
            class="bg-white ring-2 ring-purple-700 shadow-md py-6 px-6 pb-3 rounded-lg lg:px-8 lg:py-12"
          >
            <div>
              <h3
                class="text-purple-600 text-sm font-semibold uppercase tracking-wide"
              >
                Pro
              </h3>
              <div
                class="flex flex-col items-start sm:flex-row sm:items-center sm:justify-between lg:flex-col lg:items-start"
              >
                <div class="mt-3 flex items-center">
                  <p
                    class="text-purple-600 text-4xl font-extrabold tracking-tight"
                  >
                    $19
                  </p>
                  <div class="ml-4">
                    <p class="text-gray-700 text-sm">USD / mo</p>
                    <p class="text-gray-500 text-sm">Billed yearly ($220)</p>
                  </div>
                </div>
                <a
                  href="#"
                  class="bg-purple-600 text-white hover:bg-purple-700 mt-6 w-full inline-block py-2 px-8 border border-transparent rounded-md shadow-sm text-center text-sm font-medium sm:mt-0 sm:w-auto lg:mt-6 lg:w-full"
                  >Buy Pro</a
                >
              </div>
            </div>
            <h4 class="sr-only">Features</h4>
            <ul
              role="list"
              class="border-gray-200 divide-gray-200 my-7 border-t divide-y lg:border-t-0"
            >
              <li class="py-3 flex items-center">
                <!-- Heroicon name: solid/check -->
                <svg
                  class="text-purple-500 w-5 h-5 flex-shrink-0"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                    clip-rule="evenodd"
                  />
                </svg>
                <span class="text-gray-600 ml-3 text-sm font-medium"
                  >10 Gb Storage¹</span
                >
              </li>

              <li class="py-3 flex items-center">
                <!-- Heroicon name: solid/check -->
                <svg
                  class="text-purple-500 w-5 h-5 flex-shrink-0"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                    clip-rule="evenodd"
                  />
                </svg>
                <span class="text-gray-600 ml-3 text-sm font-medium"
                  >1 Gb RAM Memory¹</span
                >
              </li>

              <li class="py-3 flex items-center">
                <!-- Heroicon name: solid/check -->
                <svg
                  class="text-purple-500 w-5 h-5 flex-shrink-0"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                    clip-rule="evenodd"
                  />
                </svg>
                <span class="text-gray-600 ml-3 text-sm font-medium"
                  >5 Site (plus 2 Cloned sites²)</span
                >
              </li>
            </ul>
            <small class="text-gray-400 inline-block">¹Total resource usage including site + database.</small>
              <small class="text-gray-400 inline-block">¹Shared resourced </small>
              <small class="text-gray-400 inline-block">²Cloned sites will use ezyhost subdomains only. </small>
          </div>

          <div
            class="bg-purple-700 lg:bg-transparent py-6 px-6 pb-3 rounded-lg lg:px-8 lg:py-12"
          >
            <div>
              <h3
                class="text-white text-sm font-semibold uppercase tracking-wide"
              >
                Enterprise
              </h3>
              <div
                class="flex flex-col items-start sm:flex-row sm:items-center sm:justify-between lg:flex-col lg:items-start"
              >
                <div class="mt-3 flex items-center">
                  <p class="text-white text-4xl font-extrabold tracking-tight">
                    $12
                  </p>
                  <div class="ml-4">
                    <p class="text-white text-sm">USD / mo</p>
                    <p class="text-purple-200 text-sm">Billed yearly ($140)</p>
                  </div>
                </div>
                <a
                  href="#"
                  class="bg-white text-purple-600 hover:bg-purple-50 mt-6 w-full inline-block py-2 px-8 border border-transparent rounded-md shadow-sm text-center text-sm font-medium sm:mt-0 sm:w-auto lg:mt-6 lg:w-full"
                  >Buy Enterprise</a
                >
              </div>
            </div>
            <h4 class="sr-only">Features</h4>
            <ul
              role="list"
              class="border-purple-500 divide-purple-500 divide-opacity-75 my-7 border-t divide-y lg:border-t-0"
            >
              <li class="py-3 flex items-center">
                <!-- Heroicon name: solid/check -->
                <svg
                  class="text-purple-200 w-5 h-5 flex-shrink-0"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                    clip-rule="evenodd"
                  />
                </svg>
                <span class="text-white ml-3 text-sm font-medium"
                  >30 Gb Storage¹</span
                >
              </li>

              <li class="py-3 flex items-center">
                <!-- Heroicon name: solid/check -->
                <svg
                  class="text-purple-200 w-5 h-5 flex-shrink-0"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                    clip-rule="evenodd"
                  />
                </svg>
                <span class="text-white ml-3 text-sm font-medium"
                  >4 Gb RAM Memory¹</span
                >
              </li>

              <li class="py-3 flex items-center">
                <!-- Heroicon name: solid/check -->
                <svg
                  class="text-purple-200 w-5 h-5 flex-shrink-0"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                    clip-rule="evenodd"
                  />
                </svg>
                <span class="text-white ml-3 text-sm font-medium"
                  >15 Site (plus 15 Cloned sites²)</span
                >
              </li>

            </ul>
            <small class="text-blue-200 inline-block">¹Total resource usage including site + database.</small>
              <small class="text-blue-200 inline-block">¹Shared resourced </small>
              <small class="text-blue-200 inline-block">²Cloned sites will use ezyhost subdomains only. </small>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
