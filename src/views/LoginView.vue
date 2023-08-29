<script setup lang="ts">
import { PhEye, PhEyeClosed } from '@phosphor-icons/vue'
import { ref } from 'vue'

const isVisible = ref(false)
</script>
<template>
  <main class="py-20 px-20 bg-[#F6F6F6]">
    <form
      class="grid grid-cols-5 border border-[#CCCCCC] max-w-7xl mx-auto gap-5 p-5 bg-white shadow rounded"
    >
      <div
        class="bg-primary h-full p-10 col-span-2 overflow-hidden relative flex flex-col gap-8 rounded"
      >
        <img src="../assets/logo.svg" alt="Logo" class="w-14 self-center" />
        <div class="relative z-10">
          <div class="text-3xl text-white font-medium">Hello Welcome!</div>
          <div class="text-white/90">Exploring amazing news around the world!</div>
        </div>
        <img src="../assets/illustration.svg" class="w-full z-0" alt="" />
      </div>
      <div class="border border-[#CCCCCC] p-10 flex flex-col gap-8 col-span-3 rounded">
        <div>
          <div class="text-3xl font-medium">Login</div>
          <div class="text-black/70">Please enter your details below to continue</div>
        </div>
        <div class="flex flex-col gap-5">
          <div
            class="flex items-center border border-[#CCCCCC] focus-within:ring ring-primary/10 rounded"
          >
            <input
              type="email"
              placeholder="Email address"
              class="py-4 px-4 bg-transparent flex-1 focus:outline-none"
            />
          </div>
          <div
            class="flex items-center border border-[#CCCCCC] focus-within:ring ring-primary/10 rounded relative"
          >
            <input
              type="password"
              placeholder="Password"
              class="py-4 px-4 bg-transparent flex-1 focus:outline-none"
            />
            <PhEye
              :onclick="() => (isVisible = false)"
              v-if="isVisible"
              color="#B60044"
              size="16"
              class="mx-4 absolute right-0 cursor-pointer"
            />
            <PhEyeClosed
              :onclick="() => (isVisible = true)"
              v-else
              color="#B60044"
              size="16"
              class="mx-4 absolute right-0 cursor-pointer"
            />
          </div>
          <RouterLink to="/" class="self-end text-primary font-medium">Forgot Password?</RouterLink>
          <button class="bg-primary p-4 px-12 text-[#E9D800] w-1/2 rounded">Login</button>
          <RouterLink to="/signup" class="text-primary font-medium"
            >Don't have an account? Create an account</RouterLink
          >
        </div>
      </div>
    </form>
  </main>
</template>
