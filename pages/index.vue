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
          class="bg-white p-4 pb-10 rounded-lg shadow-2xl border-2 border-sky-200 rotate-[-2deg] transition-all duration-500 group-hover:rotate-0 group-hover:scale-105"
        >
          <!-- Photo Area -->
          <div
            class="w-72 h-72 bg-gradient-to-br from-sky-400 to-sky-600 rounded flex items-center justify-center border-2 border-sky-300 shadow-lg"
          >
            <div class="text-center text-sky-900">
              <p class="text-lg font-semibold">Photo placeholder</p>
              <!-- <img src="/assets/images/pic.JPG" alt=""> -->
            </div>
          </div>

          <!-- Name and Title -->
          <div class="mt-4 text-center space-y-2">
            <h1 class="text-2xl font-bold text-sky-900">Serli Gharapetian</h1>
            <p class="text-md text-sky-700 font-medium">Front-End Developer</p>
          </div>
        </div>
      </div>

      <!-- Navigation Buttons -->
      <div class="flex flex-col gap-6">
        <NuxtLink
          to="/resume"
          class="group bg-sky-500 text-white font-semibold py-4 px-8 rounded-lg shadow-lg hover:bg-gradient-to-r hover:from-sky-600 hover:to-blue-600 hover:translate-x-1 transition-all duration-300 text-lg flex items-center justify-center gap-3 focus:outline-none"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="size-6"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m0 12.75h7.5m-7.5 3H12M10.5 2.25H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z"
            />
          </svg>
          <span>View Resume</span>
        </NuxtLink>
        <NuxtLink
          to="/projects"
          class="group bg-sky-500 text-white font-semibold py-4 px-8 rounded-lg shadow-lg hover:bg-sky-600 hover:shadow-[0_0_20px_5px_rgba(56,189,248,0.4)] transition-all duration-300 text-lg flex items-center justify-center gap-3 focus:outline-none"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="size-6 group-hover:scale-110 group-hover:rotate-12 transition-transform duration-300"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M14.25 9.75 16.5 12l-2.25 2.25m-4.5 0L7.5 12l2.25-2.25M6 20.25h12A2.25 2.25 0 0 0 20.25 18V6A2.25 2.25 0 0 0 18 3.75H6A2.25 2.25 0 0 0 3.75 6v12A2.25 2.25 0 0 0 6 20.25Z"
            />
          </svg>
          <span>View Projects</span>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style></style>
