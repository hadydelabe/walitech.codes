<template>
  <div>
    <div class="container px-6 py-16 mx-auto">
      <div class="items-center lg:flex">
        <div class="w-full lg:w-1/2">
          <div class="lg:max-w-lg">
            <h1 class="font-semibold text-gray-800 dark:text-white lg:text-6xl">À propos de <span
                class="text-blue-500 ">nous</span>
            </h1>

            <p class="mt-3 text-2xl text-gray-600 dark:text-gray-400">Wali Technologies est une société de développement
              d'applications et de logiciels qui couvre les besoins métiers spécifiques de nos clients en utilisant les
              meilleurs solutions technologiques
            </p>

            <NuxtLink to="/contact"
              class="mt-5 inline-flex items-center justify-center px-6 py-3 text-white duration-300 bg-blue-600 rounded-lg hover:bg-blue-500 focus:ring focus:ring-blue-300 focus:ring-opacity-80">
              Nous contacter
            </NuxtLink>
          </div>
        </div>

        <div class="flex items-center justify-center w-full mt-6 lg:mt-0 lg:w-1/2">
          <img class="w-full h-full lg:max-w-3xl" src="https://merakiui.com/images/components/Catalogue-pana.svg"
            alt="Catalogue-pana.svg">
        </div>
      </div>
    </div>
  </div>
</template>