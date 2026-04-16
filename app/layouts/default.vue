<template>
  <div class="min-h-screen bg-[#F6F5FC] text-[#181B42]">
    <nav class="w-full bg-[#4338A6] px-4 py-4 md:px-8 md:py-5">
      <div class="mx-auto flex w-full max-w-[1240px] items-center justify-between rounded-[5px] bg-[#4338A6]">
        <NuxtLink to="/" class="flex items-center gap-3">
          <img src="~/assets/images/intellitoggle.png" alt="IntelliToggle" class="h-[28px] w-auto md:h-[34px]" />
        </NuxtLink>

        <button class="rounded-md p-2 text-white md:hidden" @click="mobileMenuOpen = !mobileMenuOpen">
          <img src="~/assets/images/menu.png" alt="Menu" class="h-6 w-6" />
        </button>

        <div class="hidden items-center gap-8 md:flex">
          <NuxtLink class="text-[12px] font-medium text-white" to="/">Home</NuxtLink>
          <NuxtLink class="text-[12px] font-medium text-white/95" to="/about">About</NuxtLink>
          <NuxtLink class="text-[12px] font-medium text-white/95" to="/pricing">Pricing</NuxtLink>
        </div>

        <button class="hidden rounded-[6px] bg-[#F9A71E] px-5 py-2 text-[14px] font-semibold text-[#0E1030] md:block">
          Start Sandbox
        </button>
      </div>

      <div v-if="mobileMenuOpen" class="mx-auto mt-4 w-full max-w-[1240px] rounded-lg bg-[#3D3398] p-4 md:hidden">
        <div class="flex flex-col gap-3 text-white">
          <NuxtLink to="/" @click="mobileMenuOpen = false">Home</NuxtLink>
          <NuxtLink to="/about" @click="mobileMenuOpen = false">About</NuxtLink>
          <NuxtLink to="/pricing" @click="mobileMenuOpen = false">Pricing</NuxtLink>
          <button class="mt-2 rounded-[6px] bg-[#F9A71E] px-5 py-2 text-sm font-semibold text-[#0E1030]">Start Sandbox</button>
        </div>
      </div>
    </nav>

    <slot />

    <footer class="bg-[#ECEBF5] px-4 pb-10 pt-8 md:px-8 md:pb-14 md:pt-10">
      <div class="mx-auto w-full max-w-[1240px]">
        <section class="mb-10 rounded-[12px] bg-[url('~/assets/images/bgpattern.png')] bg-cover bg-center px-6 py-8 text-center text-white md:px-8 md:py-10">
          <h2 class="mx-auto max-w-2xl text-2xl font-semibold leading-tight md:text-[40px]">
            Launch Features Confidently With AI Driven Feature Flags
          </h2>
          <p class="mt-2 text-sm text-white/85 md:text-base">Start for free, scale as your team grows</p>
          <div class="mt-6 flex flex-col justify-center gap-3 sm:flex-row">
            <button class="rounded-[6px] bg-[#F9A71E] px-7 py-2.5 text-sm font-semibold text-[#101333]">Start for $1/mo</button>
            <button class="rounded-[6px] border border-[#F9A71E] px-7 py-2.5 text-sm font-semibold text-[#F9A71E]">Join AI Early Access</button>
          </div>
        </section>

        <section class="grid grid-cols-1 gap-8 md:grid-cols-[1.4fr_1fr_1fr_1.2fr]">
          <div>
            <img src="~/assets/images/intellitogggle_footer.png" alt="IntelliToggle" class="mb-4 h-11 w-auto" />
            <p class="max-w-[280px] text-[12px] leading-5 text-[#5B5D6B]">
              IntelliToggle is built by AORTEM, a company focused on powering scalable, multi-platform developer tools.
            </p>
            <img src="~/assets/images/github.png" alt="GitHub" class="mt-4 h-5 w-5" />
          </div>

          <div>
            <h3 class="mb-3 text-[11px] font-semibold text-[#5C5E6D]">Company</h3>
            <ul class="space-y-2 text-[12px] font-medium text-[#202449]">
              <li>Pricing</li>
              <li>Documentation</li>
              <li>About Us</li>
            </ul>
          </div>

          <div>
            <h3 class="mb-3 text-[11px] font-semibold text-[#5C5E6D]">Resources</h3>
            <ul class="space-y-2 text-[12px] font-medium text-[#202449]">
              <li>Why IntelliToggle is different</li>
              <li>Customer Support</li>
              <li>Terms & Conditions</li>
              <li>Privacy Policy</li>
            </ul>
          </div>

          <div>
            <h3 class="mb-3 text-[11px] font-semibold text-[#202449]">Subscribe to Newsletter</h3>
            <div class="flex overflow-hidden rounded-[4px] border border-[#D5D7E6] bg-white">
              <input type="email" placeholder="Enter email address" class="w-full px-3 py-2 text-[10px] outline-none placeholder:text-[#A2A4B2]" />
              <button class="bg-[#F9A71E] px-5 text-[10px] font-semibold text-[#101333]">Join</button>
            </div>
          </div>
        </section>
      </div>
    </footer>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const mobileMenuOpen = ref(false)
</script>
