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
        <div>
          <div class="w-36 border-t border-gray-700 pt-2">
            <span class="text-sm font-normal text-teal-500">hello@razor.de</span>
          </div>
          <span>Get the app</span>
          <h1 class="text-5xl font-bold leading-tight tracking-tight">Enter your email. We'll send you a download
            link</h1>
          <div>
            <input type="text">
            <button>Get Link</button>
          </div>
          <p>By signing up, I agree to the Razor Privacy Policy & Terms of Service</p>
          <div>
            <button>Play Store</button>
            <button>App Store</button>
          </div>
        </div>
        <div></div>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>

</style>
