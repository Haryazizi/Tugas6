<template>
  <div class="flex flex-nowrap">
    <div>
      HTML Merupakan Hypertext Markup Language adalah bahasa markup standar
      untuk membuat halaman website. Terdiri dari kode tag-tag, HTML berfungsi
      membuat strukur website hingga menyusun format teks dan gambar pada
      halaman web.
    </div>
    <div>
      CSS adalah bahasa Cascading Style Sheet dan biasanya digunakan untuk
      mengatur tampilan elemen yang tertulis dalam bahasa markup, seperti HTML.
      CSS berfungsi untuk memisahkan konten dari tampilan visualnya di situs.
    </div>
    <div>
      JavaScript adalah bahasa pemrograman yang digunakan dalam pengembangan
      website agar lebih dinamis dan interaktif pada html dan css, JavaScript
      itu sendiri bisa meninkatkan fungsionalitas dari web.
    </div>
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