<template>
  <button
    data-drawer-target="sidebar-multi-level-sidebar"
    data-drawer-toggle="sidebar-multi-level-sidebar"
    aria-controls="sidebar-multi-level-sidebar"
    type="button"
    class="inline-flex items-center p-2 mt-2 ml-3 text-sm text-gray-500 rounded-lg sm:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
  >
    <span class="sr-only">Open sidebar</span>
    <svg
      class="w-6 h-6"
      aria-hidden="true"
      fill="currentColor"
      viewBox="0 0 20 20"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        clip-rule="evenodd"
        fill-rule="evenodd"
        d="M2 4.75A.75.75 0 012.75 4h14.5a.75.75 0 010 1.5H2.75A.75.75 0 012 4.75zm0 10.5a.75.75 0 01.75-.75h7.5a.75.75 0 010 1.5h-7.5a.75.75 0 01-.75-.75zM2 10a.75.75 0 01.75-.75h14.5a.75.75 0 010 1.5H2.75A.75.75 0 012 10z"
      ></path>
    </svg>
  </button>

  <aside
    id="sidebar-multi-level-sidebar"
    class="top-0 left-0 z-40 w-80 h-screen transition-transform -translate-x-full sm:translate-x-0"
    aria-label="Sidebar"
  >
    <!-- <div class="px-10 pt-16">
        <h3 class="text-3xl font-bold text-gray-700"></h3>
    </div> -->
    <div
      class="h-full px-3 pb-4 pt-10 overflow-y-auto bg-gray-50 dark:bg-gray-800"
    >
      <ul class="space-y-2 font-medium">
        <li>
          <button
            type="button"
            class="flex items-center w-full p-6 text-base text-gray-900 transition duration-75 rounded-lg group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700"
            aria-controls="dropdown-example"
            data-collapse-toggle="dropdown-example"
          >
            <img :src="el1" class="w-12" />
            <span class="ml-3">Attractiveness in Japan</span>
          </button>
        </li>
        <li>
          <button
            type="button"
            class="flex items-center w-full p-6 text-base text-gray-900 transition duration-75 rounded-lg group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700"
            aria-controls="dropdown-example"
            data-collapse-toggle="dropdown-example"
          >
            <img :src="el2" class="w-12" />
            <span class="flex-1 ml-3 text-left whitespace-nowrap"
              >Study abroad plan</span
            >
            <!-- <svg
              class="w-3 h-3"
              aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 10 6"
            >
              <path
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="m1 1 4 4 4-4"
              />
            </svg> -->
          </button>
          
          <ul class="hidden py-2 space-y-2">
            <li>
              <a
                href="#"
                class="flex items-center w-full p-2 text-gray-900 transition duration-75 rounded-lg pl-11 group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700"
                >Products</a
              >
            </li>
            <li>
              <a
                href="#"
                class="flex items-center w-full p-2 text-gray-900 transition duration-75 rounded-lg pl-11 group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700"
                >Billing</a
              >
            </li>
            <li>
              <a
                href="#"
                class="flex items-center w-full p-2 text-gray-900 transition duration-75 rounded-lg pl-11 group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700"
                >Invoice</a
              >
            </li>
          </ul>
        </li>
        <li>
          <button
            type="button"
            class="flex items-center w-full p-6 text-base text-gray-900 transition duration-75 rounded-lg group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700"
            aria-controls="dropdown-example"
            data-collapse-toggle="dropdown-example"
          >
            <img :src="el5" class="w-12" />
            <span class="flex-1 ml-3 whitespace-nowrap text-left"
              >Life in Japan</span
            >
            <!-- <svg
              class="w-3 h-3"
              aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 10 6"
            >
              <path
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="m1 1 4 4 4-4"
              />
            </svg> -->
          </button>
        </li>
        <li>
          <button
            type="button"
            class="flex items-center w-full p-6 text-base text-gray-900 transition duration-75 rounded-lg group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700"
            aria-controls="dropdown-example"
            data-collapse-toggle="dropdown-example"
          >
            <img :src="el4" class="w-12" />
            <span class="flex-1 ml-3 whitespace-nowrap text-left"
              >Crisis management</span
            >
            <!-- <svg
              class="w-3 h-3"
              aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 10 6"
            >
              <path
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="m1 1 4 4 4-4"
              />
            </svg> -->
          </button>
        </li>
        <li>
          <button
            type="button"
            class="flex items-center w-full p-6 text-base text-gray-900 transition duration-75 rounded-lg group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700"
            aria-controls="dropdown-example"
            data-collapse-toggle="dropdown-example"
          >
            <img :src="el3" class="w-12" />
            <span class="flex-1 ml-3 whitespace-nowrap text-left"
              >Employment in Japan</span
            >
            <!-- <svg
              class="w-3 h-3"
              aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 10 6"
            >
              <path
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="m1 1 4 4 4-4"
              />
            </svg> -->
          </button>
        </li>
      </ul>
    </div>
  </aside>
</template>

<script>
import el1 from "./../assets/img/el1.png";
import el2 from "./../assets/img/el2.png";
import el3 from "./../assets/img/el3.png";
import el4 from "./../assets/img/el4.png";
import el5 from "./../assets/img/el5.png";

export default {
  name: "HeaderBar",
  components: {

  },
  data: function () {
    return {
      el1: el1,
      el2: el2,
      el3: el3,
      el4: el4,
      el5: el5,
    };
  },
  methods: {
    
  },
};
</script>

<style></style>
