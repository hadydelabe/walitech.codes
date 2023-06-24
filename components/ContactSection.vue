<template>
<div
  class="grid p-2 leading-6 text-black border-b-0 border-t-8 border-solid lg:p-20 border-x-0 border-slate-300 bg-slate-500"
  id="lead"
  style="border-width: 0px;"
>
  <div class="text-black">
    <div class="flex justify-center mt-12">
      <div class="p-4 w-full rounded-sm md:w-1/2">
        <div
          class="relative py-2 px-3 mt-10 rounded-lg"
          style="box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px;"
        >
          <label
            for="name"
            class="inline-block absolute left-2 -top-2 px-3 -mt-5 font-medium tracking-widest text-white cursor-default"
            >Nombre</label
          ><input
            type="text"
            name="name"
            id="name"
            class="block p-4 m-0 w-full h-12 text-lg font-normal tracking-widest leading-7 bg-white rounded border-0 border-gray-500 border-solid appearance-none cursor-text bg-opacity-[0.4] focus:border-blue-600 focus:outline-offset-2"
            placeholder=""
          />
        </div>
        <p
          class="inline-block left-2 px-3 mx-0 mt-4 mb-0 font-medium tracking-widest text-white"
        >
          Teléfono
        </p>
        <div class="flex gap-0">
          <div class="w-2/3">
            <div class="p-3 mt-1 h-12">
              <div class="relative h-12 bg-white pointer-events-auto">
                <div class="relative">
                  <input
                    type="text"
                    class="block py-2 pr-12 pl-4 m-0 w-full h-10 text-sm rounded border border-gray-200 border-solid appearance-none cursor-text focus:border-blue-600 focus:outline-offset-2"
                    autocomplete="off"
                    aria-readonly="false"
                    aria-disabled="false"
                    id="vue_country_intl-1-input"
                    placeholder="Código"
                    style="line-height: 1.42857; outline: none;"
                  /><label
                    class="overflow-hidden absolute py-2 px-4 h-12 text-sm font-normal leading-7 text-cyan-900 whitespace-nowrap rounded cursor-text"
                    style="inset: 1px;"
                    ><span
                      class="inline-block mr-2 w-5 h-3 text-lg align-middle bg-no-repeat bg-zinc-300"
                      style='box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px; background-image: url("/assets/flags-2x-196dacee.5ce8d5d7.png"); background-position: -2083px 0px; background-size: 5630px 15px;'
                    ></span
                    ><span class="inline-block text-lg align-middle"
                      >+502</span
                    ></label
                  ><label
                    class="absolute right-0 top-1/2 left-1/2 pr-10 mr-0 mb-0 -mt-1 -ml-1 h-full rounded border-4 border-transparent border-solid cursor-default"
                    style='transition: transform 0.3s ease 0s; content: " "; border-image: initial;'
                  ></label>
                  <div class="hidden"></div>
                </div>
                <!--v-if-->
              </div>
            </div>
          </div>
          <div
            class="relative py-2 pr-3 pl-0 mt-4 w-full rounded-lg"
            style="box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px;"
          >
            <input
              type="phone"
              name="phone"
              maxlength="10"
              id="phone"
              class="block p-4 mx-0 mb-0 -mt-2 w-full h-12 text-lg font-normal tracking-widest leading-7 bg-white rounded cursor-text bg-opacity-[0.4]"
              placeholder=""
            />
          </div>
        </div>
        <div
          class="relative py-2 px-3 mt-10 rounded-lg"
          style="box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px;"
        >
          <label
            for="name"
            class="inline-block absolute left-2 -top-2 px-3 -mt-4 font-medium tracking-widest text-white cursor-default"
            >Correo</label
          ><input
            type="email"
            name="email"
            id="email"
            class="block p-4 m-0 w-full h-12 text-lg font-normal tracking-widest leading-7 bg-white rounded border border-gray-500 border-solid appearance-none cursor-text bg-opacity-[0.4] focus:border-blue-600 focus:outline-offset-2"
            placeholder=""
          />
        </div>
        <div class="flex justify-end p-2 mt-10 md:mt-8">
          <button
            class="py-4 px-8 mx-0 mt-0 mb-4 w-full text-xl font-semibold tracking-wider leading-7 text-center normal-case bg-none rounded-lg opacity-40 cursor-pointer md:text-xl md:leading-7 bg-slate-300 text-slate-900"
          >
            Completa tus datos</button
          ><!----><!---->
        </div>
      </div>
    </div>
  </div>
</div>

</template>

<script setup>

</script>



<style>

</style>
