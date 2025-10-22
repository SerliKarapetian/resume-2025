<template>
  <div
    class="min-h-screen bg-gradient-to-br from-sky-950 via-sky-900 to-sky-800 text-gray-800 p-6 lg:p-10 font-[Georgia,serif]"
  >
    <div class="max-w-4xl mx-auto border-2 border-gray-200 rounded-lg p-6 bg-white shadow-lg">
      <!-- Header -->
      <header class="text-left mb-12">
        <div class="flex items-center gap-4 mb-4">
          <div
            class="w-16 h-16 bg-sky-500 rounded-full flex items-center justify-center"
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
            <h1 class="text-4xl font-semibold text-gray-900 tracking-tight">
              Jane Doe
            </h1>
            <p class="text-xl text-gray-600 font-medium">Junior Front-End Developer | Aspiring UI/UX Designer</p>
          </div>
        </div>
        <div
          class="flex flex-wrap gap-3 mt-4 text-sm text-gray-600"
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
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-2 mb-4"
        >
          About Me
        </h2>
        <p
          class="text-gray-700 leading-relaxed text-base"
        >
          I’m a creative problem-solver who believes good design should serve people. I enjoy collaborating with others to develop ideas and crafting thoughtful solutions that make everyday tasks simpler and more enjoyable. With patience, curiosity, and attention to detail, I’m focused on deepening my understanding of UI/UX design and creating user experiences that are both practical and visually engaging.
        </p>
      </section>

      <!-- Experience -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-2 mb-4"
        >
          Experience
        </h2>
        <div class="space-y-8">
          <div
            class="p-4 bg-gray-50 rounded-lg shadow-sm"
          >
            <h3 class="text-xl font-medium text-gray-900">
              Front-End Developer & Documentation Assistant
            </h3>
            <p class="text-gray-600">XYZ Company | Aug 2024 – Oct 2025</p>
            <ul
              class="list-disc list-inside text-gray-700 mt-2 space-y-2"
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
            class="p-4 bg-gray-50 rounded-lg shadow-sm"
          >
            <h3 class="text-xl font-medium text-gray-900">
              English Teacher
            </h3>
            <p class="text-gray-600">XYZ Language Center | 2022 – Present (intermittent)</p>
            <ul
              class="list-disc list-inside text-gray-700 mt-2 space-y-2"
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
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-2 mb-4"
        >
          Education
        </h2>
        <div>
          <h3 class="text-xl font-medium text-gray-900">
            Bachelor’s Degree in Computer Engineering
          </h3>
          <p class="text-gray-600">XYZ University | 2018 – 2022</p>
          <p class="text-gray-700 mt-1">Math and Physics Diploma</p>
          <p class="text-gray-600 mt-1">High School | 2014 – 2018</p>
        </div>
      </section>

      <!-- Skills & UI/UX Aspirations -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-2 mb-4"
        >
          Skills & UI/UX Aspirations
        </h2>
        <div class="flex flex-col lg:flex-row gap-6">
          <!-- Hard Skills -->
          <div class="w-full lg:w-1/2">
            <h3 class="text-lg font-semibold text-gray-900 mb-3">Technical Skills</h3>
            <div class="space-y-3">
              <div>
                <div class="flex justify-between mb-1 text-sm">
                  <span class="text-gray-700">HTML</span>
                  <span class="text-gray-900 font-medium">50%</span>
                </div>
                <div class="progress-bar h-2 bg-gray-300 rounded-full overflow-hidden">
                  <div class="progress-fill h-full bg-gradient-to-r from-sky-600 to-sky-700" style="width: 50%;"></div>
                </div>
              </div>
              <div>
                <div class="flex justify-between mb-1 text-sm">
                  <span class="text-gray-700">CSS & Tailwind CSS</span>
                  <span class="text-gray-900 font-medium">50%</span>
                </div>
                <div class="progress-bar h-2 bg-gray-300 rounded-full overflow-hidden">
                  <div class="progress-fill h-full bg-gradient-to-r from-sky-600 to-sky-700" style="width: 50%;"></div>
                </div>
              </div>
              <div>
                <div class="flex justify-between mb-1 text-sm">
                  <span class="text-gray-700">JavaScript & Nuxt.js</span>
                  <span class="text-gray-900 font-medium">40%</span>
                </div>
                <div class="progress-bar h-2 bg-gray-300 rounded-full overflow-hidden">
                  <div class="progress-fill h-full bg-gradient-to-r from-sky-600 to-sky-700" style="width: 40%;"></div>
                </div>
              </div>
              <div>
                <div class="flex justify-between mb-1 text-sm">
                  <span class="text-gray-700">Vuetify</span>
                  <span class="text-gray-900 font-medium">30%</span>
                </div>
                <div class="progress-bar h-2 bg-gray-300 rounded-full overflow-hidden">
                  <div class="progress-fill h-full bg-gradient-to-r from-sky-600 to-sky-700" style="width: 30%;"></div>
                </div>
              </div>
              <div>
                <div class="flex justify-between mb-1 text-sm">
                  <span class="text-gray-700">UI/UX Design (Learning)</span>
                  <span class="text-gray-900 font-medium">20%</span>
                </div>
                <div class="progress-bar h-2 bg-gray-300 rounded-full overflow-hidden">
                  <div class="progress-fill h-full bg-gradient-to-r from-sky-600 to-sky-700" style="width: 20%;"></div>
                </div>
              </div>
            </div>
          </div>
          <!-- Soft Skills -->
          <div class="w-full lg:w-1/2">
            <h3 class="text-lg font-semibold text-gray-900 mb-3">Soft Skills</h3>
            <div class="grid grid-cols-2 gap-2">
              <span class="px-2 py-1 bg-sky-200 text-sky-800 rounded-lg text-center border border-sky-400 text-sm">Teamwork</span>
              <span class="px-2 py-1 bg-sky-200 text-sky-800 rounded-lg text-center border border-sky-400 text-sm">Creativity</span>
              <span class="px-2 py-1 bg-sky-200 text-sky-800 rounded-lg text-center border border-sky-400 text-sm">Problem-solving</span>
              <span class="px-2 py-1 bg-sky-200 text-sky-800 rounded-lg text-center border border-sky-400 text-sm">Adaptability</span>
              <span class="px-2 py-1 bg-sky-200 text-sky-800 rounded-lg text-center border border-sky-400 text-sm">Willingness to Learn</span>
              <span class="px-2 py-1 bg-sky-200 text-sky-800 rounded-lg text-center border border-sky-400 text-sm">Time Management</span>
              <span class="px-2 py-1 bg-sky-200 text-sky-800 rounded-lg text-center border border-sky-400 text-sm col-span-2">Multilingual (Armenian, Persian, English)</span>
            </div>
          </div>
        </div>
        <!-- UI/UX Aspirations -->
        <p class="text-gray-700 mt-4 text-sm">
          Actively exploring UI/UX design tools (e.g., Figma) and principles to complement my front-end skills, with a goal to design intuitive interfaces.
        </p>
      </section>

      <!-- Projects -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-2 mb-4"
        >
          Projects
        </h2>
        <div class="space-y-6">
          <div
            class="p-4 bg-gray-50 rounded-lg shadow-sm"
          >
            <h3 class="text-xl font-medium text-gray-900">
              Crochet Management System
            </h3>
            <p class="text-gray-700">
              A web app for crocheters to track inventory, patterns, and projects. Evolved from Nuxt and CSS to Nuxt with Vuetify, now using Tailwind. Includes mindmaps and use case diagrams. Inspired by personal crocheting needs.
            </p>
          </div>
          <div
            class="p-4 bg-gray-50 rounded-lg shadow-sm"
          >
            <h3 class="text-xl font-medium text-gray-900">
              Mini Front-End Projects
            </h3>
            <p class="text-gray-700">
              Tic Tac Toe, Rock Paper Scissors, To-Do List, and First Portfolio Website. Built with HTML, CSS, and JS to master web fundamentals and responsive design.
            </p>
          </div>
        </div>
      </section>

      <!-- Languages -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-2 mb-4"
        >
          Languages
        </h2>
        <div
          class="grid grid-cols-2 lg:grid-cols-3 gap-3 text-gray-700 text-sm"
        >
          <span class="px-3 py-1 bg-gray-200 rounded-full">Armenian</span>
          <span class="px-3 py-1 bg-gray-200 rounded-full">Persian</span>
          <span class="px-3 py-1 bg-gray-200 rounded-full">English</span>
        </div>
      </section>

      <!-- Back Button -->
      <div class="mt-10 text-center">
        <NuxtLink
          to="/"
          class="inline-block bg-sky-500 text-white font-semibold py-3 px-8 rounded-lg shadow-md focus:outline-none"
        >
          Back to HomePage
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
/* Font import (optional, ensure Georgia is available or fallback to serif) */
@font-face {
  font-family: "Georgia";
  src: local("Georgia"), url("https://fonts.cdnfonts.com/s/17370/Georgia.woff") format("woff");
}

/* Progress Bar Styles */
.progress-bar {
  height: 10px;
  border-radius: 5px;
  background-color: #e5e7eb;
  overflow: hidden;
  border: 1px solid #d1d5db;
}

.progress-fill {
  height: 100%;
  border-radius: 5px;
  background: linear-gradient(to right, #0284c7, #075985);
}

/* Print styles */
@media print {
  .bg-white,
  .border-2,
  .shadow-lg,
  .mt-10,
  a {
    display: block !important;
    border: none !important;
    box-shadow: none !important;
    margin: 0 !important;
  }
  body {
    background: white !important;
    color: black !important;
  }
  .max-w-4xl {
    max-width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }
  h1, h2, h3, p, ul, li {
    color: black !important;
  }
  .border-b-2 {
    border-bottom: 2px solid #e5e7eb !important;
  }
  .progress-bar,
  .progress-fill {
    display: none !important;
  }
}
</style>