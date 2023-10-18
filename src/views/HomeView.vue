<template>
    <main class="md:w-full md:py-12">
        <div class="w-auto px-4 mx-auto md:relative md:overflow-hidden md:max-w-7xl md:px-24">
            <!-- Hero Banner -->
            <div class="flex flex-col-reverse gap-4 md:flex md:flex-row sm:flex-col-reverse">
                <!-- Hero Content -->
                <div class="md:w-2/3 md:p-9 md:flex md:flex-col md:justify-center">
                    <h1
                        class="text-5xl font-bold text-transparent md:text-5xl bg-gradient-to-r from-blue-500 via-red-500 to-purple-500 bg-clip-text md:py-4">
                        UX Engineer, Nakama
                    </h1>
                    <p class="mt-4 text-sm leading-7 text-gray-400 md:text-base md:leading-7">
                        Hi 🖐 , I'm M. Fakhrian, a Computer Science graduate from Indonesia
                        passionate about crafting efficient user interfaces. I'm also an ERP
                        enthusiast, merging technology and business processes for optimal
                        outcomes.
                    </p>

                    <!-- CTA hero -->
                    <div class="mt-6">
                        <div class="">
                            <a href="#"
                                class="flex items-center justify-center w-full px-8 py-3 text-base font-medium text-white bg-gray-800 border border-transparent rounded-md sm:w-3/5 md:w-1/3 lg:w-1/3 hover:bg-indigo-700 md:py-2 md:text-lg md:px-10 hover:shadow">
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

            <!-- <hr class="my-6 opacity-10"> -->

            <!-- Collaborated -->
            <div class="my-12 md:my-6 container-collaborated">
                <div class="wrap-corated">
                    <h1 class="text-xs text-center text-gray-400 md:text-gray-300 md:text-sm ">
                        Have Worked With
                    </h1>

                    <div class="grid items-center w-full grid-cols-3 gap-5 mt-4 text-center md:grid-cols-8">
                        <div class="flex items-center justify-center h-12 px-3 py-4 overflow-hidden bg-white rounded-sm bg-opacity-10 compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-1.png" alt="logoweb.png" class="" />
                        </div>
                        <div class="flex items-center justify-center h-12 px-3 py-4 overflow-hidden bg-white rounded-sm bg-opacity-10 compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-2.png" alt="logoweb.png" />
                        </div>
                        <div class="flex items-center justify-center h-12 px-3 py-4 overflow-hidden bg-white rounded-sm bg-opacity-10 compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-3.png" alt="logoweb.png" />
                        </div>
                        <div class="flex items-center justify-center h-12 px-3 py-4 overflow-hidden bg-white rounded-sm bg-opacity-10 compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-4.png" alt="logoweb.png" />
                        </div>
                        <div class="flex items-center justify-center h-12 px-3 py-4 overflow-hidden bg-white rounded-sm bg-opacity-10 compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-5.png" alt="logoweb.png" />
                        </div>
                        <div class="flex items-center justify-center h-12 px-3 py-4 overflow-hidden bg-white rounded-sm bg-opacity-10 compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-6.png" alt="logoweb.png" />
                        </div>
                        <div class="flex items-center justify-center h-12 px-3 py-4 overflow-hidden bg-white rounded-sm bg-opacity-10 compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-7.png" alt="logoweb.png" />
                        </div>
                        <div class="flex items-center justify-center h-12 px-3 py-4 overflow-hidden bg-white rounded-sm bg-opacity-10 compimg">
                            <img src="@/assets/img/compicon/compicons-gray/compicon-1.png" alt="logoweb.png" />
                        </div>
                    </div>

                </div>
            </div>

            <!-- Article -->
            <div class="container mt-5 md:mt-20">
                <div class="flex flex-col md:flex-row md:justify-between wrap gap-9">
                    <!-- Blog -->
                    <div class="md:w-4/6 blog-wrap">
                        <h1 class="text-2xl font-bold text-gray-300">
                            👨‍💻 Learn with Writing
                        </h1>
                        <div class="flex flex-col gap-8 mt-6 card-container">
                            <!-- Article -->
                            <div class="card">
                                <div class="flex flex-row items-center gap-4 row">
                                    <img class="object-cover h-40 rounded-md w-28 md:h-36 md:w-44"
                                        src="@/assets/img/images/img-card-erp.png" alt="card.png" />
                                    <div class="flex flex-col gap-2 content-card">
                                        <a href="#" class="text-xl font-bold text-gray-200 md:text-xl">
                                            Kenalan sama Ekosistem ERP
                                        </a>
                                        <p
                                            class="text-sm leading-6 tracking-tighter text-gray-500 md:tracking-wider md:text-sm">
                                            Jelajahi Kreativitas Tanpa Batas: Pahami Gestalt Principle
                                            dalam Satu Praktek! Temukan Rasa Memukau Desain UI dalam
                                            Sekejap Mata!
                                        </p>
                                        <a href="#" class="text-sm font-semibold text-indigo-500">Read More »</a>
                                    </div>
                                </div>
                            </div>

                            <div class="card">
                                <div class="flex flex-row-reverse items-center gap-4 md:flex-row row">
                                    <img class="object-cover h-40 rounded-md w-28 md:h-36 md:w-44"
                                        src="@/assets/img/images/img-card-artdir.png" alt="card.png" />
                                    <div class="flex flex-col gap-2 content-card">
                                        <a href="#" class="text-xl font-bold text-gray-200 md:text-xl">
                                            Nekat Jadi PM Art Director
                                        </a>
                                        <p
                                            class="text-sm leading-6 tracking-tighter text-gray-500 md:tracking-wider md:text-sm">
                                            Jelajahi Kreativitas Tanpa Batas: Pahami Gestalt Principle
                                            dalam Satu Praktek! Temukan Rasa Memukau Desain UI dalam
                                            Sekejap Mata!
                                        </p>
                                        <a href="#" class="text-sm font-semibold text-indigo-500">Read More »</a>
                                    </div>
                                </div>
                            </div>

                            <div class="card">
                                <div class="flex flex-row items-center gap-4 row">
                                    <img class="object-cover h-40 rounded-md w-28 md:h-36 md:w-44"
                                        src="@/assets/img/images/img-card.png" alt="card.png" />
                                    <div class="flex flex-col gap-2 content-card">
                                        <a href="#" class="text-xl font-bold text-gray-200 md:text-xl">
                                            Pahami UX Gestalt Principle dalam Sekejap!
                                        </a>
                                        <p
                                            class="text-sm leading-6 tracking-tighter text-gray-500 md:tracking-wider md:text-sm">
                                            Jelajahi Kreativitas Tanpa Batas: Pahami Gestalt Principle
                                            dalam Satu Praktek! Temukan Rasa Memukau Desain UI dalam
                                            Sekejap Mata!
                                        </p>
                                        <a href="#" class="text-sm font-semibold text-indigo-500">Read More »</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Experience -->
                    <div class="h-full bg-gray-800 md:w-2/6 bg-opacity-40 ex-wrap rounded-xl">
                        <div class="flex flex-col gap-4 p-5">
                            <h1 class="text-lg font-bold text-gray-300">✨ Experience</h1>

                            <div class="flex flex-col gap-4 company-describe">
                                <div class="flex flex-row items-center justify-between w-full gap-4 company">
                                    <div class="flex items-center justify-center w-1/6 imgex">
                                        <img src="@/assets/img/compicon/exicon.png" alt="exicon.png" />
                                    </div>
                                    <div class="flex flex-col w-5/6 textcomp">
                                        <div class="flex items-center justify-between header">
                                            <h1 class="text-sm font-bold text-white">
                                                Broadways HRIS
                                            </h1>
                                            <h1 class="text-xs text-white">Full Time</h1>
                                        </div>
                                        <div class="flex justify-between sub">
                                            <p class="text-xs text-gray-500">Product Specialist</p>
                                            <p class="text-xs text-gray-500">Nov 22 - Jun 23</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="flex flex-row items-center justify-between w-full gap-4 company">
                                    <div class="flex items-center justify-center w-1/6 imgex">
                                        <img src="@/assets/img/compicon/exicon.png" alt="exicon.png" />
                                    </div>
                                    <div class="w-5/6 textcomp">
                                        <div class="flex items-center justify-between header">
                                            <h1 class="text-white">RUN System</h1>
                                            <h1 class="text-xs text-white">Internship</h1>
                                        </div>
                                        <div class="flex justify-between sub">
                                            <p class="text-xs text-gray-500">Business Analyst</p>
                                            <p class="text-xs text-gray-500">Nov 22 - Jan 23</p>
                                        </div>
                                    </div>
                                </div>

                                <div class="flex flex-row items-center justify-between w-full gap-4 company">
                                    <div class="flex items-center justify-center w-1/6 imgex">
                                        <img src="@/assets/img/compicon/exicon.png" alt="exicon.png" />
                                    </div>
                                    <div class="w-5/6 textcomp">
                                        <div class="flex items-center justify-between header">
                                            <h1 class="text-white">BeautyLux Skincare</h1>
                                            <h1 class="text-xs text-white">Internship</h1>
                                        </div>
                                        <div class="flex justify-between sub">
                                            <p class="text-xs text-gray-500">Brand Designer</p>
                                            <p class="text-xs text-gray-500">Nov 22 - Jan 23</p>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <div class="flex mt-3 cta-email">
                                <a href="#" class="w-full py-2 text-center text-gray-500 bg-white rounded-md bg-opacity-5 hover:text-white">Download CV</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>
