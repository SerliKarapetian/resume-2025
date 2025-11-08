<template>
  <div
    class="min-h-screen bg-gradient-to-br from-sky-950 via-sky-900 to-sky-800 text-gray-800 p-6 lg:p-10 font-[Georgia,serif]"
  >
    <div
      class="max-w-4xl mx-auto border border-gray-300 rounded-xl p-8 bg-white shadow-sm hover:shadow-md transition-shadow duration-300"
    >
      <!-- Header -->
      <header class="text-left mb-12">
        <div
          class="flex flex-col sm:flex-row items-start sm:items-center gap-6 mb-6"
        >
          <div class="flex items-center gap-4 flex-1">
            <div
              class="w-20 h-20 bg-gradient-to-br from-sky-500 to-blue-600 rounded-full flex items-center justify-center shadow-md hover:shadow-lg transition-shadow duration-300"
            >
              <svg
                class="w-10 h-10 text-white"
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
            <div class="flex-1">
              <h1
                class="text-3xl sm:text-4xl font-semibold text-gray-900 tracking-tight leading-tight"
              >
                Serli Gharapetian
              </h1>
              <p class="text-base sm:text-lg font-medium text-gray-600 mt-1">
                Junior Front-End Developer | Aspiring UI/UX Designer
              </p>
            </div>
          </div>
          <div class="flex-shrink-0">
            <img
              src="https://api.qrserver.com/v1/create-qr-code/?size=80x80&data=https://janedoe.design&margin=0"
              alt="Resume QR Code"
              class="shadow-sm"
              title="Scan to visit my resume on your phone"
            />
          </div>
        </div>
        <!-- Contact Info - Improved Layout -->
        <div
          class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-1 text-sm text-gray-600"
        >
          <a
            href="mailto:jane.doe@email.com"
            class="flex items-center gap-2 p-2 transition-colors duration-200 group"
            ><span
              class="w-6 h-6 flex items-center justify-center text-sky-600 transition-colors duration-200"
              ><svg
                class="w-5 h-5"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                /></svg></span
            ><span
              class="group-hover:text-sky-700 transition-colors duration-200"
              >serligharapetianwork@email.com</span
            ></a
          >
          <div class="flex items-center gap-2 p-2">
            <span class="w-6 h-6 flex items-center justify-center text-sky-600"
              ><svg
                class="w-5 h-5"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
                /></svg></span
            ><span>+00 000 000 000</span>
          </div>
          <a
            href="#"
            class="flex items-center gap-2 p-2 transition-colors duration-200 group"
            ><span
              class="w-6 h-6 flex items-center justify-center text-sky-600 transition-colors duration-200"
              ><svg
                class="w-5 h-5"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                /></svg></span
            ><span
              class="group-hover:text-sky-700 transition-colors duration-200"
              >linkedin.com/in/janedoe</span
            ></a
          >
          <a
            href="#"
            class="flex items-center gap-2 p-2 transition-colors duration-200 group"
            ><span
              class="w-6 h-6 flex items-center justify-center text-sky-600 transition-colors duration-200"
              ><svg
                class="w-5 h-5"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"
                /></svg></span
            ><span
              class="group-hover:text-sky-700 transition-colors duration-200"
              >github.com/SerliKarapetian</span
            ></a
          >
          <a
            href="#"
            class="flex items-center gap-2 p-2 transition-colors duration-200 group"
            ><span
              class="w-6 h-6 flex items-center justify-center text-sky-600 transition-colors duration-200"
              ><svg
                class="w-5 h-5"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                /></svg></span
            ><span
              class="group-hover:text-sky-700 transition-colors duration-200"
              >serligharapetian.ir</span
            ></a
          >
          <div class="flex items-center gap-2 p-2">
            <span class="w-6 h-6 flex items-center justify-center text-sky-600"
              ><svg
                class="w-5 h-5"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"
                /></svg></span
            ><span>Tehran, Iran</span>
          </div>
        </div>
      </header>

      <!-- About Me -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-3 mb-6"
        >
          About Me
        </h2>
        <p class="text-base text-gray-700 leading-relaxed text-justify">
          I'm a creative problem-solver who believes good design should serve
          people. I enjoy collaborating with others to develop ideas and
          crafting thoughtful solutions that make everyday tasks simpler and
          more enjoyable. With patience, curiosity, and attention to detail, I'm
          focused on deepening my understanding of UI/UX design and creating
          user experiences that are both practical and visually engaging.
        </p>
      </section>

      <!-- Experience -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-3 mb-6"
        >
          Experience
        </h2>
        <div class="space-y-2">
          <div class="p-1">
            <h3 class="text-xl font-medium text-gray-900">
              Front-End Developer & Documentation Assistant
            </h3>
            <p class="text-base text-gray-600">
              XYZ Company | Aug 2024 – Oct 2025
            </p>
            <ul
              class="list-disc list-inside text-base text-gray-700 mt-2 space-y-2"
            >
              <li>
                Developed a strong understanding of documentation’s role in the
                software development lifecycle.
              </li>
              <li>
                Collaborated with cross-functional teams to meet goals
                efficiently and on time.
              </li>
              <li>
                Designed responsive landing pages with a focus on user
                experience and visual consistency.
              </li>
              <li>
                Contributed to a large-scale surveillance software project’s
                front-end.
              </li>
              <li>
                Built cashier and accounting sections for an unreleased store
                management system.
              </li>
              <li>Managed two key sections in the latest internal project.</li>
              <li>
                Participated in UI/UX discussions to enhance design quality.
              </li>
              <li>
                Used Git and project tools for version control and task
                tracking.
              </li>
            </ul>
          </div>
          <div class="p-1">
            <h3 class="text-xl font-medium text-gray-900">English Teacher</h3>
            <p class="text-base text-gray-600">
              XYZ Language Center | 2022 – Present (intermittent)
            </p>
            <ul
              class="list-disc list-inside text-base text-gray-700 mt-2 space-y-2"
            >
              <li>
                Adapted teaching methods for diverse ages and learning styles.
              </li>
              <li>Enhanced communication skills with diverse learners.</li>
              <li>
                Developed confidence through one-on-one and group instruction.
              </li>
              <li>Improved planning with customized lesson plans.</li>
            </ul>
          </div>
        </div>
      </section>

      <!-- Education -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-3 mb-6"
        >
          Education
        </h2>
        <div>
          <h3 class="text-xl font-medium text-gray-900">
            Bachelor’s Degree in Computer Engineering
          </h3>
          <p class="text-base text-gray-600">XYZ University | 2021 – 2025</p>
          <!-- <h3 class="text-xl font-medium text-gray-900">
            Math and Physics Diploma
          </h3>
          <p class="text-base text-gray-600 mt-1">High School | 2014 – 2018</p> -->
        </div>
      </section>

      <!-- Skills & UI/UX Aspirations -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-3 mb-6"
        >
          Skills & UI/UX Aspirations
        </h2>
        <div class="flex flex-col lg:flex-row gap-8">
          <!-- Hard Skills -->
          <div class="w-full lg:w-1/2">
            <h3
              class="text-xl font-medium text-gray-900 mb-4 flex items-center gap-2"
            >
              Technical Skills
            </h3>
            <div class="space-y-4">
              <div class="skill-item">
                <div class="flex justify-between mb-2 text-sm">
                  <span class="text-gray-700 font-medium">HTML</span
                  ><span class="text-sky-700 font-semibold">50%</span>
                </div>
                <div class="progress-bar">
                  <div class="progress-fill" style="width: 50%"></div>
                </div>
              </div>
              <div class="skill-item">
                <div class="flex justify-between mb-2 text-sm">
                  <span class="text-gray-700 font-medium"
                    >CSS & Tailwind CSS</span
                  ><span class="text-sky-700 font-semibold">50%</span>
                </div>
                <div class="progress-bar">
                  <div class="progress-fill" style="width: 50%"></div>
                </div>
              </div>
              <div class="skill-item">
                <div class="flex justify-between mb-2 text-sm">
                  <span class="text-gray-700 font-medium"
                    >JavaScript & Nuxt.js</span
                  ><span class="text-sky-700 font-semibold">40%</span>
                </div>
                <div class="progress-bar">
                  <div class="progress-fill" style="width: 40%"></div>
                </div>
              </div>
              <div class="skill-item">
                <div class="flex justify-between mb-2 text-sm">
                  <span class="text-gray-700 font-medium">Vuetify</span
                  ><span class="text-sky-700 font-semibold">30%</span>
                </div>
                <div class="progress-bar">
                  <div class="progress-fill" style="width: 30%"></div>
                </div>
              </div>
              <div class="skill-item">
                <div class="flex justify-between mb-2 text-sm">
                  <span class="text-gray-700 font-medium"
                    >UI/UX Design (Learning)</span
                  ><span class="text-sky-700 font-semibold">20%</span>
                </div>
                <div class="progress-bar">
                  <div class="progress-fill" style="width: 20%"></div>
                </div>
              </div>
            </div>
          </div>
          <!-- Soft Skills -->
          <div class="w-full lg:w-1/2">
            <h3
              class="text-xl font-medium text-gray-900 mb-4 flex items-center gap-2"
            >
              Soft Skills
            </h3>
            <div class="grid grid-cols-2 gap-3">
              <span
                class="px-3 py-2 bg-gradient-to-r from-sky-100 to-blue-100 text-sky-800 rounded-lg text-center border border-sky-200 text-sm font-medium hover:shadow-sm transition-shadow duration-200"
                >Teamwork</span
              >
              <span
                class="px-3 py-2 bg-gradient-to-r from-sky-100 to-blue-100 text-sky-800 rounded-lg text-center border border-sky-200 text-sm font-medium hover:shadow-sm transition-shadow duration-200"
                >Creativity</span
              >
              <span
                class="px-3 py-2 bg-gradient-to-r from-sky-100 to-blue-100 text-sky-800 rounded-lg text-center border border-sky-200 text-sm font-medium hover:shadow-sm transition-shadow duration-200"
                >Problem-solving</span
              >
              <span
                class="px-3 py-2 bg-gradient-to-r from-sky-100 to-blue-100 text-sky-800 rounded-lg text-center border border-sky-200 text-sm font-medium hover:shadow-sm transition-shadow duration-200"
                >Adaptability</span
              >
              <span
                class="px-3 py-2 bg-gradient-to-r from-sky-100 to-blue-100 text-sky-800 rounded-lg text-center border border-sky-200 text-sm font-medium hover:shadow-sm transition-shadow duration-200"
                >Willingness to Learn</span
              >
              <span
                class="px-3 py-2 bg-gradient-to-r from-sky-100 to-blue-100 text-sky-800 rounded-lg text-center border border-sky-200 text-sm font-medium hover:shadow-sm transition-shadow duration-200"
                >Time Management</span
              >
              <span
                class="px-3 py-2 bg-gradient-to-r from-sky-100 to-blue-100 text-sky-800 rounded-lg text-center border border-sky-200 text-sm font-medium hover:shadow-sm transition-shadow duration-200 col-span-2"
                >Multilingual Communication</span
              >
            </div>
          </div>
        </div>
        <!-- UI/UX Aspirations -->
        <div
          class="mt-6 p-4 bg-gradient-to-r from-sky-50 to-blue-50 rounded-xl border border-sky-100"
        >
          <p class="text-base text-gray-700 leading-relaxed italic">
            🎯 <strong class="font-medium">UI/UX Aspiration:</strong> Actively
            exploring UI/UX design tools (Figma, Adobe XD) and principles to
            complement my front-end skills, with a goal to design intuitive,
            accessible, and user-centered interfaces.
          </p>
        </div>
      </section>

      <!-- Languages -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-3 mb-6"
        >
          Languages
        </h2>
        <div class="flex flex-wrap gap-4">
          <span
            class="px-4 py-2 bg-gradient-to-r from-sky-100 to-blue-100 text-sky-800 rounded-full text-sm font-medium border border-sky-200 hover:shadow-sm transition-shadow duration-200"
            >Armenian (Native)</span
          >
          <span
            class="px-4 py-2 bg-gradient-to-r from-sky-100 to-blue-100 text-sky-800 rounded-full text-sm font-medium border border-sky-200 hover:shadow-sm transition-shadow duration-200"
            >Persian (Fluent)</span
          >
          <span
            class="px-4 py-2 bg-gradient-to-r from-sky-100 to-blue-100 text-sky-800 rounded-full text-sm font-medium border border-sky-200 hover:shadow-sm transition-shadow duration-200"
            >English (Professional)</span
          >
        </div>
      </section>

      <!-- Projects -->
      <section class="mb-10">
        <h2
          class="text-2xl font-semibold text-gray-900 border-b-2 border-gray-300 pb-3 mb-6"
        >
          Projects
        </h2>
        <div class="space-y-2">
          <div class="p-1">
            <h3 class="text-xl font-medium text-gray-900">
              Tailwind & Design Exploration
            </h3>
            <p class="text-base text-gray-700">
              Designed and developed responsive landing pages for various small
              projects at the company using Tailwind CSS, improved presentation
              and design consistency across platforms.
            </p>
          </div>
          <div class="p-1">
            <h3 class="text-xl font-medium text-gray-900">
              Crochet Management System
            </h3>
            <p class="text-base text-gray-700">
              A web app for crocheters to track inventory, patterns, and
              projects. Evolved from Nuxt and CSS to Nuxt with Vuetify, now
              using Tailwind. Includes mindmaps and use case diagrams. Inspired
              by personal crocheting needs.
            </p>
          </div>
          <div class="p-1">
            <h3 class="text-xl font-medium text-gray-900">
              Mini Front-End Projects
            </h3>
            <p class="text-base text-gray-700">
              Tic Tac Toe, Rock Paper Scissors, To-Do List, and First Portfolio
              Website. Built with HTML, CSS, and JS to master web fundamentals
              and responsive design.
            </p>
          </div>
        </div>
      </section>

      <!-- Back Button -->
      <div class="mt-12 text-center">
        <NuxtLink
          to="/"
          class="inline-flex items-center gap-2 bg-gradient-to-r from-sky-500 to-blue-600 text-white font-semibold py-3 px-8 rounded-lg shadow-md hover:shadow-lg transition-all duration-300 hover:scale-105 focus:outline-none focus:ring-2 focus:ring-sky-300 focus:ring-offset-2"
        >
          <svg
            class="w-5 h-5"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M10 19l-7-7m0 0l7-7m-7 7h18"
            />
          </svg>
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
@font-face {
  font-family: "Georgia";
  src: local("Georgia"),
    url("https://fonts.cdnfonts.com/s/17370/Georgia.woff") format("woff");
}

/* Progress Bar Styles */
.progress-bar {
  height: 8px;
  border-radius: 4px;
  background-color: #f3f4f6;
  overflow: hidden;
  border: 1px solid #e5e7eb;
}

.progress-fill {
  height: 100%;
  border-radius: 4px;
  background: linear-gradient(to right, #0284c7, #075985);
  transition: width 0.8s ease-in-out;
  position: relative;
}

.progress-fill::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  background-image: linear-gradient(
    -45deg,
    rgba(255, 255, 255, 0.2) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.2) 50%,
    rgba(255, 255, 255, 0.2) 75%,
    transparent 75%,
    transparent
  );
  background-size: 16px 16px;
  animation: move 1s linear infinite;
}

@keyframes move {
  0% {
    background-position: 0 0;
  }
  100% {
    background-position: 16px 0;
  }
}

/* Skill item hover effects */
.skill-item:hover .progress-fill {
  transform: scaleY(1.1);
  transition: transform 0.2s ease;
}

/* Print styles */
@media print {
  .bg-white,
  .border,
  .shadow-sm,
  .mt-12,
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
  h1,
  h2,
  h3,
  p,
  ul,
  li {
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
