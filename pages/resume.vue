<template>
  <div
    class="min-h-screen bg-gradient-to-br from-sky-950 via-sky-900 to-sky-800 text-gray-100 p-6 lg:p-10 font-[Inter,sans-serif]"
  >
    <div class="max-w-3xl mx-auto">
      <!-- Header -->
      <header class="text-left mb-12 animate-fade-in">
        <div class="flex items-center gap-4 mb-4">
          <div
            class="w-16 h-16 bg-sky-500 rounded-full flex items-center justify-center shadow-lg animate-pulse-slow"
          >
            <svg
              class="w-8 h-8 text-white"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                fill-rule="evenodd"
                d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
          <div>
            <h1 class="text-4xl font-bold text-sky-100 tracking-tight shadow-sm">
              Jane Doe
            </h1>
            <p class="text-xl text-sky-300 font-medium">Junior Front-End Developer | Aspiring UI/UX Designer</p>
          </div>
        </div>
        <div
          class="flex flex-wrap gap-3 mt-4 text-sm text-sky-200"
        >
          <span>📧 jane.doe@email.com</span>
          <span>📱 +00 000 000 000</span>
          <span>💼 linkedin.com/in/janedoe</span>
          <span>💻 github.com/janedoe</span>
          <span>🌐 janedoe.design</span>
          <span>City, Country</span>
          <span
            class="ml-auto"
          >
            <img
              src="https://api.qrserver.com/v1/create-qr-code/?size=50x50&data=https://janedoe.design"
              alt="Portfolio QR Code"
              class="inline-block"
            />
          </span>
        </div>
      </header>

      <!-- About Me -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-sky-100 border-b border-gradient pb-2 mb-4 relative"
        >
          About Me
        </h2>
        <p
          class="text-sky-200 leading-loose text-base"
        >
          I’m a creative problem-solver who believes good design should serve people. I enjoy collaborating with others to develop ideas and crafting thoughtful solutions that make everyday tasks simpler and more enjoyable. With patience, curiosity, and attention to detail, I’m focused on deepening my understanding of UI/UX design and creating user experiences that are both practical and visually engaging.
        </p>
      </section>

      <!-- Experience -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-sky-100 border-b border-gradient pb-2 mb-4 relative"
        >
          Experience
        </h2>
        <div class="space-y-8">
          <div
            class="p-4 bg-sky-900/20 rounded-lg shadow-md hover:shadow-xl hover:scale-102 transition-all duration-300"
          >
            <h3 class="text-xl font-medium text-sky-100">
              Front-End Developer & Documentation Assistant
            </h3>
            <p class="text-sky-300">XYZ Company | Aug 2024 – Oct 2025</p>
            <ul
              class="list-disc list-inside text-sky-200 mt-2 space-y-2"
            >
              <li>Developed a strong understanding of documentation’s role in the software development lifecycle.</li>
              <li>Collaborated with cross-functional teams to meet goals efficiently and on time.</li>
              <li>Designed responsive landing pages with a focus on user experience and visual consistency.</li>
              <li>Contributed to a large-scale surveillance software project’s front-end.</li>
              <li>Built cashier and accounting sections for an unreleased store management system.</li>
              <li>Managed two key sections in the latest internal project.</li>
              <li>Participated in UI/UX discussions to enhance design quality.</li>
              <li>Used Git and project tools for version control and task tracking.</li>
            </ul>
          </div>
          <div
            class="p-4 bg-sky-900/20 rounded-lg shadow-md hover:shadow-xl hover:scale-102 transition-all duration-300"
          >
            <h3 class="text-xl font-medium text-sky-100">
              English Teacher
            </h3>
            <p class="text-sky-300">XYZ Language Center | 2022 – Present (intermittent)</p>
            <ul
              class="list-disc list-inside text-sky-200 mt-2 space-y-2"
            >
              <li>Adapted teaching methods for diverse ages and learning styles.</li>
              <li>Enhanced communication skills with diverse learners.</li>
              <li>Developed confidence through one-on-one and group instruction.</li>
              <li>Improved planning with customized lesson plans.</li>
            </ul>
          </div>
        </div>
      </section>

      <!-- Education -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-sky-100 border-b border-gradient pb-2 mb-4 relative"
        >
          Education
        </h2>
        <div>
          <h3 class="text-xl font-medium text-sky-100">
            Bachelor’s Degree in Computer Engineering
          </h3>
          <p class="text-sky-300">XYZ University</p>
          <p class="text-sky-200 mt-1">Math and Physics Diploma</p>
        </div>
      </section>

      <!-- Skills & UI/UX Aspirations -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-sky-100 border-b border-gradient pb-2 mb-4 relative"
        >
          Skills & UI/UX Aspirations
        </h2>
        <div
          class="grid grid-cols-2 lg:grid-cols-4 gap-3 text-sky-200 text-sm"
        >
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">HTML</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">CSS</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">JavaScript</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Nuxt.js</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Vuetify</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Tailwind CSS</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">UI/UX Design (learning)</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Git (basic)</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Responsive Design (basic)</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Teamwork</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Creativity</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Problem-Solving</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Adaptability</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Willingness to Learn</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Time Management</span>
        </div>
        <p class="text-sky-200 mt-4 text-sm">
          Actively exploring UI/UX design tools (e.g., Figma) and principles to complement my front-end skills, with a goal to design intuitive interfaces.
        </p>
      </section>

      <!-- Projects -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-sky-100 border-b border-gradient pb-2 mb-4 relative"
        >
          Projects
        </h2>
        <div class="space-y-6">
          <div
            class="p-4 bg-sky-900/20 rounded-lg shadow-md hover:shadow-xl hover:scale-102 transition-all duration-300"
          >
            <h3 class="text-xl font-medium text-sky-100">
              Crochet Management System
            </h3>
            <p class="text-sky-200">
              A web app for crocheters to track inventory, patterns, and projects. Evolved from Nuxt and CSS to Nuxt with Vuetify, now using Tailwind. Includes mindmaps and use case diagrams. Inspired by personal crocheting needs.
            </p>
          </div>
          <div
            class="p-4 bg-sky-900/20 rounded-lg shadow-md hover:shadow-xl hover:scale-102 transition-all duration-300"
          >
            <h3 class="text-xl font-medium text-sky-100">
              Mini Front-End Projects
            </h3>
            <p class="text-sky-200">
              Tic Tac Toe, Rock Paper Scissors, To-Do List, and First Portfolio Website. Built with HTML, CSS, and JS to master web fundamentals and responsive design.
            </p>
          </div>
        </div>
      </section>

      <!-- Languages -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-sky-100 border-b border-gradient pb-2 mb-4 relative"
        >
          Languages
        </h2>
        <div
          class="grid grid-cols-2 lg:grid-cols-3 gap-3 text-sky-200 text-sm"
        >
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Armenian</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">Persian</span>
          <span class="px-3 py-1 bg-sky-900/50 rounded-full">English</span>
        </div>
      </section>

      <!-- References -->
      <section>
        <h2
          class="text-2xl font-semibold text-sky-100 border-b border-gradient pb-2 mb-4 relative"
        >
          References
        </h2>
        <p class="text-sky-200">Available upon request.</p>
      </section>

      <!-- Back Button -->
      <div class="mt-10 text-center">
        <NuxtLink
          to="/"
          class="inline-block bg-sky-400 text-white font-semibold py-3 px-8 rounded-lg shadow-lg hover:bg-sky-500 hover:shadow-[0_0_15px_5px_rgba(255,255,255,0.5),0_0_25px_10px_rgba(125,211,252,0.3)] transition-all duration-300 focus:outline-none"
        >
          Back to Portfolio
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import { useRoute } from "vue-router";

const route = useRoute();
</script>

<style scoped>
/* Font import (optional, ensure Inter is available or fallback to system fonts) */
@font-face {
  font-family: "Inter";
  src: url("https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap") format("woff2");
}

.animate-fade-in {
  animation: fadeIn 0.5s ease-in;
}

.animate-pulse-slow {
  animation: pulse 2s infinite ease-in-out;
}

.border-gradient {
  position: relative;
}
.border-gradient::after {
  content: "";
  position: absolute;
  bottom: -2px;
  left: 0;
  width: 100%;
  height: 2px;
  background: linear-gradient(to right, transparent, #93c5fd, transparent);
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(10px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes pulse {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.05); }
}

@media print {
  .bg-gradient-to-br,
  .animate-fade-in,
  .animate-pulse-slow,
  .hover\:shadow-\[.*\],
  .hover\:scale-\[.*\],
  .hover\:opacity-\[.*\],
  .mt-10,
  a {
    display: none !important;
  }
  body {
    background: white !important;
    color: black !important;
  }
  .max-w-3xl {
    max-width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }
  h1, h2, h3, p, ul, li {
    color: black !important;
  }
  .border-gradient {
    border-bottom: 2px solid #93c5fd !important;
  }
}
</style>