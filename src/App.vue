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
              <input type="text" class="px-6 py-4 flex-1 rounded-l-xl border-2 border-r-0 border-gray-700 bg-gray-900 leading-6 focus:outline-none">
              <button class="px-6 py-4 rounded-r-xl border-2 border-l-0 border-gray-700 bg-teal-500 text-gray-900 text-lg leading-6 font-bold">Get Link</button>
            </div>
            <p class="pt-8 font-normal tracking-wide text-gray-600">
              By signing up, I agree to the Razor
              <a href="" class="text-gray-500 underline">Privacy Policy</a> &
              <a href="" class="text-gray-500 underline">Terms of Service</a>
            </p>
            <div class="flex items-center gap-4 pt-12">
              <button class="flex items-center gap-2 px-6 py-4 text-gray-500 rounded-xl bg-gray-900">
                <PlayStoreIcon class="h-7 w-7"/>
                Play Store
              </button>
              <button class="flex items-center gap-2 px-6 py-4 text-gray-500 rounded-xl bg-gray-900">
                <AppleIcon class="h-7 w-7"/>
                App Store
              </button>
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
import AppleIcon from './icons/apple.svg'
import PlayStoreIcon from './icons/play-store.svg'
</script>

<style scoped>

</style>
