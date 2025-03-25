<template>
    <footer class="bg-gradient-to-r from-gray-900 to-gray-800 text-white py-8 text-center">
      <div class="container mx-auto flex flex-col items-center">
        <p class="text-lg font-semibold opacity-80">&copy; 2025 - {{ name }}</p>
        <div class="flex space-x-6 mt-6">
          <a v-for="(link, platform) in socialLinks" 
             :key="platform" 
             :href="link" 
             target="_blank" 
             class="group flex flex-col items-center space-y-2 bg-gray-800 px-6 py-3 rounded-xl hover:bg-gray-700 transition transform hover:scale-110 shadow-lg hover:shadow-2xl">
            <i :class="icons[platform]" class="text-3xl transition-transform duration-300 group-hover:rotate-6"></i>
            <span class="text-md font-medium group-hover:text-gray-300 transition">{{ platform }}</span>
          </a>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    data() {
      return {
        name: "Amilkar Vladimir Reyes Reyes", 
        socialLinks: {
          Facebook: "https://facebook.com/Amilkar Reyes",
          Twitter: "https://twitter.com/tuusuario",
          Instagram: "https://instagram.com/amilkar_reyes_07",
        },
        icons: {
          Facebook: "fab fa-facebook-f text-blue-500",
          Twitter: "fab fa-twitter text-blue-400",
          Instagram: "fab fa-instagram text-pink-500",
        },
      };
    },
  };
  </script>
  
  <style scoped>
  footer a {
    transition: transform 0.3s, background 0.3s;
  }
  
  footer a:hover {
    transform: scale(1.1);
  }
  </style>
  