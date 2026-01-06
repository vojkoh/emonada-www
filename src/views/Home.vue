<template>
  <div class="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100">
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

    <!-- Hero Section -->
    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
      <div class="text-center">
        <h2 class="text-5xl font-extrabold text-gray-900 mb-4">
          Welcome to Emonada
        </h2>
        <p class="text-xl text-gray-600 mb-8 max-w-2xl mx-auto">
          A simple, elegant static website built with Vue 3 and Tailwind CSS
        </p>
        <div class="flex justify-center space-x-4">
          <router-link
            to="/about"
            class="bg-indigo-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-indigo-700 transition-colors shadow-lg"
          >
            Learn More
          </router-link>
          <a
            href="https://github.com"
            class="bg-gray-200 text-gray-800 px-8 py-3 rounded-lg font-semibold hover:bg-gray-300 transition-colors"
          >
            View on GitHub
          </a>
        </div>
      </div>

      <!-- Features Grid -->
      <div class="mt-20 grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded-lg shadow-md">
          <div class="text-indigo-600 text-4xl mb-4">⚡</div>
          <h3 class="text-xl font-bold mb-2">Fast & Modern</h3>
          <p class="text-gray-600">
            Built with Vue 3 and Vite for lightning-fast development and production builds.
          </p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <div class="text-indigo-600 text-4xl mb-4">🎨</div>
          <h3 class="text-xl font-bold mb-2">Beautiful Design</h3>
          <p class="text-gray-600">
            Styled with Tailwind CSS for a clean and responsive user interface.
          </p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <div class="text-indigo-600 text-4xl mb-4">📱</div>
          <h3 class="text-xl font-bold mb-2">Responsive</h3>
          <p class="text-gray-600">
            Looks great on all devices, from mobile phones to desktop computers.
          </p>
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
// Home page component
</script>
