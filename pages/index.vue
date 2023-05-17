<template>
  <div>
    <header class="head-title">
      <div
        :class="isOpen ? 'flex' : 'hidden'"
        class="mt-2 flex-col space-y-4 md:mt-0 md:flex md:flex-row md:items-center md:space-y-0 md:space-x-10"
      >
        <a class="transform text-gray-800 hover:text-yellow-400" href="#"
          >Home</a
        >
        <NuxtLink
          to="/about"
          class="transform text-gray-800 hover:text-yellow-400"
          href="#"
          >About</NuxtLink
        >
        <NuxtLink
          to="/blog"
          class="transform text-gray-800 hover:text-yellow-400"
          href="#"
          >Blog</NuxtLink
        >
        <NuxtLink
          to="/content"
          class="transform text-gray-800 hover:text-yellow-400"
          href="#"
          >Content</NuxtLink
        >
        <NuxtLink
          to="/user"
          class="rounded-2xl border bg-gradient-to-b from-yellow-300 to-yellow-500 px-4 py-2 text-center text-white hover:shadow-xl"
          href="#"
          >Contact Us</NuxtLink
        >
      </div>
    </header>

    <section class="bg-gray-200">
      <div class="flex justify-center">
        <div class="px-20 py-32 lg:w-1/2">
          <div class="w-full">
            <h1 class="mb-2 text-4xl font-medium text-gray-900">
              Belajar Dasar Fornt End
            </h1>
            <div class="leading-relaxed">
              Front end merupakan salah satu bagian dari website yang
              menampilkan tampilan untuk para pengguna. Pada bagian ini dibuat
              dengan menggunakan 3 bahasa pemrograman web yaitu HyperText Markup
              Language (HTML), Cascading Style Sheets (CSS), dan JavaScript.
            </div>
            <button
              class="mt-4 rounded-xl bg-gradient-to-b from-yellow-300 to-yellow-500 px-8 py-2 text-xl text-white hover:shadow-2xl"
            >
              Get started
            </button>
          </div>
        </div>
      </div>
    </section>

    <section class="bg-white">
      <NuxtLayout :name="layouts.index">
        <div class="mx-auto max-w-5xl px-6 py-16 text-center">
          <div class="flex flex-col items-center justify-center">
            <h2 class="text-3xl font-semibold text-gray-800">About Us</h2>
          </div>
          <p class="mt-4 text-black-600">Yang harus dipelajari :</p>
          <ul>
            <li>Html</li>
            <li>Css</li>
            <li>JavaScript</li>
          </ul>
        </div>
      </NuxtLayout>
    </section>

    <!-- <section class="container mx-auto mt-20">
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
              <h2 class="mb-2 text-2xl font-medium text-gray-800">
                JavaScript
              </h2>
              <a href="#" class="text-base text-yellow-600">Read More </a>
            </div>
          </div>
        </div>
      </div>
    </section> -->

    <section class="container mx-auto mt-20">
      <div class="mb-12 flex flex-col items-center justify-center">
        <h2 class="text-3xl font-semibold text-gray-800">Penjelasan</h2>
      </div>
    </section>

    <div class="flex flex-nowrap">
      <div class="relative mx-6">
        <div class="rounded-lg bg-white shadow-md">
          <img
            src="https://www.nurulfikri.com/wp-content/uploads/2019/11/logo-2582748_960_720.png"
            class="w-full rounded-t-lg"
          />
          <div class="p-6">
            <h2 class="mb-2 text-2xl font-medium text-gray-800">HTML</h2>
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
          </div>
        </div>
      </div>
    </div>

    <!-- <div class="flex flex-nowrap">
      <div>
        HTML Merupakan Hypertext Markup Language adalah bahasa markup standar
        untuk membuat halaman website. Terdiri dari kode tag-tag, HTML berfungsi
        membuat strukur website hingga menyusun format teks dan gambar pada
        halaman web.
      </div>
      <div>
        CSS adalah bahasa Cascading Style Sheet dan biasanya digunakan untuk
        mengatur tampilan elemen yang tertulis dalam bahasa markup, seperti
        HTML. CSS berfungsi untuk memisahkan konten dari tampilan visualnya di
        situs.
      </div>
      <div>
        JavaScript adalah bahasa pemrograman yang digunakan dalam pengembangan
        website agar lebih dinamis dan interaktif pada html dan css, JavaScript
        itu sendiri bisa meninkatkan fungsionalitas dari web.
      </div>
    </div> -->

    <div class="container mx-auto mt-20">
      <div class="mb-12 flex flex-col items-center justify-center">
        <h2 class="text-3xl font-semibold text-gray-800">Video Penjelasan</h2>
      </div>
    </div>
    <div class="flex items-center justify-center">
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/qzMPvbL3GRQ"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen
      ></iframe>
    </div>

    <Card :nama="nama" :deskripsi="deskripsi"></Card>

    <footer class="bg-gray-100 text-white">
      <div class="container mx-auto flex items-center px-5 py-8">
        <p class="text-sm text-black">
          @haryazizi —
          <a href="#" class="ml-1 text-black" target="_blank"
            >www.instagram.com</a
          >
        </p>
      </div>
    </footer>
  </div>
</template>

<style lang="postcss" scoped>
.badge {
  @apply inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700;
  &:hover {
    @apply bg-gray-300;
  }
}
</style>

<script>
export default {
  data() {
    return {
      nama: "HTML",
      deskripsi:
        "HTML Merupakan Hypertext Markup Language adalah bahasa markup standar",
      layouts: {
        index: "index",
      },
    };
  },
};
</script>

