<template>
  <div
    class="min-h-screen bg-gradient-to-br from-sky-950 via-sky-900 to-blue-800 text-gray-800 p-6 lg:p-12 font-[Georgia,serif] relative overflow-hidden"
  >
    <!-- Vignette Overlay -->
    <div
      class="absolute inset-0 bg-[radial-gradient(ellipse_at_center,rgba(255,255,255,0.15)_0%,rgba(0,0,0,0.5)_100%)]"
    ></div>
    <section class="relative z-10">
      <div class="container mx-auto px-4 max-w-screen-xl">
        <!-- Header -->
        <div class="text-center mb-16">
          <h2
            class="text-4xl font-extrabold mb-4 text-gray-100 drop-shadow-md animate-bounce-in"
          >
            My Projects
          </h2>
          <p class="text-lg text-gray-300 max-w-3xl mx-auto leading-relaxed">
            A selection of projects highlighting my work in web development and
            design.
          </p>
        </div>

        <!-- Projects Grid -->
        <div
          dir="ltr"
          class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-10 md:gap-16 justify-items-center bg-white/10 backdrop-blur-md rounded-lg p-8 shadow-[0_4px_30px_rgba(0,0,0,0.3)]"
        >
          <div
            v-for="(project, index) in projects"
            :key="index"
            class="flip-card relative animate-polaroid"
          >
            <!-- Polaroid Frame -->
            <div class="flip-card-inner">
              <!-- Front Face -->
              <div
                class="flip-card-front bg-white p-4 pb-10 rounded-md shadow-2xl border-2 border-gray-300"
              >
                <!-- Photo Area -->
                <div
                  class="w-[260px] h-[260px] flex items-center justify-center shadow-md bg-gradient-to-br from-gray-50 to-gray-100 mx-auto"
                >
                  <img
                    :src="project.image"
                    :alt="project.title"
                    class="object-contain w-full h-full rounded"
                  />
                </div>
                <!-- Name and Short Description -->
                <div class="mt-4 text-center space-y-2">
                  <h3
                    class="text-xl font-semibold text-gray-900 flex items-center justify-center"
                  >
                    {{ project.title }}
                    <!-- <span
                      class="ml-2 text-xs bg-blue-500 text-white px-2 py-1 rounded-full"
                    >
                      {{ project.category }}
                    </span> -->
                  </h3>
                  <p class="text-base text-gray-700 font-medium">
                    {{ project.shortDescription }}
                  </p>
                </div>
              </div>

              <!-- Back Face -->
              <div
                class="flip-card-back bg-gradient-to-br from-gray-100 to-slate-200 text-slate-800 rounded-lg p-6 flex flex-col justify-center items-center"
              >
                <!-- <h3 class="text-xl font-bold mb-2">
                  {{ project.title }}
                </h3> -->
                <p
                  class="text-base mb-4 text-center"
                  v-html="project.description"
                ></p>
                <!-- <ul class="text-sm space-y-1 mb-4 text-center">
                  <li v-for="feature in project.features" :key="feature.label">
                    <span class="font-semibold">{{ feature.label }}:</span>
                    {{ feature.value }}
                  </li>
                </ul> -->
                <NuxtLink
                  :to="project.link"
                  class="inline-flex items-center text-slate-800 font-semibold bg-pink-300 hover:bg-pink-400 px-6 py-2 rounded-full transition-all duration-300 hover:shadow-[0_0_10px_rgba(255,255,255,0.5)]"
                  :aria-label="'View project ' + project.title"
                >
                  View Project
                  <svg
                    class="w-5 h-5 ml-2 transition-transform duration-300 group-hover:translate-x-1"
                    fill="none"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke="currentColor"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M9 5l7 7-7 7"
                    />
                  </svg>
                </NuxtLink>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
import { ref } from "vue";

