<script setup>
import Experience from './experience/Experience.vue';
import Article from './article/Article.vue';
</script>

<template>
    <div class="container mt-5 md:mt-20">
        <div class="flex flex-col md:flex-row md:justify-between wrap gap-9">
            <!-- Blog -->
            <div class="md:w-4/6 blog-wrap">
                <h1 class="text-xl font-bold text-gray-300 md:text-2xl">
                    👨‍💻 Learn with Writing
                </h1>
                <Article />
            </div>

            <!-- Experience -->
            <div class="h-full bg-gray-800 md:w-2/6 bg-opacity-40 ex-wrap rounded-xl">
                <Experience />
            </div>
        </div>
    </div>
</template>