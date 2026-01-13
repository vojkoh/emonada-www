<template>
  <div class="min-h-screen bg-gradient-to-br from-purple-50 to-pink-100">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between h-16">
          <div class="flex items-center">
            <h1 class="text-2xl font-bold text-indigo-600">Emonada</h1>
          </div>
          <div class="flex items-center space-x-4">
            <router-link
              to="/"
              class="text-gray-700 hover:text-indigo-600 px-3 py-2 rounded-md text-sm font-medium transition-colors"
              active-class="text-indigo-600 bg-indigo-50"
            >
              Home
            </router-link>
            <router-link
              to="/about"
              class="text-gray-700 hover:text-indigo-600 px-3 py-2 rounded-md text-sm font-medium transition-colors"
              active-class="text-indigo-600 bg-indigo-50"
            >
              About
            </router-link>
          </div>
        </div>
      </div>
    </nav>

    <!-- About Content -->
    <main class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
      <div class="bg-white rounded-lg shadow-xl p-8 md:p-12">
        <h2 class="text-4xl font-bold text-gray-900 mb-6">About Emonada</h2>
        
        <div class="prose prose-lg max-w-none">
          <p class="text-gray-700 mb-6">
            Emonada is a simple static website template designed to showcase the power and elegance
            of modern web development tools. This project demonstrates how to create a beautiful,
            responsive website using Vue 3 and Tailwind CSS.
          </p>

          <h3 class="text-2xl font-bold text-gray-900 mb-4">Technology Stack</h3>
          <ul class="space-y-3 mb-6">
            <li class="flex items-start">
              <span class="text-indigo-600 mr-2">•</span>
              <span class="text-gray-700">
                <strong>Vue 3:</strong> The progressive JavaScript framework for building user interfaces
              </span>
            </li>
            <li class="flex items-start">
              <span class="text-indigo-600 mr-2">•</span>
              <span class="text-gray-700">
                <strong>Vue Router:</strong> Official routing library for Vue.js
              </span>
            </li>
            <li class="flex items-start">
              <span class="text-indigo-600 mr-2">•</span>
              <span class="text-gray-700">
                <strong>Tailwind CSS:</strong> A utility-first CSS framework for rapid UI development
              </span>
            </li>
            <li class="flex items-start">
              <span class="text-indigo-600 mr-2">•</span>
              <span class="text-gray-700">
                <strong>Vite:</strong> Next-generation frontend tooling for faster development
              </span>
            </li>
          </ul>

          <h3 class="text-2xl font-bold text-gray-900 mb-4">Features</h3>
          <ul class="space-y-3 mb-6">
            <li class="flex items-start">
              <span class="text-indigo-600 mr-2">✓</span>
              <span class="text-gray-700">Clean and modern design</span>
            </li>
            <li class="flex items-start">
              <span class="text-indigo-600 mr-2">✓</span>
              <span class="text-gray-700">Fully responsive layout</span>
            </li>
            <li class="flex items-start">
              <span class="text-indigo-600 mr-2">✓</span>
              <span class="text-gray-700">Fast page navigation with Vue Router</span>
            </li>
            <li class="flex items-start">
              <span class="text-indigo-600 mr-2">✓</span>
              <span class="text-gray-700">Easy to customize and extend</span>
            </li>
            <li class="flex items-start">
              <span class="text-indigo-600 mr-2">✓</span>
              <span class="text-gray-700">Production-ready build configuration</span>
            </li>
          </ul>

          <div class="bg-indigo-50 border-l-4 border-indigo-600 p-6 mt-8">
            <p class="text-gray-800">
              <strong>Note:</strong> This is a demonstration project showcasing best practices
              for building static websites with Vue 3 and Tailwind CSS. Feel free to use it as
              a starting point for your own projects!
            </p>
          </div>
        </div>

        <div class="mt-8 text-center">
          <router-link
            to="/"
            class="inline-block bg-indigo-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-indigo-700 transition-colors shadow-lg"
          >
            Back to Home
          </router-link>
        </div>
      </div>
    </main>

    <!-- Footer -->
    <footer class="bg-white mt-20 border-t border-gray-200">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8">
        <p class="text-center text-gray-500">
          © 2026 Emonada. Built with Vue 3 and Tailwind CSS.
        </p>
      </div>
    </footer>
  </div>
</template>

<script setup>
// About page component
</script>
