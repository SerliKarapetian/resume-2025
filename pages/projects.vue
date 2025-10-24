<template>
  <div
    class="min-h-screen bg-gradient-to-br from-sky-950 via-sky-900 to-sky-800 text-gray-800 p-6 lg:p-10 font-[Georgia,serif]"
  >
    <section>
      <div class="container mx-auto px-4 max-w-7xl">
        <div class="text-center mb-16">
          <h2 class="text-4xl font-bold mb-4 text-gray-200">My Projects</h2>
          <p class="text-lg text-gray-200 max-w-3xl mx-auto leading-relaxed">
            A showcase of projects I’ve built to enhance my skills and explore
            innovative solutions.
          </p>
        </div>

        <!-- Projects Grid -->
        <div
          dir="ltr"
          class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 md:gap-8"
        >
          <div
            v-for="(project, index) in projects"
            :key="index"
            class="group relative bg-gray-50 rounded-3xl p-5 md:p-6 shadow-md hover:shadow-lg transition-all duration-500 border border-gradient-to-r from-blue-200 to-indigo-200 hover:scale-105 animate-fade-in"
          >
            <!-- Always visible content -->
            <div class="h-full flex flex-col">
              <!-- Category Badge -->
              <div
                class="absolute top-4 left-4 bg-blue-500 text-white text-xs font-semibold px-2 py-1 rounded-full"
              >
                {{ project.category }}
              </div>
              <!-- Image section -->
              <div class="relative z-10 flex justify-center h-24 mb-4">
                <div
                  class="w-24 h-24 flex items-center justify-center group-hover:scale-110 transition-all duration-400"
                >
                  <img
                    :src="project.image"
                    :alt="project.title"
                    class="object-contain w-full h-full"
                  />
                </div>
              </div>

              <!-- Content column -->
              <div class="flex-grow min-w-0">
                <h3 class="text-xl font-semibold text-gray-800 mb-3">
                  {{ project.title }}
                </h3>
                <p class="text-base text-gray-600 mb-6 leading-relaxed">
                  {{ project.shortDescription }}
                </p>
              </div>
            </div>

            <!-- Desktop Hover Content -->
            <div
              class="absolute inset-0 rounded-3xl p-5 md:p-6 opacity-0 group-hover:opacity-100 transition-all duration-500 backdrop-blur-md"
              :style="`background-color: ${project.bgColor}`"
            >
              <div class="grid gap-4 h-full">
                <!-- Empty space to align with visible content -->
                <div class="h-24"></div>
                <!-- Content column -->
                <div class="overflow-y-auto pr-2">
                  <h3 class="text-lg font-bold text-white mb-4">
                    {{ project.title }}
                  </h3>
                  <p class="text-white text-sm mb-2 line-clamp-3">
                    {{ project.description }}
                  </p>
                  <!-- <ul class="text-white text-sm space-y-2">
                    <li v-for="feature in project.features" :key="feature.label">
                      <span class="font-semibold">{{ feature.label }}:</span> {{ feature.value }}
                    </li>
                  </ul> -->
                </div>
              </div>
            </div>

            <!-- Learn More Link -->
            <div class="mt-auto flex justify-end">
              <NuxtLink
                :to="project.link"
                class="inline-flex items-center text-blue-600 font-semibold transition-colors duration-300 group-hover:text-white mb-2"
                :aria-label="'Learn more about ' + project.title"
              >
                <svg
                  class="w-5 h-5 mr-2 transition-transform duration-300 group-hover:translate-x-1 stroke-blue-600 group-hover:stroke-white"
                  fill="none"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M9 5l7 7-7 7"
                  />
                </svg>
                <span class="cursor-pointer relative">
                  Learn More
                  <span
                    class="absolute bottom-0 right-0 w-0 h-0.5 bg-white transition-all duration-500 group-hover:w-full"
                  ></span>
                </span>
              </NuxtLink>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