// Project data
const projects = ref([
  {
    title: "Todo List",
    image: "/images/todolist.png",
    shortDescription: "A sleek app to manage tasks and boost productivity.",
    description:
      "A web-based <strong>todo list</strong> application built to practice state management and responsive design, allowing users to create, edit, and delete tasks with ease.",
    category: "Web App",
    link: "/pages/todolist",
  },
  {
    title: "Tic Tac Toe",
    image: "/images/tictactoe.png",
    shortDescription: "A fun two-player game with a vibrant UI.",
    description:
      "A web-based <strong>Tic Tac Toe</strong> game developed to practice JavaScript logic and CSS animations, featuring a clean interface and responsive design.",
    category: "Game",
    link: "/pages/tictactoe",
  },
  {
    title: "Rock Paper Scissors",
    image: "/images/rps.png",
    shortDescription: "A playful game to test luck and strategy.",
    description:
      "An <strong>interactive Rock Paper Scissors game</strong> built to enhance JavaScript skills, with animated transitions and a mobile-friendly layout.",
    category: "Game",
    link: "/pages/rockpaperscissors",
  },
  {
    title: "8-Ball",
    image: "/images/8ball.png",
    shortDescription: "A magic 8-ball for fun predictions.",
    description:
      "A <strong>digital Magic 8-Ball</strong> application created to practice random response generation and playful UI design, with smooth animations.",
    category: "Web App",
    link: "/pages/8ball",
  },
  {
    title: "Cat Photo Gallery",
    image: "/images/cat.png",
    shortDescription: "A gallery showcasing adorable cat photos.",
    description:
      "A <strong>photo gallery</strong> application showcasing cat images, built to practice API integration and grid layouts with Tailwind CSS.",
    category: "Web App",
    link: "/pages/catphoto",
  },
  {
    title: "Sticky Notes",
    image: "/images/stickynotes.png",
    shortDescription: "A colorful app for quick memos.",
    description:
      "A <strong>sticky notes</strong> application designed to practice drag-and-drop functionality and local storage, with a vibrant and intuitive interface.",
    category: "Web App",
    link: "/pages/stickynotes",
  },
  {
    title: "Tattoo Shop website",
    image: "/images/shop-website.png",
    shortDescription: "A bold landing page for a tattoo shop.",
    description:
      "A <strong>responsive landing page</strong> for a tattoo shop, built to practice modern web design principles and Tailwind CSS for styling.",
    category: "Website",
    link: "/pages/tattooshop",
  },
  {
    title: "Quote Generator",
    image: "/images/quote.png",
    shortDescription: "Inspirational quotes at your fingertips.",
    description:
      "A <strong>quote generator</strong> application that fetches random quotes via an API, designed to practice asynchronous JavaScript and UI design.",
    category: "Web App",
    link: "/pages/quotegenerator",
  },
  {
    title: "Pomodoro Timer",
    image: "/images/promodo-timer.png",
    shortDescription: "A timer for focused work sessions.",
    description:
      "A <strong>Pomodoro timer</strong> application built to practice JavaScript timers and state management, with a clean and distraction-free design.",
    category: "Web App",
    link: "/pages/pomodoro",
  },
  {
    title: "Expense Tracker",
    image: "/images/piggy-bank.png",
    shortDescription: "Track your expenses with ease.",
    description:
      "A personal <strong>expense tracker</strong> built to practice data visualization and local storage, featuring charts and a user-friendly interface.",
    category: "Web App",
    link: "/pages/expensetracker",
  },
  {
    title: "Music Playlist App",
    image: "/images/music-playlist-app.png",
    shortDescription: "Create and manage music playlists.",
    description:
      "A <strong>music playlist</strong> application designed to practice dynamic list rendering and API integration, with a sleek and modern UI.",
    category: "Web App",
    link: "/pages/musicplaylist",
  },
]);
</script>

<style scoped>
/* Font import */
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;800&display=swap");

.font-poppins {
  font-family: "Poppins", sans-serif;
}

/* Flip card styles */
.flip-card {
  background-color: transparent;
  width: 300px;
  height: 400px;
  perspective: 1000px;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front,
.flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-card-front {
  background-color: #fff;
}

.flip-card-back {
  background-color: transparent;
  transform: rotateY(180deg);
}

/* .flip-card-back p strong {
  font-weight: 700;
    color: inherit;
} */

/* Polaroid animation */
@keyframes polaroidFade {
  0% {
    opacity: 0;
    transform: translateY(30px) scale(0.9);
  }
  100% {
    opacity: 1;
    transform: translateY(0) scale(1);
  }
}

.animate-polaroid {
  animation: polaroidFade 0.8s ease-out forwards;
}

/* Title animation */
@keyframes bounceIn {
  0% {
    opacity: 0;
    transform: scale(0.8);
  }
  50% {
    transform: scale(1.05);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}

.animate-bounce-in {
  animation: bounceIn 1s ease-out;
}

/* Custom cursor */
.flip-card:hover {
  cursor: pointer;
}
</style>