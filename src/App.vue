<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <div class="min-h-screen font-poppins flex flex-col bg-soft text-gray-800">
    <!-- Navbar -->
    <header class="bg-white shadow sticky top-0 z-50">
      <div class="container mx-auto px-4 py-4 flex justify-between items-center">
        <h1 class="text-2xl font-bold text-blue-600">CodeMart</h1>
        <nav class="space-x-4">
          <a href="#" class="hover:text-blue-600">Beranda</a>
          <a href="#products" class="hover:text-blue-600">Produk</a>
          <a href="#contact" class="hover:text-blue-600">Kontak</a>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-blue-500 to-indigo-600 text-white py-20 text-center">
      <div class="container mx-auto px-4">
        <h2 class="text-4xl md:text-5xl font-bold mb-4">Jual Source Code Siap Pakai</h2>
        <p class="text-lg mb-6">
          Solusi cepat dan hemat untuk project sekolah, kampus, atau usaha digital Anda.
        </p>
        <a
          href="#products"
          class="bg-white text-blue-600 font-semibold px-6 py-3 rounded-full hover:bg-gray-100 transition"
        >
          Lihat Produk
        </a>
      </div>
    </section>

    <!-- Produk Section -->
    <section id="products" class="py-16">
      <div class="container mx-auto px-4">
        <h3 class="text-2xl font-bold text-center mb-10">Source Code Tersedia</h3>
        <div class="grid md:grid-cols-3 gap-8">
          <div class="bg-white p-6 rounded-2xl shadow hover:shadow-lg transition">
            <div class="aspect-[4/3] overflow-hidden rounded mb-4">
              <img
                src="/images/produk.png"
                alt="Aplikasi Kasir"
                class="w-full h-full object-cover"
              />
            </div>

            <!-- Kategori -->
            <div class="mb-4">
              <span class="bg-blue-100 text-blue-600 text-xs font-semibold px-3 py-1 rounded-full">
                Web Application
              </span>
            </div>

            <h4 class="text-xl font-semibold mb-2">Aplikasi Kasir (POS)</h4>
            <p class="mb-4 text-sm">
              Built with Laravel + Vue. Fitur lengkap, responsive dan cocok untuk UMKM.
            </p>
            <span class="font-bold text-blue-600 block mb-2">Rp150.000</span>
            <button class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">
              Beli Sekarang
            </button>
          </div>
          <div class="bg-white p-6 rounded-2xl shadow hover:shadow-lg transition">
            <div class="aspect-[4/3] overflow-hidden rounded mb-4">
              <img
                src="/images/produk.png"
                alt="Aplikasi Kasir"
                class="w-full h-full object-cover"
              />
            </div>

            <!-- Kategori -->
            <div class="mb-4">
              <span class="bg-blue-100 text-blue-600 text-xs font-semibold px-3 py-1 rounded-full">
                Web Application
              </span>
            </div>

            <h4 class="text-xl font-semibold mb-2">Aplikasi Kasir (POS)</h4>
            <p class="mb-4 text-sm">
              Built with Laravel + Vue. Fitur lengkap, responsive dan cocok untuk UMKM.
            </p>
            <span class="font-bold text-blue-600 block mb-2">Rp150.000</span>
            <button class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">
              Beli Sekarang
            </button>
          </div>
          <div class="bg-white p-6 rounded-2xl shadow hover:shadow-lg transition">
            <div class="aspect-[4/3] overflow-hidden rounded mb-4">
              <img
                src="/images/produk.png"
                alt="Aplikasi Kasir"
                class="w-full h-full object-cover"
              />
            </div>

            <!-- Kategori -->
            <div class="mb-4">
              <span class="bg-blue-100 text-blue-600 text-xs font-semibold px-3 py-1 rounded-full">
                Web Application
              </span>
            </div>

            <h4 class="text-xl font-semibold mb-2">Aplikasi Kasir (POS)</h4>
            <p class="mb-4 text-sm">
              Built with Laravel + Vue. Fitur lengkap, responsive dan cocok untuk UMKM.
            </p>
            <span class="font-bold text-blue-600 block mb-2">Rp150.000</span>
            <button class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">
              Beli Sekarang
            </button>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="bg-gray-200 text-center py-6 mt-auto">
      <p class="text-sm">© 2025 CodeMart. WhatsApp: 08xx-xxxx-xxxx</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>
