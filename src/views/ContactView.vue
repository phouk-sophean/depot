<template>
  <div class="min-h-screen bg-gradient-to-br from-slate-50 via-blue-50 to-indigo-100">
    <section class="py-20 px-4">
      <div class="max-w-7xl mx-auto">
        
        <!-- Header Section -->
        <div class="text-center mb-16 space-y-6">
          <div class="inline-flex items-center px-4 py-2 bg-blue-100 text-blue-700 rounded-full text-sm font-medium mb-4">
            📞 Get In Touch
          </div>
          <h1 class="text-5xl md:text-7xl font-black text-transparent bg-clip-text bg-gradient-to-r from-blue-600 via-purple-600 to-cyan-500 leading-tight">
            Contact Us
          </h1>
          <p class="max-w-3xl mx-auto text-slate-600 text-xl leading-relaxed font-light">
            We'd love to hear from you. Send us a message and we'll respond as soon as possible.
          </p>
        </div>

        <div class="grid lg:grid-cols-2 gap-16 items-start">
          
          <!-- Contact Form -->
          <div class="bg-white/80 backdrop-blur-sm rounded-2xl shadow-xl p-8 border border-white/20">
            <h2 class="text-3xl font-bold text-slate-800 mb-8">Send us a message</h2>
            
            <form class="space-y-6">
              <!-- Name Fields -->
              <div class="grid md:grid-cols-2 gap-6">
                <div class="space-y-2">
                  <label for="firstName" class="text-sm font-semibold text-slate-700">First Name</label>
                  <input 
                    type="text" 
                    id="firstName" 
                    name="firstName"
                    class="w-full px-4 py-3 bg-slate-50 border border-slate-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition-all duration-300"
                    placeholder="John"
                  />
                </div>
                <div class="space-y-2">
                  <label for="lastName" class="text-sm font-semibold text-slate-700">Last Name</label>
                  <input 
                    type="text" 
                    id="lastName" 
                    name="lastName"
                    class="w-full px-4 py-3 bg-slate-50 border border-slate-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition-all duration-300"
                    placeholder="Doe"
                  />
                </div>
              </div>

              <!-- Email -->
              <div class="space-y-2">
                <label for="email" class="text-sm font-semibold text-slate-700">Email Address</label>
                <input 
                  type="email" 
                  id="email" 
                  name="email"
                  class="w-full px-4 py-3 bg-slate-50 border border-slate-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition-all duration-300"
                  placeholder="john@example.com"
                />
              </div>

              <!-- Phone -->
              <div class="space-y-2">
                <label for="phone" class="text-sm font-semibold text-slate-700">Phone Number</label>
                <input 
                  type="tel" 
                  id="phone" 
                  name="phone"
                  class="w-full px-4 py-3 bg-slate-50 border border-slate-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition-all duration-300"
                  placeholder="+1 (555) 123-4567"
                />
              </div>

              <!-- Subject -->
              <div class="space-y-2">
                <label for="subject" class="text-sm font-semibold text-slate-700">Subject</label>
                <select 
                  id="subject" 
                  name="subject"
                  class="w-full px-4 py-3 bg-slate-50 border border-slate-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition-all duration-300"
                >
                  <option value="">Select a subject</option>
                  <option value="general">General Inquiry</option>
                  <option value="support">Technical Support</option>
                  <option value="sales">Sales Question</option>
                  <option value="partnership">Partnership</option>
                  <option value="other">Other</option>
                </select>
              </div>

              <!-- Message -->
              <div class="space-y-2">
                <label for="message" class="text-sm font-semibold text-slate-700">Message</label>
                <textarea 
                  id="message" 
                  name="message" 
                  rows="5"
                  class="w-full px-4 py-3 bg-slate-50 border border-slate-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition-all duration-300 resize-none"
                  placeholder="Tell us about your project or question..."
                ></textarea>
              </div>

              <!-- Submit Button -->
              <button 
                type="submit"
                class="w-full bg-gradient-to-r from-blue-500 to-purple-600 hover:from-blue-600 hover:to-purple-700 text-white font-semibold py-4 rounded-xl transition-all duration-300 transform hover:scale-105 shadow-lg hover:shadow-xl"
              >
                Send Message 🚀
              </button>
            </form>
          </div>

          <!-- Contact Information -->
          <div class="space-y-8">
            
            <!-- Contact Cards -->
            <div class="space-y-6">
              
              <!-- Office Location -->
              <div class="group bg-white/80 backdrop-blur-sm rounded-2xl p-6 shadow-lg border border-white/20 hover:shadow-xl transition-all duration-300 hover:-translate-y-1">
                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-gradient-to-r from-blue-500 to-purple-600 rounded-xl flex items-center justify-center text-white text-xl flex-shrink-0 group-hover:scale-110 transition-transform duration-300">
                    📍
                  </div>
                  <div>
                    <h3 class="text-xl font-bold text-slate-800 mb-2">Visit Our Office</h3>
                    <p class="text-slate-600 leading-relaxed">
                      123 Business Street<br>
                      Suite 100<br>
                      New York, NY 10001<br>
                      United States
                    </p>
                  </div>
                </div>
              </div>

              <!-- Phone -->
              <div class="group bg-white/80 backdrop-blur-sm rounded-2xl p-6 shadow-lg border border-white/20 hover:shadow-xl transition-all duration-300 hover:-translate-y-1">
                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-gradient-to-r from-green-500 to-teal-600 rounded-xl flex items-center justify-center text-white text-xl flex-shrink-0 group-hover:scale-110 transition-transform duration-300">
                    📞
                  </div>
                  <div>
                    <h3 class="text-xl font-bold text-slate-800 mb-2">Call Us</h3>
                    <p class="text-slate-600 leading-relaxed">
                      Main: +1 (555) 123-4567<br>
                      Support: +1 (555) 123-4568<br>
                      Sales: +1 (555) 123-4569
                    </p>
                  </div>
                </div>
              </div>

              <!-- Email -->
              <div class="group bg-white/80 backdrop-blur-sm rounded-2xl p-6 shadow-lg border border-white/20 hover:shadow-xl transition-all duration-300 hover:-translate-y-1">
                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-gradient-to-r from-purple-500 to-pink-600 rounded-xl flex items-center justify-center text-white text-xl flex-shrink-0 group-hover:scale-110 transition-transform duration-300">
                    ✉️
                  </div>
                  <div>
                    <h3 class="text-xl font-bold text-slate-800 mb-2">Email Us</h3>
                    <p class="text-slate-600 leading-relaxed">
                      General: hello@company.com<br>
                      Support: support@company.com<br>
                      Sales: sales@company.com
                    </p>
                  </div>
                </div>
              </div>

              <!-- Business Hours -->
              <div class="group bg-white/80 backdrop-blur-sm rounded-2xl p-6 shadow-lg border border-white/20 hover:shadow-xl transition-all duration-300 hover:-translate-y-1">
                <div class="flex items-start space-x-4">
                  <div class="w-12 h-12 bg-gradient-to-r from-orange-500 to-red-600 rounded-xl flex items-center justify-center text-white text-xl flex-shrink-0 group-hover:scale-110 transition-transform duration-300">
                    🕒
                  </div>
                  <div>
                    <h3 class="text-xl font-bold text-slate-800 mb-2">Business Hours</h3>
                    <p class="text-slate-600 leading-relaxed">
                      Monday - Friday: 9:00 AM - 6:00 PM<br>
                      Saturday: 10:00 AM - 4:00 PM<br>
                      Sunday: Closed
                    </p>
                  </div>
                </div>
              </div>

            </div>

            <!-- Social Media -->
            <div class="bg-gradient-to-r from-blue-600 to-purple-600 rounded-2xl p-1">
              <div class="bg-white rounded-2xl p-6">
                <h3 class="text-xl font-bold text-slate-800 mb-4 text-center">Follow Us</h3>
                <div class="flex justify-center space-x-4">
                  <a href="#" class="w-12 h-12 bg-blue-500 hover:bg-blue-600 rounded-xl flex items-center justify-center text-white transition-all duration-300 hover:scale-110">
                    📘
                  </a>
                  <a href="#" class="w-12 h-12 bg-sky-500 hover:bg-sky-600 rounded-xl flex items-center justify-center text-white transition-all duration-300 hover:scale-110">
                    🐦
                  </a>
                  <a href="#" class="w-12 h-12 bg-blue-700 hover:bg-blue-800 rounded-xl flex items-center justify-center text-white transition-all duration-300 hover:scale-110">
                    💼
                  </a>
                  <a href="#" class="w-12 h-12 bg-pink-500 hover:bg-pink-600 rounded-xl flex items-center justify-center text-white transition-all duration-300 hover:scale-110">
                    📷
                  </a>
                </div>
              </div>
            </div>

          </div>
        </div>

        <!-- FAQ Section -->
        <div class="mt-20">
          <div class="text-center mb-12">
            <h2 class="text-4xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-blue-600 to-purple-600 mb-4">
              Frequently Asked Questions
            </h2>
            <p class="text-slate-600 text-lg">Quick answers to common questions</p>
          </div>

          <div class="grid md:grid-cols-2 gap-8">
            <div class="bg-white/80 backdrop-blur-sm rounded-2xl p-6 shadow-lg border border-white/20">
              <h4 class="text-lg font-bold text-slate-800 mb-3">How quickly do you respond?</h4>
              <p class="text-slate-600">We typically respond to all inquiries within 24 hours during business days.</p>
            </div>
            
            <div class="bg-white/80 backdrop-blur-sm rounded-2xl p-6 shadow-lg border border-white/20">
              <h4 class="text-lg font-bold text-slate-800 mb-3">Do you offer free consultations?</h4>
              <p class="text-slate-600">Yes! We offer free 30-minute consultations to discuss your project needs.</p>
            </div>
            
            <div class="bg-white/80 backdrop-blur-sm rounded-2xl p-6 shadow-lg border border-white/20">
              <h4 class="text-lg font-bold text-slate-800 mb-3">What's your project timeline?</h4>
              <p class="text-slate-600">Project timelines vary based on scope, but most projects are completed within 4-12 weeks.</p>
            </div>
            
            <div class="bg-white/80 backdrop-blur-sm rounded-2xl p-6 shadow-lg border border-white/20">
              <h4 class="text-lg font-bold text-slate-800 mb-3">Do you work internationally?</h4>
              <p class="text-slate-600">We work with clients worldwide and accommodate different time zones.</p>
            </div>
          </div>
        </div>

        <!-- Call to Action -->
        <div class="mt-20 text-center">
          <div class="bg-gradient-to-r from-blue-600 to-purple-600 rounded-3xl p-1">
            <div class="bg-white rounded-3xl p-12">
              <h3 class="text-3xl font-bold text-slate-800 mb-4">Ready to Start Your Project?</h3>
              <p class="text-xl text-slate-600 mb-8 max-w-2xl mx-auto">
                Let's discuss how we can help bring your vision to life. Get in touch today for a free consultation.
              </p>
              <button class="bg-gradient-to-r from-blue-500 to-purple-600 hover:from-blue-600 hover:to-purple-700 text-white font-semibold px-8 py-4 rounded-xl transition-all duration-300 transform hover:scale-105 shadow-lg hover:shadow-xl">
                Schedule a Call 📅
              </button>
            </div>
          </div>
        </div>

      </div>
    </section>
      <footer
    class="relative bg-gradient-to-r from-slate-900 via-blue-900 to-indigo-900 text-white py-12 mt-20"
  >
    <div class="relative max-w-7xl mx-auto px-6">
      <div
        class="flex flex-col md:flex-row justify-between items-center space-y-6 md:space-y-0"
      >
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
          <div
            class="w-24 h-1 bg-gradient-to-r from-blue-500 to-purple-500 rounded-full"
          ></div>
        </div>
      </div>
    </div>
  </footer>
  </div>
</template>