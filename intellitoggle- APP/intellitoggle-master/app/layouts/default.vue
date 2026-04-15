<template>
  <nav
    class="bg-[#42389E] py-6 px-4 md:py-8 md:px-12 lg:py-10 lg:px-24 xl:px-[120px] flex flex-wrap justify-between items-center gap-4">
    <div class="flex-shrink-0">
      <img src="~/assets/images/intellitoggle.png" alt="Intellitoggle Logo"
        class="w-32 h-8 sm:w-40 sm:h-10 md:w-[205.5px] md:h-[50.8px]">
    </div>

    <button class="md:hidden text-white p-2" @click="mobileMenuOpen = !mobileMenuOpen">
      <img src="~/assets/images/menu.png" alt="Menu icon" class="w-6 h-6">
    </button>

    <div class="hidden md:flex">
      <ul class="flex items-center gap-4 lg:gap-[27px] text-white text-sm lg:text-base">
        <li>
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about">About</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/pricing">Pricing</NuxtLink>
        </li>
      </ul>
    </div>

    <div class="hidden md:block">
      <button
        class="bg-[#F9A71E] px-4 py-2 lg:px-6 lg:py-3 rounded-lg text-[#0F1026] font-semibold text-sm lg:text-base">Start
        Sandbox</button>
    </div>

    <div v-if="mobileMenuOpen" class="w-full md:hidden mt-4">
      <ul class="flex flex-col gap-4 text-white">
        <li>
          <NuxtLink to="/" @click="mobileMenuOpen = false">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about" @click="mobileMenuOpen = false">About</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/pricing" @click="mobileMenuOpen = false">Pricing</NuxtLink>
        </li>
        <li><button class="bg-[#F9A71E] px-6 py-3 rounded-lg text-[#0F1026] font-semibold w-full md:w-[214px]">Start Sandbox</button>
        </li>
      </ul>
    </div>
  </nav>

  <div>
    <slot />
  </div>

  <!-- Footer -->
  <footer class="bg-[#ECEBF5] px-4 py-12 md:px-12 md:py-16 lg:px-24 lg:py-20 xl:px-[120px]">
    <div class="flex flex-col lg:flex-row justify-between gap-8 lg:gap-12">
      <div class="max-w-full lg:max-w-[300px]">
        <div class="mb-5">
          <img src="~/assets/images/intellitogggle_footer.png" alt="Intellitoggle Logo"
            class="w-36 h-11 md:w-[170.5px] md:h-[50.8px]">
        </div>
        <p class="text-[#4A4B4D] text-sm mb-4">
          IntelliToggle is built by AORTEM, a company focused on powering scalable, multi-platform developer tools.
        </p>
        <div>
          <img src="~/assets/images/github.png" alt="Intellitoggle Logo"
            class="w-[30px] h-[30px]">
        </div>
      </div>

      <div class="flex flex-col sm:flex-row gap-8 sm:gap-12 lg:gap-[118px]">
        <div>
          <h2 class="text-[#5F5F60] mb-4 lg:mb-6 font-semibold">Resources</h2>
          <ul class="font-semibold text-[#323338] space-y-3 lg:space-y-4 text-sm lg:text-base">
            <li class="cursor-pointer">Why Intellitoggle is different</li>
            <li class="cursor-pointer">Customer Support</li>
            <li class="cursor-pointer">Terms & Conditions</li>
            <li class="cursor-pointer">Privacy Policy</li>
          </ul>
        </div>
        <div>
          <h2 class="text-[#5F5F60] mb-4 lg:mb-6 font-semibold">Company</h2>
          <ul class="font-semibold text-[#323338] space-y-3 lg:space-y-4 text-sm lg:text-base">
            <li class="cursor-pointer">Pricing</li>
            <li class="cursor-pointer">Documentation</li>
            <li class="cursor-pointer">About Us</li>
          </ul>
        </div>
      </div>

      <div class="w-full lg:w-auto">
        <h1 class="text-[#323338] mb-4 lg:mb-6 font-semibold">Newsletter</h1>
        <div class="flex flex-col sm:flex-row items-stretch sm:items-center">
          <input type="text" placeholder="Enter email address"
            class="py-3 px-4 rounded-lg sm:rounded-l-lg sm:rounded-r-none placeholder:text-sm flex-1 min-w-0">
          <button
            class="bg-[#F9A71E] px-6 py-3 rounded-lg sm:rounded-l-none sm:rounded-r-lg text-[#0F1026] font-semibold whitespace-nowrap">
            Subscribe to Newsletter
          </button>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup>
import { ref } from 'vue'
const mobileMenuOpen = ref(false)
</script>

<style scoped>
.router-link-exact-active {
  font-weight: bold;
}
</style>