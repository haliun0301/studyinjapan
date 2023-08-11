<template>
    <header>
      <!-- Hero section with background image, heading, subheading and button -->
      <div
        class="relative overflow-hidden bg-cover bg-no-repeat"
        style="
          background-position: 100%;
          background-image: url('https://fpc.org.uk/wp-content/uploads/2022/07/11.-Japan.jpg');
          height: 550px;
        "
      >
        <div
          class="absolute h-full w-full overflow-hidden bg-fixed"
          style="background-color: rgba(0, 0, 0, 0.6)"
        >
          <!-- Navigation -->
          <nav
            class="relative flex w-full items-center justify-between bg-transparent py-2 text-gray-200 hover:text-gray-300 focus:text-gray-300 dark:bg-neutral-600 dark:text-neutral-200 md:flex-wrap md:justify-start"
            data-te-navbar-ref
          >
            <div class="flex w-full flex-wrap items-center justify-between px-3">
              <div class="flex items-center">
                <!-- Hamburger menu button -->
                <button
                  class="border-0 bg-transparent px-2 text-xl leading-none transition-shadow duration-150 ease-in-out hover:text-neutral-700 focus:text-neutral-700 dark:hover:text-white dark:focus:text-white lg:hidden"
                  type="button"
                  data-te-collapse-init
                  data-te-target="#navbarSupportedContentX"
                  aria-controls="navbarSupportedContentX"
                  aria-expanded="false"
                  aria-label="Toggle navigation"
                >
                  <!-- Hamburger menu icon -->
                  <span class="[&>svg]:w-5">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="1.5"
                      stroke="currentColor"
                      class="h-7 w-7"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
                      />
                    </svg>
                  </span>
                </button>
              </div>
  
              <!-- Navigation links -->
              <div
                class="!visible hidden grow basis-[100%] items-end lg:!flex lg:basis-auto mt-4"
                id="navbarSupportedContentX"
                data-te-collapse-item
              >
                <ul
                  class="ml-auto flex flex-col lg:flex-row"
                  data-te-navbar-nav-ref
                >
                  <li class="mb-4 lg:mb-0 lg:pr-3" data-te-nav-item-ref>
                    <a
                      class="block transition duration-150 ease-in-out hover:text-neutral-700 focus:text-neutral-700 disabled:text-black/30 dark:hover:text-white dark:focus:text-white lg:p-2 [&.active]:text-black/90"
                      href="#!"
                      data-te-nav-link-ref
                      data-te-ripple-init
                      data-te-ripple-color="light"
                    >
                      <div class="flex flex-row">
                        <div class="pr-2">
                          <svg
                            xmlns="http://www.w3.org/2000/svg"
                            fill="none"
                            viewBox="0 0 24 24"
                            stroke-width="1.5"
                            stroke="currentColor"
                            class="w-6 h-6"
                          >
                            <path
                              stroke-linecap="round"
                              stroke-linejoin="round"
                              d="M12 21a9.004 9.004 0 008.716-6.747M12 21a9.004 9.004 0 01-8.716-6.747M12 21c2.485 0 4.5-4.03 4.5-9S14.485 3 12 3m0 18c-2.485 0-4.5-4.03-4.5-9S9.515 3 12 3m0 0a8.997 8.997 0 017.843 4.582M12 3a8.997 8.997 0 00-7.843 4.582m15.686 0A11.953 11.953 0 0112 10.5c-2.998 0-5.74-1.1-7.843-2.918m15.686 0A8.959 8.959 0 0121 12c0 .778-.099 1.533-.284 2.253m0 0A17.919 17.919 0 0112 16.5c-3.162 0-6.133-.815-8.716-2.247m0 0A9.015 9.015 0 013 12c0-1.605.42-3.113 1.157-4.418"
                            />
                          </svg>
                        </div>
                        <div>English</div>
                      </div>
                    </a>
                  </li>
                  <li class="mb-4 lg:mb-0 lg:pr-2" data-te-nav-item-ref>
                    <form>
                      <div class="relative">
                        <div
                          class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none"
                        >
                          <svg
                            class="w-4 h-4 text-white dark:text-gray-400"
                            aria-hidden="true"
                            xmlns="http://www.w3.org/2000/svg"
                            fill="none"
                            viewBox="0 0 20 20"
                          >
                            <path
                              stroke="currentColor"
                              stroke-linecap="round"
                              stroke-linejoin="round"
                              stroke-width="2"
                              d="m19 19-4-4m0-7A7 7 0 1 1 1 8a7 7 0 0 1 14 0Z"
                            />
                          </svg>
                        </div>
                        <input
                          type="search"
                          id="small-search"
                          class="block w-full p-2 pl-10 text-sm text-white border border-gray-300 rounded-md bg-transparent focus:ring-teal-500 focus:border-teal-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-teal-500 dark:focus:border-teal-500"
                          placeholder="Search"
                          required
                        />
                        <button
                          type="submit"
                          class="text-white block h-full absolute right-0 bottom-0 bg-teal-500 hover:bg-teal-800 focus:ring-4 focus:outline-none focus:ring-teal-300 font-small rounded-md text-sm px-4 py-2 dark:bg-teal-600 dark:hover:bg-teal-700 dark:focus:ring-teal-800"
                        >
                          Search
                        </button>
                      </div>
                    </form>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
          <div class="z-10">
            <img
              :src="element"
              style="height: 300px;"
              class="relative overflow-hidden -ml-20 -mt-10"
            />
            <!-- Title -->
            <div class="flex h-full items-center justify-center z-40 -mt-20">
              <div class="px-6 text-center text-white md:px-12">
                <h1 class="mb-6 text-5xl font-bold">Study in Japan</h1>
                <h3 class="mb-8 text-xxl font-medium">Your Japan Companion</h3>
                <!-- <button
                  type="button"
                  class="inline-block rounded border-2 border-neutral-50 px-6 pb-[6px] pt-2 text-xs font-medium uppercase leading-normal text-neutral-50 transition duration-150 ease-in-out hover:border-neutral-100 hover:bg-neutral-500 hover:bg-opacity-10 hover:text-neutral-100 focus:border-neutral-100 focus:text-neutral-100 focus:outline-none focus:ring-0 active:border-neutral-200 active:text-neutral-200 dark:hover:bg-neutral-100 dark:hover:bg-opacity-10"
                  data-te-ripple-init
                  data-te-ripple-color="light"
                >
                  Get started
                </button> -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>
  </template>
  
  <script>
  import element from "./../assets/img/element1.png";
  export default {
    name: "HeaderBar",
    components: {},
    data: function () {
      return {
        element: element,
      };
    },
  };
  </script>
  
  <style></style>
  