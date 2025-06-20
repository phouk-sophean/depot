<template>
  <div class="min-h-screen bg-gradient-to-br from-slate-50 via-blue-50 to-indigo-100 py-8">
    <div class="max-w-7xl mx-auto px-6">
      
      <!-- Header Section -->
      <div class="mb-8">
        <div class="flex flex-col md:flex-row md:items-center md:justify-between">
          <div>
            <h1 class="text-4xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-blue-600 to-purple-600 mb-2">
              User Management
            </h1>
            <p class="text-slate-600">Manage and view all registered users</p>
          </div>
          <div class="mt-4 md:mt-0">
            <div class="inline-flex items-center px-4 py-2 bg-blue-100 text-blue-700 rounded-full text-sm font-medium">
              👥 5 Active Users
            </div>
          </div>
        </div>
      </div>

      <!-- Users Grid -->
      <div class="grid gap-6">
        
        <!-- User 1 -->
        <div class="bg-white/80 backdrop-blur-sm rounded-2xl shadow-lg border border-white/20 p-6 hover:shadow-xl transition-all duration-300 hover:-translate-y-1">
          <div class="flex flex-col md:flex-row md:items-center md:justify-between">
            <div class="flex items-center space-x-4 mb-4 md:mb-0">
              <div class="relative">
                <div class="w-16 h-16 bg-gradient-to-r from-blue-500 to-purple-600 rounded-full flex items-center justify-center text-white text-xl font-bold">
                  JD
                </div>
                <div class="absolute -bottom-1 -right-1 w-5 h-5 bg-green-500 rounded-full border-2 border-white"></div>
              </div>
              <div>
                <h3 class="text-xl font-bold text-slate-800">John Doe</h3>
                <p class="text-slate-600">Software Engineer</p>
              </div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-8 flex-1 md:ml-8">
              <div>
                <p class="text-sm font-semibold text-slate-500 mb-1">Email</p>
                <p class="text-slate-700">john.doe@company.com</p>
              </div>
              <div>
                <p class="text-sm font-semibold text-slate-500 mb-1">Phone</p>
                <p class="text-slate-700">+1 (555) 123-4567</p>
              </div>
              <div>
                <span class="inline-flex items-center px-3 py-1 rounded-full text-sm font-medium bg-green-100 text-green-800">
                  ✅ Active
                </span>
              </div>
            </div>
          </div>
        </div>

        <!-- User 2 -->
        <div class="bg-white/80 backdrop-blur-sm rounded-2xl shadow-lg border border-white/20 p-6 hover:shadow-xl transition-all duration-300 hover:-translate-y-1">
          <div class="flex flex-col md:flex-row md:items-center md:justify-between">
            <div class="flex items-center space-x-4 mb-4 md:mb-0">
              <div class="relative">
                <div class="w-16 h-16 bg-gradient-to-r from-pink-500 to-rose-600 rounded-full flex items-center justify-center text-white text-xl font-bold">
                  JS
                </div>
                <div class="absolute -bottom-1 -right-1 w-5 h-5 bg-green-500 rounded-full border-2 border-white"></div>
              </div>
              <div>
                <h3 class="text-xl font-bold text-slate-800">Jane Smith</h3>
                <p class="text-slate-600">UI/UX Designer</p>
              </div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-8 flex-1 md:ml-8">
              <div>
                <p class="text-sm font-semibold text-slate-500 mb-1">Email</p>
                <p class="text-slate-700">jane.smith@company.com</p>
              </div>
              <div>
                <p class="text-sm font-semibold text-slate-500 mb-1">Phone</p>
                <p class="text-slate-700">+1 (555) 234-5678</p>
              </div>
              <div>
                <span class="inline-flex items-center px-3 py-1 rounded-full text-sm font-medium bg-green-100 text-green-800">
                  ✅ Active
                </span>
              </div>
            </div>
          </div>
        </div>

        <!-- User 3 -->
        <div class="bg-white/80 backdrop-blur-sm rounded-2xl shadow-lg border border-white/20 p-6 hover:shadow-xl transition-all duration-300 hover:-translate-y-1">
          <div class="flex flex-col md:flex-row md:items-center md:justify-between">
            <div class="flex items-center space-x-4 mb-4 md:mb-0">
              <div class="relative">
                <div class="w-16 h-16 bg-gradient-to-r from-green-500 to-teal-600 rounded-full flex items-center justify-center text-white text-xl font-bold">
                  MJ
                </div>
                <div class="absolute -bottom-1 -right-1 w-5 h-5 bg-yellow-500 rounded-full border-2 border-white"></div>
              </div>
              <div>
                <h3 class="text-xl font-bold text-slate-800">Michael Johnson</h3>
                <p class="text-slate-600">Project Manager</p>
              </div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-8 flex-1 md:ml-8">
              <div>
                <p class="text-sm font-semibold text-slate-500 mb-1">Email</p>
                <p class="text-slate-700">michael.j@company.com</p>
              </div>
              <div>
                <p class="text-sm font-semibold text-slate-500 mb-1">Phone</p>
                <p class="text-slate-700">+1 (555) 345-6789</p>
              </div>
              <div>
                <span class="inline-flex items-center px-3 py-1 rounded-full text-sm font-medium bg-yellow-100 text-yellow-800">
                  ⏸️ Away
                </span>
              </div>
            </div>
          </div>
        </div>

        <!-- User 4 -->
        <div class="bg-white/80 backdrop-blur-sm rounded-2xl shadow-lg border border-white/20 p-6 hover:shadow-xl transition-all duration-300 hover:-translate-y-1">
          <div class="flex flex-col md:flex-row md:items-center md:justify-between">
            <div class="flex items-center space-x-4 mb-4 md:mb-0">
              <div class="relative">
                <div class="w-16 h-16 bg-gradient-to-r from-purple-500 to-indigo-600 rounded-full flex items-center justify-center text-white text-xl font-bold">
                  EB
                </div>
                <div class="absolute -bottom-1 -right-1 w-5 h-5 bg-red-500 rounded-full border-2 border-white"></div>
              </div>
              <div>
                <h3 class="text-xl font-bold text-slate-800">Emily Brown</h3>
                <p class="text-slate-600">Marketing Specialist</p>
              </div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-8 flex-1 md:ml-8">
              <div>
                <p class="text-sm font-semibold text-slate-500 mb-1">Email</p>
                <p class="text-slate-700">emily.brown@company.com</p>
              </div>
              <div>
                <p class="text-sm font-semibold text-slate-500 mb-1">Phone</p>
                <p class="text-slate-700">+1 (555) 456-7890</p>
              </div>
              <div>
                <span class="inline-flex items-center px-3 py-1 rounded-full text-sm font-medium bg-red-100 text-red-800">
                  ❌ Inactive
                </span>
              </div>
            </div>
          </div>
        </div>

        <!-- User 5 -->
        <div class="bg-white/80 backdrop-blur-sm rounded-2xl shadow-lg border border-white/20 p-6 hover:shadow-xl transition-all duration-300 hover:-translate-y-1">
          <div class="flex flex-col md:flex-row md:items-center md:justify-between">
            <div class="flex items-center space-x-4 mb-4 md:mb-0">
              <div class="relative">
                <div class="w-16 h-16 bg-gradient-to-r from-orange-500 to-red-600 rounded-full flex items-center justify-center text-white text-xl font-bold">
                  DW
                </div>
                <div class="absolute -bottom-1 -right-1 w-5 h-5 bg-green-500 rounded-full border-2 border-white"></div>
              </div>
              <div>
                <h3 class="text-xl font-bold text-slate-800">David Wilson</h3>
                <p class="text-slate-600">DevOps Engineer</p>
              </div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-8 flex-1 md:ml-8">
              <div>
                <p class="text-sm font-semibold text-slate-500 mb-1">Email</p>
                <p class="text-slate-700">david.wilson@company.com</p>
              </div>
              <div>
                <p class="text-sm font-semibold text-slate-500 mb-1">Phone</p>
                <p class="text-slate-700">+1 (555) 567-8901</p>
              </div>
              <div>
                <span class="inline-flex items-center px-3 py-1 rounded-full text-sm font-medium bg-green-100 text-green-800">
                  ✅ Active
                </span>
              </div>
            </div>
          </div>
        </div>

      </div>

      <!-- Summary Stats -->
      <div class="mt-12 grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-white/80 backdrop-blur-sm rounded-2xl p-6 shadow-lg border border-white/20 text-center">
          <div class="text-3xl font-bold text-green-600 mb-2">3</div>
          <div class="text-slate-600 font-medium">Active Users</div>
        </div>
        <div class="bg-white/80 backdrop-blur-sm rounded-2xl p-6 shadow-lg border border-white/20 text-center">
          <div class="text-3xl font-bold text-yellow-600 mb-2">1</div>
          <div class="text-slate-600 font-medium">Away Users</div>
        </div>
        <div class="bg-white/80 backdrop-blur-sm rounded-2xl p-6 shadow-lg border border-white/20 text-center">
          <div class="text-3xl font-bold text-red-600 mb-2">1</div>
          <div class="text-slate-600 font-medium">Inactive Users</div>
        </div>
      </div>

    </div>
  </div>
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
</template>