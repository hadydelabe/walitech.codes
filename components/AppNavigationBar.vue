<template>
<div class="container mx-auto  flex items-center w-full leading-6 text-neutral-700 bg-blue-900">
  <h1
    class="p-0 m-0 font-sans text-3xl font-medium leading-none uppercase xl:text-4xl"
    style="letter-spacing: 2px;"
  >
    <a
      href="index.html"
      class="leading-7 text-white uppercase cursor-pointer hover:text-sky-300"
      style="text-decoration: none; letter-spacing: 2px;"
      >Arsha</a
    >
  </h1>
  <!-- Uncomment below if you prefer to use an image logo -->
  <!-- <a href="index.html" class="logo me-auto"><img src="assets/img/logo.png" alt="" class="img-fluid"></a>-->

  <nav
    id="navbar"
    class="flex relative flex-wrap justify-between items-center p-0 text-neutral-700"
  >
    <ul class="flex items-center p-0 m-0" style="list-style: none;">
      <li class="relative text-left" style="list-style: outside none none;">
        <a
          class="flex justify-between items-center py-2 pr-0 pl-8 text-sm font-medium text-white whitespace-nowrap border-0 cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
          href="#hero"
          style="text-decoration: none; transition: all 0.3s ease 0s; background-position: 0px center; list-style: outside none none;"
          >Home</a
        >
      </li>
      <li class="relative text-left" style="list-style: outside none none;">
        <a
          class="flex justify-between items-center py-2 pr-0 pl-8 text-sm font-medium whitespace-nowrap border-0 cursor-pointer text-sky-400 hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-sky-400"
          href="#about"
          style="text-decoration: none; transition: all 0.3s ease 0s; background-position: 0px center; list-style: outside none none;"
          >About</a
        >
      </li>
      <li class="relative text-left" style="list-style: outside none none;">
        <a
          class="flex justify-between items-center py-2 pr-0 pl-8 text-sm font-medium text-white whitespace-nowrap border-0 cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
          href="#services"
          style="text-decoration: none; transition: all 0.3s ease 0s; background-position: 0px center; list-style: outside none none;"
          >Services</a
        >
      </li>
      <li class="relative text-left" style="list-style: outside none none;">
        <a
          class="flex justify-between items-center py-2 pr-0 pl-8 text-sm font-medium text-white whitespace-nowrap border-0 cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
          href="#portfolio"
          style="text-decoration: none; transition: all 0.3s ease 0s; background-position: 0px center; list-style: outside none none;"
          >Portfolio</a
        >
      </li>
      <li class="relative text-left" style="list-style: outside none none;">
        <a
          class="flex justify-between items-center py-2 pr-0 pl-8 text-sm font-medium text-white whitespace-nowrap border-0 cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
          href="#team"
          style="text-decoration: none; transition: all 0.3s ease 0s; background-position: 0px center; list-style: outside none none;"
          >Team</a
        >
      </li>
      <li class="relative text-left" style="list-style: outside none none;">
        <a
          href="#"
          class="flex justify-between items-center py-2 pr-0 pl-8 text-sm font-medium text-white whitespace-nowrap cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
          style="text-decoration: none; transition: all 0.3s ease 0s; list-style: outside none none;"
          ><span class="" style="list-style: outside none none;"
            >Drop Down</span
          >
          <i
            class="ml-1 text-xs italic"
            style="line-height: 0px; list-style: outside none none;"
          ></i
        ></a>
        <ul
          class="block absolute invisible items-center py-2 px-0 m-0 bg-white rounded opacity-0"
          style="list-style: none; left: 14px; top: 72.5px; z-index: 99; box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px; transition: all 0.3s ease 0s;"
        >
          <li
            class="relative"
            style="min-width: 200px; list-style: outside none none;"
          >
            <a
              href="#"
              class="flex justify-between items-center py-2 px-5 text-sm font-medium leading-5 text-teal-900 normal-case whitespace-nowrap cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
              style="text-decoration: none; transition: all 0.3s ease 0s; list-style: outside none none;"
              >Drop Down 1</a
            >
          </li>
          <li
            class="relative"
            style="min-width: 200px; list-style: outside none none;"
          >
            <a
              href="#"
              class="flex justify-between items-center py-2 px-5 text-sm font-medium leading-5 text-teal-900 normal-case whitespace-nowrap cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
              style="text-decoration: none; transition: all 0.3s ease 0s; list-style: outside none none;"
              ><span class="" style="list-style: outside none none;"
                >Deep Drop Down</span
              >
              <i
                class="ml-1 text-xs italic"
                style="line-height: 0px; list-style: outside none none;"
              ></i
            ></a>
            <ul
              class="block absolute top-0 items-center py-2 px-0 m-0 rounded opacity-0"
              style="list-style: none; left: 170px; z-index: 99; box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px; transition: all 0.3s ease 0s;"
            >
              <li
                class="relative"
                style="min-width: 200px; list-style: outside none none;"
              >
                <a
                  href="#"
                  class="flex justify-between items-center py-2 px-5 text-sm font-medium leading-5 text-teal-900 normal-case whitespace-nowrap cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
                  style="text-decoration: none; transition: all 0.3s ease 0s; list-style: outside none none;"
                  >Deep Drop Down 1</a
                >
              </li>
              <li
                class="relative"
                style="min-width: 200px; list-style: outside none none;"
              >
                <a
                  href="#"
                  class="flex justify-between items-center py-2 px-5 text-sm font-medium leading-5 text-teal-900 normal-case whitespace-nowrap cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
                  style="text-decoration: none; transition: all 0.3s ease 0s; list-style: outside none none;"
                  >Deep Drop Down 2</a
                >
              </li>
              <li
                class="relative"
                style="min-width: 200px; list-style: outside none none;"
              >
                <a
                  href="#"
                  class="flex justify-between items-center py-2 px-5 text-sm font-medium leading-5 text-teal-900 normal-case whitespace-nowrap cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
                  style="text-decoration: none; transition: all 0.3s ease 0s; list-style: outside none none;"
                  >Deep Drop Down 3</a
                >
              </li>
              <li
                class="relative"
                style="min-width: 200px; list-style: outside none none;"
              >
                <a
                  href="#"
                  class="flex justify-between items-center py-2 px-5 text-sm font-medium leading-5 text-teal-900 normal-case whitespace-nowrap cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
                  style="text-decoration: none; transition: all 0.3s ease 0s; list-style: outside none none;"
                  >Deep Drop Down 4</a
                >
              </li>
              <li
                class="relative"
                style="min-width: 200px; list-style: outside none none;"
              >
                <a
                  href="#"
                  class="flex justify-between items-center py-2 px-5 text-sm font-medium leading-5 text-teal-900 normal-case whitespace-nowrap cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
                  style="text-decoration: none; transition: all 0.3s ease 0s; list-style: outside none none;"
                  >Deep Drop Down 5</a
                >
              </li>
            </ul>
          </li>
          <li
            class="relative"
            style="min-width: 200px; list-style: outside none none;"
          >
            <a
              href="#"
              class="flex justify-between items-center py-2 px-5 text-sm font-medium leading-5 text-teal-900 normal-case whitespace-nowrap cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
              style="text-decoration: none; transition: all 0.3s ease 0s; list-style: outside none none;"
              >Drop Down 2</a
            >
          </li>
          <li
            class="relative"
            style="min-width: 200px; list-style: outside none none;"
          >
            <a
              href="#"
              class="flex justify-between items-center py-2 px-5 text-sm font-medium leading-5 text-teal-900 normal-case whitespace-nowrap cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
              style="text-decoration: none; transition: all 0.3s ease 0s; list-style: outside none none;"
              >Drop Down 3</a
            >
          </li>
          <li
            class="relative"
            style="min-width: 200px; list-style: outside none none;"
          >
            <a
              href="#"
              class="flex justify-between items-center py-2 px-5 text-sm font-medium leading-5 text-teal-900 normal-case whitespace-nowrap cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
              style="text-decoration: none; transition: all 0.3s ease 0s; list-style: outside none none;"
              >Drop Down 4</a
            >
          </li>
        </ul>
      </li>
      <li class="relative text-left" style="list-style: outside none none;">
        <a
          class="flex justify-between items-center py-2 pr-0 pl-8 text-sm font-medium text-white whitespace-nowrap border-0 cursor-pointer hover:text-sky-400 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:py-2 focus:pr-0 focus:pl-8 focus:text-sm focus:font-medium focus:text-white"
          href="#contact"
          style="text-decoration: none; transition: all 0.3s ease 0s; background-position: 0px center; list-style: outside none none;"
          >Contact</a
        >
      </li>
      <li class="relative text-left" style="list-style: outside none none;">
        <a
          class="flex justify-between items-center py-2 px-5 ml-8 text-sm font-semibold leading-5 text-white whitespace-nowrap border-2 border-solid cursor-pointer border-sky-400 hover:bg-sky-400 hover:text-white focus:ml-8 focus:flex focus:items-center focus:justify-between focus:whitespace-nowrap focus:border-2 focus:border-solid focus:border-sky-400 focus:bg-sky-400 focus:px-5 focus:py-2 focus:text-sm focus:font-semibold focus:text-white"
          href="#about"
          style="text-decoration: none; transition: all 0.3s ease 0s; border-radius: 50px; list-style: outside none none;"
          >Get Started</a
        >
      </li>
    </ul>
    <i
      class="hidden text-3xl italic text-white cursor-pointer"
      style="line-height: 0px; transition: all 0.5s ease 0s;"
    ></i>
  </nav>
  <!-- .navbar -->
</div>

</template>

<script setup>

</script>



<style>

</style>
