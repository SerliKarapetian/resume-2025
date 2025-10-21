<template>
  <div
    class="min-h-screen bg-gradient-to-br from-sky-950 via-sky-900 to-sky-800 flex items-center justify-center p-4 sm:p-6 lg:p-8 relative"
  >
    <div
      class="flex flex-col lg:flex-row items-center gap-12 lg:gap-16 max-w-6xl relative z-10"
    >
      <!-- Polaroid Container -->
      <div class="relative group">
        <!-- Polaroid Frame -->
        <div
          class="bg-white p-6 pb-10 rounded-xl shadow-2xl border-8 border-sky-200 rotate-[-2deg] transition-all duration-500 group-hover:rotate-0 group-hover:scale-105"
        >
          <!-- Photo Area -->
          <div
            class="w-64 h-64 bg-gradient-to-br from-sky-400 to-sky-600 rounded flex items-center justify-center border-4 border-sky-300 shadow-lg"
          >
            <div class="text-center text-sky-900">
              <p class="text-lg font-semibold">Photo placeholder</p>
            </div>
          </div>

          <!-- Name and Title -->
          <div class="mt-4 text-center space-y-2">
            <h1 class="text-3xl font-bold text-sky-900">Serli Gharapetian</h1>
            <div class="h-0.5 w-16 bg-sky-500 mx-auto"></div>
            <p class="text-lg text-sky-700 font-medium">
              Front-End Developer
            </p>
          </div>

        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style></style>
