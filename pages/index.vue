<script setup>
// import NavBar from "~/components/NavBar.vue";
</script>

<template>
  <div class="h-screen w-full bg-white/60 p-6">
    <div class="flex items-center justify-center h-full w-full p-3">
      <div
        class="flex flex-col justify-center items-center gap-2 p-5 md:w-[40%] w-full"
      >
        <div class="flex flex-col text-center">
          <div class="p-1 mb-5">
            <h1 class="text-7xl font-extrabold">Romeo</h1>
          </div>
          <p class="text-sm text-black/70">(C3R0).</p>
        </div>
        <div
          class="p-1 rounded-full border border-black/10 bg-gray-50 text-center text-black/80 w-48 mb-8"
        >
          <p>Web Developer</p>
        </div>
        <div class="flex items-center justify-center space-x-10 p-5">
          <div
            class="-rotate-6 h-68 md:w-54 w-40 p-3 border border-black/20 shadow-sm rounded-2xl"
          ></div>
          <div
            class="rotate-6 h-68 md:w-54 w-40 p-3 border border-black/20 shadow-sm rounded-2xl"
          ></div>
        </div>
      </div>
    </div>
  </div>
</template>
