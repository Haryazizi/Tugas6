<template>
  <section class="container mx-auto mt-20">
    <div class="mb-12 flex flex-col items-center justify-center">
      <h2 class="text-3xl font-semibold text-gray-800">Our Blog</h2>
    </div>
    <div class="flex flex-nowrap">
      <div class="relative mx-6">
        <div class="rounded-lg bg-white shadow-md">
          <img
            src="https://www.nurulfikri.com/wp-content/uploads/2019/11/logo-2582748_960_720.png"
            class="w-full rounded-t-lg"
          />
          <div class="p-6">
            <h2 class="mb-2 text-2xl font-medium text-gray-800">HTML</h2>
            <a href="#" class="text-base text-yellow-600">Read More </a>
          </div>
        </div>
      </div>

      <div class="relative mx-100">
        <div class="rounded-lg bg-white shadow-md">
          <img
            src="https://cdn.pixabay.com/photo/2017/08/05/11/16/logo-2582747_960_720.png"
            class="w-full rounded-t-lg"
          />
          <div class="p-6">
            <h2 class="mb-2 text-2xl font-medium text-gray-800">CSS</h2>
            <a href="#" class="text-base text-yellow-600">Read More </a>
          </div>
        </div>
      </div>

      <div class="relative mx-6">
        <div class="rounded-lg bg-white shadow-md">
          <img
            src="https://www.warnborough.online/wp-content/uploads/2018/09/javascript-2189147_960_720.png"
            class="w-full rounded-t-lg"
          />
          <div class="p-6">
            <h2 class="mb-2 text-2xl font-medium text-gray-800">JavaScript</h2>
            <NuxtLink to="/content" href="#" class="text-base text-yellow-600"
              >Read More
            </NuxtLink>
          </div>
        </div>
      </div>
    </div>

    <p>User ID: {{ $route.params.id }}</p>
    <router-link to="/about" class="text-blue-500 hover:underline"
      >Back to About Page</router-link
    >

    <p>
      <NuxtLink to="/" class="text-blue-500 underline">Home page</NuxtLink>
    </p>
  </section>
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