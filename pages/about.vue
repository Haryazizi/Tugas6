<template>
  <div class="mx-auto max-w-5xl px-6 py-16 text-center">
    <div class="flex flex-col items-center justify-center">
      <h2 class="text-3xl font-semibold text-gray-800">About Us</h2>
      <div class="w-24 border-b-4 border-yellow-400"></div>
    </div>
    <p class="mt-4 text-gray-600">
      Website yang mempelajari dasar fornt end dengan tahapan mulai dari
      mempelajari HTML, CSS, JavaScript.
    </p>

    <img
      class="mt-16 h-80 w-full rounded-md object-cover object-center shadow"
      src="https://sevima.com/wp-content/uploads/2012/11/html5.jpg"
    />
    <h2 class="text-3xl font-semibold text-gray-800">Back</h2>

    <router-link
      :to="{ name: 'user', params: { id: '1' } }"
      class="text-blue-500 hover:underline"
      >user</router-link
    >

    <p>
      <NuxtLink to="/" class="text-blue-500 underline">Home page</NuxtLink>
    </p>
  </div>
</template>

<script>
import tailwindConfig from "~tailwind.config";

export default {
  data() {
    return {
      tailwindConfig,
    };
  },
};
</script>