<template>
  <div class="container mx-auto flex flex-col items-center pb-10">
    <h1 class="text-base font-semi-bold mb-auto">Hary</h1>
    <h1 class="text-base font-semi-bold mb-10">haryazizi44@gmail.com</h1>
    <p>User ID: {{ $route.params.id }}</p>
    <router-link to="/about" class="text-blue-500 hover:underline"
      >Back to About</router-link
    >
    <p>
      <NuxtLink to="/" class="text-blue-500 underline">Home page</NuxtLink>
    </p>
  </div>
</template>