const projects = ref([
  {
    title: "Todo List",
    image: "/logo/logo.png",
    shortDescription: "A simple app to manage tasks and stay organized.",
    description:
      "A web-based todo list application built to practice state management and responsive design, allowing users to create, edit, and delete tasks with ease.",
    category: "Web App",
    bgColor: "#2e475d",
    link: "/pages/todolist",
  },
  {
    title: "Tic Tac Toe",
    image: "/logo/logo.png",
    shortDescription: "A classic two-player game with a modern UI.",
    description:
      "A web-based Tic Tac Toe game developed to practice JavaScript logic and CSS animations, featuring a clean interface and responsive design.",
    category: "Game",
    bgColor: "#2e475d",
    link: "/pages/tictactoe",
  },
  {
    title: "Rock Paper Scissors",
    image: "/logo/logo.png",
    shortDescription: "A fun game to test your luck and strategy.",
    description:
      "An interactive Rock Paper Scissors game built to enhance JavaScript skills, with animated transitions and a mobile-friendly layout.",
    category: "Game",
    bgColor: "#2e475d",
    link: "/pages/rockpaperscissors",
  },
  {
    title: "8-Ball",
    image: "/logo/logo.png",
    shortDescription: "A magic 8-ball app for fun predictions.",
    description:
      "A digital Magic 8-Ball application created to practice random response generation and playful UI design, with smooth animations.",
    category: "Web App",
    bgColor: "#2e475d",
    link: "/pages/8ball",
  },
  {
    title: "Cat Photo Gallery",
    image: "/logo/logo.png",
    shortDescription: "A gallery app to display cat photos.",
    description:
      "A photo gallery application showcasing cat images, built to practice API integration and grid layouts with Tailwind CSS.",
    category: "Web App",
    bgColor: "#2e475d",
    link: "/pages/catphoto",
  },
  {
    title: "Sticky Notes",
    image: "/logo/logo.png",
    shortDescription: "A digital sticky notes app for quick memos.",
    description:
      "A sticky notes application designed to practice drag-and-drop functionality and local storage, with a colorful and intuitive interface.",
    category: "Web App",
    bgColor: "#2e475d",
    link: "/pages/stickynotes",
  },
  {
    title: "Tattoo Shop Landing Page",
    image: "/logo/logo.png",
    shortDescription: "A stylish landing page for a tattoo shop.",
    description:
      "A responsive landing page for a tattoo shop, built to practice modern web design principles and Tailwind CSS for styling.",
    category: "Website",
    bgColor: "#2e475d",
    link: "/pages/tattooshop",
  },
  {
    title: "Quote Generator",
    image: "/logo/logo.png",
    shortDescription: "An app to generate inspirational quotes.",
    description:
      "A quote generator application that fetches random quotes via an API, designed to practice asynchronous JavaScript and UI design.",
    category: "Web App",
    bgColor: "#2e475d",
    link: "/pages/quotegenerator",
  },
  {
    title: "Pomodoro Timer",
    image: "/logo/logo.png",
    shortDescription: "A productivity timer for focused work sessions.",
    description:
      "A Pomodoro timer application built to practice JavaScript timers and state management, with a clean and distraction-free design.",
    category: "Web App",
    bgColor: "#2e475d",
    link: "/pages/pomodoro",
  },
  {
    title: "Expense Tracker",
    image: "/logo/logo.png",
    shortDescription: "An app to track personal expenses.",
    description:
      "A personal expense tracker built to practice data visualization and local storage, featuring charts and a user-friendly interface.",
    category: "Web App",
    bgColor: "#2e475d",
    link: "/pages/expensetracker",
  },
  {
    title: "Music Playlist App",
    image: "/logo/logo.png",
    shortDescription: "A web app to create and manage music playlists.",
    description:
      "A music playlist application designed to practice dynamic list rendering and API integration, with a sleek and modern UI.",
    category: "Web App",
    bgColor: "#2e475d",
    link: "/pages/musicplaylist",
  },
]);
</script>

<style>
/* Custom animation for card fade-in */
@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-fade-in {
  animation: fadeIn 0.6s ease-out forwards;
}
</style>
