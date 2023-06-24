<script setup>
import { ref } from 'vue';

let open = ref(false);
</script>

<template>
  <header class="bg-indigo-500">
        <nav class="container relative flex items-center justify-between px-6 py-8 mx-auto text-white">
            <a href="#">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8 md:w-10 md:h-10" fill="none" viewBox="0 0 24 24"
                    stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round"
                        d="M4 5a1 1 0 011-1h14a1 1 0 011 1v2a1 1 0 01-1 1H5a1 1 0 01-1-1V5zM4 13a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H5a1 1 0 01-1-1v-6zM16 13a1 1 0 011-1h2a1 1 0 011 1v6a1 1 0 01-1 1h-2a1 1 0 01-1-1v-6z" />
                </svg>
            </a>
    
            <button @click="open = !open" class="md:hidden">
                <span v-show="!open">
                    <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24"
                        stroke="currentColor" stroke-width="2">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16m-7 6h7" />
                    </svg>
                </span>
    
                <span v-show="open">
                    <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd"
                            d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                            clip-rule="evenodd" />
                    </svg>
                </span>
            </button>
    
            <div :class="[open ? 'translate-x-0 opacity-100 ' : 'opacity-0 -translate-x-full']"
                class="absolute inset-x-0 z-30 w-full px-6 py-8 mt-4 space-y-6 transition-all duration-300 ease-in-out bg-indigo-600 top-16 md:mt-0 md:p-0 md:top-0 md:relative md:bg-transparent md:w-auto md:opacity-100 md:translate-x-0 md:space-y-0 md:-mx-6 md:flex md:items-center">
                <a href="#" class="block text-white transition-colors duration-300 md:px-6 hover:text-indigo-300">Accueil</a>
                <a href="#" class="block text-white transition-colors duration-300 md:px-6 hover:text-indigo-300"> À propos de nous
                </a>
                <a href="#" class="block text-white transition-colors duration-300 md:px-6 hover:text-indigo-300"> Contact
                </a>
            </div>
        </nav>
    </header>
    
    <main>
        <section>
            <div class="relative grid w-full bg-indigo-500 h-96 lg:h-[32rem] place-items-center">
                <div class="flex flex-col items-center mx-auto text-center">
                    <h1 class="text-4xl font-semibold text-white uppercase md:text-6xl">Conception logiciels sur mesure</h1>
    
                    <p class="mt-6 text-lg leading-5 text-white">Transformez vos idées en réalité numérique</p>
    
                    <a href="#about" class="mt-8 cursor-pointer animate-bounce">
                        <svg width="53" height="53" viewBox="0 0 53 53" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="27" cy="26" r="18" stroke="white" stroke-width="2" />
                            <path
                                d="M22.41 23.2875L27 27.8675L31.59 23.2875L33 24.6975L27 30.6975L21 24.6975L22.41 23.2875Z"
                                fill="white" />
                        </svg>
                    </a>
                </div>
            </div>
    
            <svg class="fill-indigo-500" viewBox="0 0 1440 57" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M1440 0H0V57C720 0 1440 57 1440 57V0Z" />
            </svg>
        </section>
        <section class="container px-6 py-8 mx-auto lg:py-16 " id="about">
            <div class="lg:flex lg:items-center lg:-mx-4">
                <div class="lg:w-1/2 lg:px-4">
                    <h3 class="text-xl font-medium text-gray-800 md:text-2xl lg:text-3xl">NOUS RÉALISONS VOS APPLICATIONS ET PRODUITS LOGICIELS.</h3>
    
                    <p class="mt-6 text-gray-500 ">Spécialisées en ingénierie logicielle, nos équipes vous accompagnent sur toutes les étapes de réalisation de vos produits (applications, plateformes, API, ...).</p>
    
                    <button class="flex items-center mt-8 -mx-2 text-indigo-500" v-if="true == false" >
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8 mx-1" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M14.752 11.168l-3.197-2.132A1 1 0 0010 9.87v4.263a1 1 0 001.555.832l3.197-2.132a1 1 0 000-1.664z" />
                            <path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                        </svg>
                        <p class="mx-1 font-semibold">PLAY VIDEO</p>
                    </button>
                </div>
    
                <div class="mt-8 lg:w-1/2 lg:px-4 lg:mt-0">
                    <img class="object-cover w-full rounded-xl h-96"
                        src="https://images.unsplash.com/photo-1516131206008-dd041a9764fd?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=880&q=80"
                        alt="Video thumbnail">
                </div>
            </div>
        </section>
        <AppSection2_11/>
        <section class="container px-6 py-8 mx-auto lg:py-16" v-if="true === false">
            <h3 class="text-xl font-medium text-gray-800 md:text-2xl lg:text-3xl ">Browse Our Projects</h3>
    
            <div class="flex items-center py-6 mt-4 -mx-2 overflow-x-auto whitespace-nowrap">
                <button
                    class=" inline-flex px-4 mx-2 focus:outline-none  items-center py-0.5 text-white bg-indigo-500 hover:bg-indigo-400 duration-300 transition-colors rounded-2xl">All</button>
                <button
                    class=" inline-flex px-4 mx-2 duration-300 transition-colors hover:bg-indigo-500/70 hover:text-white text-gray-500 focus:outline-none py-0.5 cursor-pointer rounded-2xl">Web
                    Design</button>
                <button
                    class=" inline-flex px-4 mx-2 duration-300 transition-colors hover:bg-indigo-500/70 hover:text-white text-gray-500 focus:outline-none py-0.5 cursor-pointer rounded-2xl">Development</button>
                <button
                    class=" inline-flex px-4 mx-2 duration-300 transition-colors hover:bg-indigo-500/70 hover:text-white text-gray-500 focus:outline-none py-0.5 cursor-pointer rounded-2xl">Research</button>
            </div>
    
            <div class="grid grid-cols-1 gap-10 mt-10 md:grid-cols-2 lg:grid-cols-3 ">
                <a href="#" class="transition-all duration-500 lg:col-span-2 hover:scale-105">
                    <img class="object-cover object-top w-full rounded-lg shadow-md shadow-gray-200 h-80 xl:h-96"
                        src="https://cdn.dribbble.com/users/1644453/screenshots/17056773/media/00509f74e765da294440886db976943a.png?compress=1&resize=1000x750&vertical=top"
                        alt="">
                </a>

                <a href="#" class="transition-all duration-500 hover:scale-105">
                    <img class="object-cover object-top w-full rounded-lg shadow-md shadow-gray-200 h-80 xl:h-96 "
                        src="https://cdn.dribbble.com/userupload/3233220/file/original-e80767b5947df65a0f1ab4dab4964679.png?compress=1&resize=1024x768"
                        alt="">
                </a>

                <a href="#" class="transition-all duration-500 hover:scale-105">
                    <img class="object-cover object-top w-full rounded-lg shadow-md shadow-gray-200 h-80 xl:h-96"
                        src="https://cdn.dribbble.com/users/1644453/screenshots/14748860/media/25f53296059b741ac1c083be9f41745b.png?compress=1&resize=1000x750&vertical=top"
                        alt="">
                </a>

                <a href="#" class="transition-all duration-500 lg:col-span-2 hover:scale-105">
                    <img class="object-cover object-top w-full rounded-lg shadow-md shadow-gray-200 h-80 xl:h-96"
                        src="https://cdn.dribbble.com/users/878428/screenshots/17307425/media/01782a518148ce7ef2e790473c888b1f.png?compress=1&resize=1000x750&vertical=top"
                        alt="">
                </a>

                <a href="#" class="transition-all duration-500 lg:col-span-2 hover:scale-105">
                    <img class="object-cover object-top w-full rounded-lg shadow-md shadow-gray-200 h-80 xl:h-96"
                        src="https://cdn.dribbble.com/users/1930709/screenshots/11466872/media/e50b0f02160a77397eb4a76782d23966.png?compress=1&resize=1000x750&vertical=top"
                        alt="">
                </a>

                <a href="#" class="transition-all duration-500 hover:scale-105">
                    <img class="object-cover object-top w-full rounded-lg shadow-md shadow-gray-200 h-80 xl:h-96"
                        src="https://cdn.dribbble.com/users/1644453/screenshots/14403641/media/21e305eb9c8255b6e3367f0ca52c6668.png?compress=1&resize=1000x750&vertical=top"
                        alt="">
                </a>
            </div>
        </section>
    
        <section class="container px-6 py-8 mx-auto lg:py-16">
            <h3 class="text-xl font-medium text-gray-800 md:text-2xl lg:text-3xl ">Recent Blog Posts</h3>
    
            <div class="grid grid-cols-1 gap-8 mt-8 md:mt-10 md:grid-cols-2 xl:grid-cols-3">
                <div>
                    <div class="relative">
                        <img class="object-cover object-center w-full h-64 rounded-lg lg:h-80"
                            src="https://images.unsplash.com/photo-1624996379697-f01d168b1a52?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80"
                            alt="">
    
                        <div class="absolute bottom-0 flex p-3 bg-white ">
                            <img class="object-cover object-center w-10 h-10 rounded-full"
                                src="https://cdn.dribbble.com/users/1436669/screenshots/15006128/media/5f91264b3b56cc452cb2bba2535bccdd.png?compress=1&resize=1000x750&vertical=top"
                                alt="">
    
                            <div class="mx-4">
                                <h1 class="text-sm text-gray-700">Tom Hank</h1>
                                <p class="text-sm text-gray-500">Creative Director</p>
                            </div>
                        </div>
                    </div>
    
                    <h1 class="mt-6 text-xl font-semibold text-gray-800">What do you want to know about UI
                    </h1>
    
                    <hr class="w-32 my-6 text-indigo-500">
    
                    <p class="text-sm text-gray-500">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis fugit dolorum amet dolores
                        praesentium, alias nam? Tempore
                    </p>
    
                    <a href="#" class="inline-block mt-4 text-indigo-500 underline hover:text-indigo-400">Read more</a>
                </div>
    
                <div>
                    <div class="relative">
                        <img class="object-cover object-center w-full h-64 rounded-lg lg:h-80"
                            src="https://images.unsplash.com/photo-1590283603385-17ffb3a7f29f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80"
                            alt="">
    
                        <div class="absolute bottom-0 flex p-3 bg-white ">
                            <img class="object-cover object-center w-10 h-10 rounded-full"
                                src="https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=880&q=80"
                                alt="">
    
                            <div class="mx-4">
                                <h1 class="text-sm text-gray-700">arthur melo</h1>
                                <p class="text-sm text-gray-500">Creative Director</p>
                            </div>
                        </div>
                    </div>
    
                    <h1 class="mt-6 text-xl font-semibold text-gray-800">All the features you want to know
                    </h1>
    
                    <hr class="w-32 my-6 text-indigo-500">
    
                    <p class="text-sm text-gray-500">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis fugit dolorum amet dolores
                        praesentium, alias nam? Tempore
                    </p>
    
                    <a href="#" class="inline-block mt-4 text-indigo-500 underline hover:text-indigo-400">Read more</a>
                </div>
    
                <div>
                    <div class="relative">
                        <img class="object-cover object-center w-full h-64 rounded-lg lg:h-80"
                            src="https://images.unsplash.com/photo-1597534458220-9fb4969f2df5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1374&q=80"
                            alt="">
    
                        <div class="absolute bottom-0 flex p-3 bg-white ">
                            <img class="object-cover object-center w-10 h-10 rounded-full"
                                src="https://images.unsplash.com/photo-1531590878845-12627191e687?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=764&q=80"
                                alt="">
    
                            <div class="mx-4">
                                <h1 class="text-sm text-gray-700">Amelia. Anderson</h1>
                                <p class="text-sm text-gray-500">Lead Developer</p>
                            </div>
                        </div>
                    </div>
    
                    <h1 class="mt-6 text-xl font-semibold text-gray-800">Which services you get from Meraki
                        UI</h1>
    
                    <hr class="w-32 my-6 text-indigo-500">
    
                    <p class="text-sm text-gray-500">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis fugit dolorum amet dolores
                        praesentium, alias nam? Tempore
                    </p>
    
                    <a href="#" class="inline-block mt-4 text-indigo-500 underline hover:text-indigo-400">Read more</a>
                </div>
            </div>
        </section>
    </main>
    
    <footer class="flex flex-col items-center py-20 text-white bg-gray-900">
        <p class="text-center">Copyright © 2020, Hero Header Inc.</p>
    
        <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6 mt-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"
            stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round"
                d="M8.684 13.342C8.886 12.938 9 12.482 9 12c0-.482-.114-.938-.316-1.342m0 2.684a3 3 0 110-2.684m0 2.684l6.632 3.316m-6.632-6l6.632-3.316m0 0a3 3 0 105.367-2.684 3 3 0 00-5.367 2.684zm0 9.316a3 3 0 105.368 2.684 3 3 0 00-5.368-2.684z" />
        </svg>
    </footer>
</template>
