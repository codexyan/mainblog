<script setup>
import Images from '../components/homepage/hero/Images.vue';
</script>

<template>
    <main>
        <div class="flex md:flex-row flex-col-reverse gap-4 md:justify-between">
            <!-- Desciption Left -->
            <div class="description-left md:w-7/12 md:p-5">
                <h1 class="text-5xl font-bold text-transparent md:text-5xl text-white bg-clip-text md:py-4">
                    Who is Iyan?
                </h1>
                <h6 class="mt-5 text-gray-200 py-2 px-5 text-sm rounded-md bg-gray-900 w-max">🎯 Short Self-description</h6>
                <p class="mt-4 text-sm leading-7 text-gray-400 md:text-sm md:leading-7">
                    Muhammad Fakhrian itulah nama saya. Tetapi, agar mudah di ingat saya memberikan nama panggilan dengan
                    sebutan 'Iyan' saja. Saya adalah orang yang memiliki minat luas dan suka mengeksplorasi hal-hal baru,
                    terkadang dengan menulis adalah salah satu cara saya belajar.
                </p>
                <h6 class="mt-5 text-gray-200 py-2 px-5 text-sm rounded-md bg-gray-900 w-max">💡 What do you do ? </h6>
                <p class="mt-4 text-sm leading-7 text-gray-400 md:text-sm md:leading-7">
                    Sehari-hari bekerja sebagai Frontend Engineer, namun tidak terbatas pada itu, saya juga senang
                    mengeksplorasi design UI dan kemudahan pengguna dalam berselancar dengan aplikasi, mungkin saat ini
                    menyebutnya UX Engineer bukan?
                </p>
                <p class="mt-4 text-sm leading-7 text-gray-400 md:text-sm md:leading-7">
                    Akrab dengan dunia teknologi sejak duduk di bangku SMP. Serius menekuni dunia perkodean dimulai sejak akhir 2021. Dimulai dari belajar bahasa C++ pada awal perkuliahan, kemudian berlanjut ke bidang Front-end dan keterusan untuk mempelajarinya. Namun kemudian nyaman dan memutuskan berlabuh di dunia developer. Menulis kode dalam bahasa TypeScript (JavaScript), dan Dart (Flutter).
                </p>
                <p class="mt-4 text-sm leading-7 text-gray-400 md:text-sm md:leading-7">
                    Lulus (2022) dari bangku kuliah sebagai Mahasiswa Informatika di Universitas Amikom Yogyakarta, Daerah Istimewa Yogyakarta.
                </p>
                <h6 class="my-5 text-gray-200 py-2 px-5 text-sm rounded-md bg-gray-900 w-max">💡 Motivation </h6>
                <q class="italic font text-sm leading-7 text-gray-400 md:text-sm md:leading-7">
                    Kita tak pernah tau amalan yang mana yang akan membawa kita ke surga. … . Yang jelas jangan pernah meremehkan amal sholeh, sekecil apapun amalan itu. Karena dahulu seorang pelacur masuk surga hanya karena memberi minum seekor anjing yang kehausan. — Ustadz Aan Chandra Talib
                </q>
            </div>

            <!-- Description Right -->
            <div class="description-right md:w-5/12 mx-auto h-full">
                <Images />
            </div>
        </div>
    </main>
</template>

<style scoped></style>
