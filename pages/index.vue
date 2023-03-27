<template>
  <div
    class="py-11 lg:px-[200px] xl:px-[300px] 2xl:px-[600px] px-8 font-mono text-primary min-h-screen"
  >
    <!-- HEADER -->
    <div>
      <div>
        <img src="~/assets/images/svg/logo.svg" alt="Discover Nuxt 3" />
      </div>
    </div>

    <!-- PROFILE -->
    <div class="mt-20">
      <!-- image -->
      <div class="flex flex-col items-center justify-center">
        <div>
          <img src="~/assets/images/svg/ava1.svg" alt="Discover Nuxt 3" />
        </div>
        <div>
          <h1 class="text-4xl">Halo</h1>
        </div>
        <div class="font-bold text-xl mt-2">Mr.XXXXXX2020</div>
      </div>

      <!-- rank -->
      <div class="mt-8">
        <div class="flex flex-col items-center justify-center italic">
          <div>Skor Terakhir : 14 pt</div>
          <div>Skor Tertinggi : 34 pt</div>
        </div>
      </div>

      <!-- start button -->
      <div class="mt-20">
        <div class="flex items-center justify-center">
          <div class="text-2xl bg-primary text-white py-3 px-20">Mulai</div>
        </div>
      </div>
    </div>

    <!-- NAVBAR -->
  </div>
  <div
    class="w-full h-20 lg:px-[200px] xl:px-[300px] 2xl:px-[600px] bg-white px-16 py-4 flex justify-between text-gray-font fixed bottom-0 shadow-lg z-40"
  >
    <div>
      <img src="~/assets/images/svg/list.svg" />
    </div>
    <div>
      <img src="~/assets/images/svg/home_active.svg" />
    </div>
    <div>
      <img src="~/assets/images/svg/profile.svg" />
    </div>
  </div>
</template>

<script setup></script>

<style scoped></style>
