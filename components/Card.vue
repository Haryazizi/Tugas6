<template>
  <div class="drop-shadow mt-6 flex items-center justify-center">
    <div class="p-4 m-8 w-80 bg-white shadow-md rounded-xl">
      <picture class="rounded-lg block overflow-hidden">
        <img
          class="hover:scale-125 ease-in duration-150"
          src="https://sevima.com/wp-content/uploads/2012/11/html5.jpg"
          alt="Sunset in the mountains"
        />
      </picture>
      <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2">{{ nama }}</div>
        <p class="text-gray-700 text-base">{{ deskripsi }}</p>
      </div>
      <div class="px-6 pt-4 pb-2"></div>
    </div>
    <slot />
  </div>
</template>

<script setup>
export default {
  props: {
    nama: {
      type: String,
      default: "HTML",
    },
    deskripsi: {
      type: String,
      default: "Deskripsi",
    },
  },
};
</script>