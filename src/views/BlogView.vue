<script setup>
import Images from '../components/homepage/hero/Images.vue';
</script>

<template>
    <main>
        <div class="container mt-5 md:mt-4">
            <div class="flex flex-col md:flex-row md:justify-between wrap gap-9">
                <!-- Blog -->
                <div class="flex flex-col gap-8 md:w-4/6 blog-wrap">
                    <div class="flex flex-col gap-3 title">
                        <h1 class="text-xl font-bold text-gray-300 md:text-4xl">
                            👨‍💻 Learn by Writing Anything
                        </h1>
                        <p class="text-sm font-light text-gray-400">All my insightful reflections on programming and
                            personal growth.</p>
                    </div>
                    <div class="input-search">
                        <label class="relative block">
                            <span class="sr-only">Search</span>
                            <span class="absolute inset-y-0 left-0 flex items-center pl-2">
                                <svg class="w-5 h-5 fill-white" viewBox="0 0 20 20"><!-- ... --></svg>
                            </span>
                            <input
                                class="block w-2/3 py-2 pr-3 bg-gray-800 border rounded-lg shadow-sm placeholder:italic placeholder:text-slate-400 border-slate-300 pl-9 focus:outline-none focus:border-sky-500 focus:ring-sky-500 focus:ring-1 sm:text-sm"
                                placeholder="Search for anything..." type="text" name="search" />
                        </label>
                    </div>
                    <div class="flex flex-row items-center gap-3 filters">
                        <h1 class="text-gray-300">Filters :</h1>
                        <a href="#" class="px-3 py-1 text-gray-400 bg-gray-800 rounded-sm">General</a>
                        <a href="#" class="px-3 py-1 text-gray-400 bg-gray-800 rounded-sm">Programming</a>
                        <a href="#" class="px-3 py-1 text-gray-400 bg-gray-800 rounded-sm">Insight</a>
                    </div>

                    <div class="flex flex-col gap-6 card-blog md:mt-10">
                        <div class="card">
                            <div class="flex flex-row-reverse items-start gap-6 md:flex-row row">
                                <img class="object-cover h-full rounded-md w-28 md:h-36 md:w-56"
                                    src="@/assets/img/images/img-card-artdir.png" alt="card.png" />
                                <div class="flex flex-col gap-4 content-card">
                                    <a href="#" class="text-lg font-bold text-gray-200 md:text-xl">
                                        Nekat Jadi PM Director
                                    </a>
                                    <p
                                        class="overflow-hidden text-xs leading-4 text-gray-500 md:leading-6 md:tracking-wider md:text-sm">
                                        Jelajahi Kreativitas Tanpa Batas: Pahami Gestalt Principle
                                        dalam Satu Praktek!
                                    </p>
                                    <a href="#" class="text-sm font-semibold text-indigo-500">Read More »</a>
                                </div>
                            </div>
                        </div>
                        <div class="card">
                            <div class="flex flex-row-reverse items-start gap-6 md:flex-row row">
                                <img class="object-cover h-full rounded-md w-28 md:h-36 md:w-56"
                                    src="@/assets/img/images/img-card-artdir.png" alt="card.png" />
                                <div class="flex flex-col gap-4 content-card">
                                    <a href="#" class="text-base font-bold text-gray-200 md:text-xl">
                                        Nekat Jadi PM Director
                                    </a>
                                    <p
                                        class="overflow-hidden text-xs leading-4 text-gray-500 md:leading-6 md:tracking-wider md:text-sm">
                                        Jelajahi Kreativitas Tanpa Batas: Pahami Gestalt Principle
                                        dalam Satu Praktek!
                                    </p>
                                    <a href="#" class="text-sm font-semibold text-indigo-500">Read More »</a>
                                </div>
                            </div>
                        </div>
                        <div class="card">
                            <div class="flex flex-row-reverse items-start gap-6 md:flex-row row">
                                <img class="object-cover h-full rounded-md w-28 md:h-36 md:w-56"
                                    src="@/assets/img/images/img-card-artdir.png" alt="card.png" />
                                <div class="flex flex-col gap-4 content-card">
                                    <a href="#" class="text-base font-bold text-gray-200 md:text-xl">
                                        Nekat Jadi PM Director
                                    </a>
                                    <p
                                        class="overflow-hidden text-xs leading-4 text-gray-500 md:leading-6 md:tracking-wider md:text-sm">
                                        Jelajahi Kreativitas Tanpa Batas: Pahami Gestalt Principle
                                        dalam Satu Praktek!
                                    </p>
                                    <a href="#" class="text-sm font-semibold text-indigo-500">Read More »</a>
                                </div>
                            </div>
                        </div>
                        <div class="card">
                            <div class="flex flex-row-reverse items-start gap-6 md:flex-row row">
                                <img class="object-cover h-full rounded-md w-28 md:h-36 md:w-56"
                                    src="@/assets/img/images/img-card-artdir.png" alt="card.png" />
                                <div class="flex flex-col gap-4 content-card">
                                    <a href="#" class="text-base font-bold text-gray-200 md:text-xl">
                                        Nekat Jadi PM Director
                                    </a>
                                    <p
                                        class="overflow-hidden text-xs leading-4 text-gray-500 md:leading-6 md:tracking-wider md:text-sm">
                                        Jelajahi Kreativitas Tanpa Batas: Pahami Gestalt Principle
                                        dalam Satu Praktek!
                                    </p>
                                    <a href="#" class="text-sm font-semibold text-indigo-500">Read More »</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Experience -->
                <div class="h-full mx-auto md:w-2/6">
                    <Images />
                </div>
            </div>
        </div>
    </main>
</template>