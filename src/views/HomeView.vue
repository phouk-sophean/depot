<script setup>
const cards = [
  {
    id: 1,
    title: 'Web Development',
    description: 'Build fast and modern websites using the latest technologies.',
    buttonText: 'Learn More',
    image: 'https://images.squarespace-cdn.com/content/v1/55408447e4b0543265612fa6/1714545057173-E751CV4CI6HB9EYOTB20/Blue+Bird.jpg',
  },
  {
    id: 2,
    title: 'UI/UX Design',
    description: 'Create stunning and user-friendly interfaces for your apps.',
    buttonText: 'Explore',
    image: 'https://images.squarespace-cdn.com/content/v1/55408447e4b0543265612fa6/1714545057173-E751CV4CI6HB9EYOTB20/Blue+Bird.jpg',
  },
  {
    id: 3,
    title: 'Digital Marketing',
    description: 'Boost your brand visibility and reach more customers.',
    buttonText: 'Get Started',
    image: 'https://images.squarespace-cdn.com/content/v1/55408447e4b0543265612fa6/1714545057173-E751CV4CI6HB9EYOTB20/Blue+Bird.jpg',
  },
  {
    id: 4,
    title: 'Software Engineer',
    description: 'Boost your brand visibility and reach more customers.',
    buttonText: 'Let go',
    image: 'https://images.squarespace-cdn.com/content/v1/55408447e4b0543265612fa6/1714545057173-E751CV4CI6HB9EYOTB20/Blue+Bird.jpg',
  },
]
</script>

<template>
  <div class="min-h-screen bg-gradient-to-br from-slate-50 via-blue-50 to-indigo-100">
    <section class="py-20 px-4">
      <div class="max-w-7xl mx-auto">
        <!-- Hero Section -->
        <div class="text-center mb-16 space-y-6">
          <div class="inline-flex items-center px-4 py-2 bg-blue-100 text-blue-700 rounded-full text-sm font-medium mb-4">
            ✨ Welcome to Excellence
          </div>
          <h1 class="text-5xl md:text-7xl font-black text-transparent bg-clip-text bg-gradient-to-r from-blue-600 via-purple-600 to-cyan-500 leading-tight">
            Welcome to our home!
          </h1>
          <p class="max-w-4xl mx-auto text-slate-600 text-xl leading-relaxed font-light">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas amet
            quod consequatur ipsam animi magni a nisi expedita cupiditate reiciendis
            quisquam obcaecati debitis, dicta nesciunt laudantium dolores nihil aliquam
            ducimus.
          </p>
        </div>

        <!-- Cards Grid -->
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
          <div 
            v-for="(card, index) in cards" 
            :key="card.id"
            class="group relative bg-white/80 backdrop-blur-sm rounded-2xl shadow-lg hover:shadow-2xl transition-all duration-500 hover:-translate-y-2 border border-white/20 overflow-hidden"
            :style="{ animationDelay: `${index * 100}ms` }"
          >
            <!-- Card Image -->
            <div class="relative overflow-hidden rounded-t-2xl">
              <img 
                :src="card.image" 
                :alt="card.title" 
                class="w-full h-48 object-cover transition-transform duration-700 group-hover:scale-110" 
              />
              <div class="absolute inset-0 bg-gradient-to-t from-black/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
            </div>

            <!-- Card Content -->
            <div class="p-6 space-y-4">
              <h3 class="text-xl font-bold text-slate-800 group-hover:text-blue-600 transition-colors duration-300">
                {{ card.title }}
              </h3>
              <p class="text-slate-600 leading-relaxed text-sm">
                {{ card.description }}
              </p>
              <button class="w-full bg-gradient-to-r from-blue-500 to-purple-600 hover:from-blue-600 hover:to-purple-700 text-white font-semibold py-2.5 rounded-xl transition-all duration-300 transform hover:scale-105 shadow-lg hover:shadow-xl">
                {{ card.buttonText }}
              </button>
            </div>

            <!-- Decorative Elements -->
            <div class="absolute top-4 right-4 w-8 h-8 bg-gradient-to-br from-blue-400 to-purple-500 rounded-full opacity-20 group-hover:opacity-40 transition-opacity duration-300"></div>
            <div class="absolute -bottom-2 -right-2 w-16 h-16 bg-gradient-to-br from-cyan-400 to-blue-500 rounded-full opacity-10 group-hover:opacity-20 transition-opacity duration-300"></div>
          </div>
        </div>
      </div>
    </section>

    <!-- Enhanced Footer -->
    <footer class="relative bg-gradient-to-r from-slate-900 via-blue-900 to-indigo-900 text-white py-12 mt-20">
      
      <div class="relative max-w-7xl mx-auto px-6">
        <div class="flex flex-col md:flex-row justify-between items-center space-y-6 md:space-y-0">
          <div class="text-center md:text-left">
            <p class="text-slate-300 text-sm">
              © 2025 YourCompany. All rights reserved.
            </p>
            <p class="text-slate-400 text-xs mt-1">
              Crafted with ❤️ for excellence
            </p>
          </div>
          
          <div class="flex flex-wrap justify-center md:justify-end gap-8">
            <a 
              href="#" 
              class="text-slate-300 hover:text-yellow-400 transition-all duration-300 hover:scale-105 text-sm font-medium"
            >
              Privacy Policy
            </a>
            <a 
              href="#" 
              class="text-slate-300 hover:text-yellow-400 transition-all duration-300 hover:scale-105 text-sm font-medium"
            >
              Terms of Service
            </a>
            <a 
              href="#" 
              class="text-slate-300 hover:text-yellow-400 transition-all duration-300 hover:scale-105 text-sm font-medium"
            >
              Contact Us
            </a>
          </div>
        </div>
        
        <!-- Decorative Line -->
        <div class="mt-8 pt-8 border-t border-slate-700/50">
          <div class="flex justify-center">
            <div class="w-24 h-1 bg-gradient-to-r from-blue-500 to-purple-500 rounded-full"></div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>