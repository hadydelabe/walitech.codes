<script setup>
import { ref } from 'vue';

let open = ref(false);
</script>

<template>
  <header data-section-id="1" data-share="" data-category="headers-light-color" class="overflow-hidden">
    <nav class="relative px-6 py-6 flex justify-between items-center bg-white" data-config-target=".navbar-menu"
      data-config-class="hidden">
      <a class="text-3xl font-bold leading-none" href="#" data-config-id="brand">
        <img class="h-12" src="atis-assets/logo/atis/atis-color-black.svg" alt="" width="auto">
      </a>
      <div class="lg:hidden">
        <button @click="open = !open" class="navbar-burger flex items-center text-gray-400 p-3">
          <svg class="block h-4 w-4 fill-current" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"
            data-config-id="auto-svg-1-5">
            <title>Mobile menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
          </svg>
        </button>
      </div>
      <ul
        class="hidden absolute top-1/2 left-1/2 transform -translate-y-1/2 -translate-x-1/2 lg:mx-auto lg:flex lg:items-center lg:w-auto lg:space-x-6">
        <li><a class="text-sm text-gray-400 hover:text-gray-500" href="#" data-config-id="link1">Start</a></li>
        <li class="text-gray-300">
          <svg class="w-4 h-4 current-fill" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
            stroke="currentColor" data-config-id="auto-svg-2-5">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z">
            </path>
          </svg>
        </li>
        <li><a class="text-sm text-green-600 font-bold" href="#" data-config-id="link2">About Us</a></li>
        <li class="text-gray-300">
          <svg class="w-4 h-4 current-fill" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
            stroke="currentColor" data-config-id="auto-svg-3-5">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z">
            </path>
          </svg>
        </li>
        <li><a class="text-sm text-gray-400 hover:text-gray-500" href="#" data-config-id="link4">Services</a></li>
        <li class="text-gray-300">
          <svg class="w-4 h-4 current-fill" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
            stroke="currentColor" data-config-id="auto-svg-4-5">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z">
            </path>
          </svg>
        </li>
        <li><a class="text-sm text-gray-400 hover:text-gray-500" href="#" data-config-id="link4">Platform</a></li>
        <li class="text-gray-300">
          <svg class="w-4 h-4 current-fill" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
            stroke="currentColor" data-config-id="auto-svg-5-5">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z">
            </path>
          </svg>
        </li>
        <li><a class="text-sm text-gray-400 hover:text-gray-500" href="#" data-config-id="link5">Testimonials</a></li>
      </ul>
      <a class="hidden lg:block py-2 px-6 bg-pink-600 hover:bg-pink-700 text-sm text-white font-bold rounded-l-xl rounded-t-xl transition duration-200"
        href="#" data-config-id="primary-action-nav">Contact Us</a>
    </nav>
    <div :class="{ 'hidden': open }" class="sm:hidden navbar-menu fixed top-0 left-0 bottom-0 w-5/6 max-w-sm z-50"
      data-config-id="toggle-mobile-2" data-config-target=".navbar-menu" data-config-class="hidden">
      <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"></div>
      <nav class="relative flex flex-col py-6 px-6 h-full w-full bg-white border-r overflow-y-auto">
        <div class="flex items-center mb-8">
          <a class="mr-auto text-3xl font-bold leading-none" href="#" data-config-id="brand">
            <img class="h-10" src="atis-assets/logo/atis/atis-color-black.svg" alt="" width="auto">
          </a>
          <button @click="open = !open" class="navbar-close">
            <svg class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500" xmlns="http://www.w3.org/2000/svg"
              fill="none" viewBox="0 0 24 24" stroke="currentColor" data-config-id="auto-svg-6-5">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
            </svg>
          </button>
        </div>
        <div>
          <ul>
            <li class="mb-1">
              <a class="block p-4 text-sm font-semibold text-gray-400 hover:bg-purple-50 hover:text-purple-600 rounded"
                href="#">Start
              </a>
            </li>
            <li class="mb-1"><a
                class="block p-4 text-sm font-semibold text-gray-400 hover:bg-purple-50 hover:text-purple-600 rounded"
                href="#">About Us</a></li>
            <li class="mb-1"><a
                class="block p-4 text-sm font-semibold text-gray-400 hover:bg-purple-50 hover:text-purple-600 rounded"
                href="#">Services</a></li>
            <li class="mb-1"><a
                class="block p-4 text-sm font-semibold text-gray-400 hover:bg-purple-50 hover:text-purple-600 rounded"
                href="#">Platform</a></li>
            <li class="mb-1"><a
                class="block p-4 text-sm font-semibold text-gray-400 hover:bg-purple-50 hover:text-purple-600 rounded"
                href="#">Testimonials</a></li>
          </ul>
        </div>
        <div class="mt-auto">
          <div class="pt-6"><a
              class="block px-4 py-3 mb-3 leading-loose text-xs text-center font-semibold bg-gray-50 hover:bg-gray-100 rounded-l-xl rounded-t-xl"
              href="#" data-config-id="primary-action">Sign Up</a><a
              class="block px-4 py-3 mb-2 leading-loose text-xs text-center text-white font-semibold bg-pink-600 hover:bg-pink-700 rounded-l-xl rounded-t-xl"
              href="#" data-config-id="secondary-action">Log In</a></div>
          <p class="my-4 text-xs text-center text-gray-400">
            <span data-config-id="copy">© 2020 All rights reserved.</span>
          </p>
          <div class="text-center">
            <a class="inline-block px-1" href="#">
              <img src="atis-assets/social/facebook-purple.svg" alt="">
            </a>
            <a class="inline-block px-1" href="#">
              <img src="atis-assets/social/twitter-purple.svg" alt="">
            </a>
            <a class="inline-block px-1" href="#">
              <img src="atis-assets/social/instagram-purple.svg" alt="">
            </a>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>
