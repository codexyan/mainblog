<template>
    <main class="md:w-full md:py-12">
        <div class="px-8 mx-auto md:relative md:overflow-hidden md:max-w-7xl md:px-24">

            <!-- Hero Banner -->
            <div class="flex flex-col-reverse gap-4 md:flex md:flex-row sm:flex-col-reverse">
                <!-- Hero Content -->
                <div class="md:w-2/3 md:p-9 md:flex md:flex-col md:justify-center">
                    <h1
                        class="text-5xl font-bold text-transparent md:text-5xl bg-gradient-to-r from-blue-500 via-red-500 to-purple-500 bg-clip-text md:py-4">
                        UX Engineer, Nakama
                    </h1>
                    <p class="mt-4 text-sm leading-7 text-gray-400 md:text-base md:leading-7" >
                        Hi 🖐 , I'm M. Fakhrian, a Computer Science graduate from Indonesia passionate about crafting
                        efficient user interfaces. I'm also an ERP enthusiast, merging technology and business processes for
                        optimal outcomes.
                    </p>

                    <!-- CTA hero -->
                    <div class="mt-6">
                        <div class="">
                            <a href="#"
                                class="flex items-center justify-center w-2/3 px-8 py-3 text-base font-medium text-white bg-gray-800 border border-transparent rounded-md sm:w-3/5 md:w-1/3 lg:w-1/3 hover:bg-indigo-700 md:py-2 md:text-lg md:px-10 hover:shadow">
                                Hire Me!
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Images -->
                <div class="md:w-1/3 md:flex md:justify-center md:items-center">
                    <img class="w-96" src="@/assets/img/images/banner.png" alt="banner.png" />
                </div>
            </div>

            <!-- Collaborated -->
            <div class="mt-6 container-collaborated">
                <div class="wrap-corated">
                    <h1 class="text-sm text-center text-white">Have Collaborated With</h1>
                    <div class="flex flex-wrap items-center justify-center w-11/12 gap-6 px-4 py-4 mx-auto mt-5 bg-gray-900 rounded-lg compicon">
                        <div class="compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-1.png" alt="logoweb.png" class="h-8">
                        </div>
                        <div class="compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-2.png" alt="logoweb.png" class="h-7">
                        </div>
                        <div class="compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-3.png" alt="logoweb.png" class="h-8">
                        </div>
                        <div class="compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-4.png" alt="logoweb.png" class="h-8">
                        </div>
                        <div class="compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-5.png" alt="logoweb.png" class="h-8">
                        </div>
                        <div class="compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-6.png" alt="logoweb.png" class="h-4">
                        </div>
                        <div class="compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-7.png" alt="logoweb.png" class="h-8">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>