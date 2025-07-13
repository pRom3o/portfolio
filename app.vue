<script setup>
useHead({
  link: [
    {
      rel: "icon",
      type: "image/x-icon",
      href: "/ar_icon.png", // or /my-icon.png
    },
  ],
  link: [
    {
      rel: "stylesheet",
      href: "https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap",
    },
  ],
});
</script>

<template>
  <div>
    <NuxtLayout />
  </div>
</template>
