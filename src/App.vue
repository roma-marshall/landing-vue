<template>
  <div class="min-h-screen w-full bg-gray-800 text-white">
    <div class="mx-auto max-w-7xl px-4 pt-8">
      <nav class="flex items-center justify-between">
        <div class="flex items-center gap-32">
          <a href="#" class="text-2xl font-bold">Razor</a>
          <ul class="flex items-center gap-12 font-medium text-gray-500">
            <li><a href="#" class="hover:text-white">Product</a></li>
            <li><a href="#" class="hover:text-white">Resource</a></li>
            <li><a href="#" class="hover:text-white">Support</a></li>
            <li><a href="#" class="hover:text-white">Pricing</a></li>
            <li><a href="#" class="hover:text-white">Blog</a></li>
          </ul>
        </div>
        <div class="flex items-center gap-4 font-medium text-gray-500">
          <a href="#" class="hover:text-white">Sign In</a>
          <a href="#" class="hover:text-white">Request Demo</a>
        </div>
      </nav>
      <div class="grid grid-cols-2 pt-6">
        <div class="max-w-xl pr-24">
          <div class="flex items-center gap-6 w-36 border-t border-gray-700 pt-2">
            <span class="text-sm font-normal text-teal-500">hello@razor.de</span>
            <ArrowRight class="h-4 w-4 text-teal-500"/>
          </div>
          <div class="pt-16">
            <span>&#8212; Get the App</span>
            <h1 class="text-6xl font-bold tracking-tight pt-6 bg-gradient-to-br from-blue-400 to-emerald-400 bg-clip-text text-transparent">
              Enter your email <br />
              &#8212; We'll send you a download link
            </h1>
            <div class="flex items-center mt-10">
              <input type="text" class="px-6 py-4 border-2 border-gray-700 bg-gray-900">
              <button class="px-6 py-4 border-2 border-gray-700 bg-teal-500 text-gray-900 font-bold">Get Link</button>
            </div>
            <p>By signing up, I agree to the Razor Privacy Policy & Terms of Service</p>
            <div>
              <button>Play Store</button>
              <button>App Store</button>
            </div>
          </div>
        </div>
        <div></div>
      </div>
    </div>
  </div>
</template>

<script setup>
import ArrowRight from './icons/arrow-right.svg'
</script>

<style scoped>

</style>
