<template>
  <div class="min-h-screen bg-gradient-to-r from-gray-900 via-gray-800 to-black text-white font-sans flex flex-col">
    <!-- Header Section -->
    <header class="bg-gradient-to-r from-blue-700 to-purple-700 py-16 shadow-xl relative overflow-hidden">
      <div class="container mx-auto text-center flex flex-col items-center relative z-10">
        <!-- Profile Picture -->
        <div class="relative group mb-6">
          <img 
            src="./assets/profil.jpg" 
            alt="Profile Picture" 
            class="w-48 h-48 rounded-full border-4 border-gradient-to-r from-pink-500 to-yellow-500 shadow-2xl object-cover"
          />
          <!-- Animated Check Icon -->
          <span class="absolute bottom-0 right-0 bg-teal-500 text-white p-2 rounded-full shadow-md transition-transform duration-500 ease-in-out transform group-hover:translate-x-1 group-hover:translate-y-1">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 animate-bounce" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
            </svg>
          </span>
        </div>
        <!-- Name and Title -->
        <h1 class="text-6xl font-bold mt-4 text-neon transition-transform duration-500 hover:scale-110">Dhiyaul Haq Ikbar Wisuda</h1>
        <p class="text-lg text-gray-300">Full-Stack Developer | UI/UX Designer</p>
        <!-- Social Links -->
      </div>
      <div class="absolute inset-0 bg-gradient-to-t from-transparent via-blue-900 to-black opacity-50"></div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 py-16 flex-grow">
      <!-- About Me Section -->
      <section class="mb-16">
        <h2 class="text-4xl font-semibold mb-6 text-transparent bg-clip-text bg-gradient-to-r from-teal-400 to-blue-500 animate-fade-in">About Me</h2>
        <p class="text-lg leading-relaxed text-gray-300">
          Saya adalah seorang mahasiswa di Universitas Brawijaya yang mengambil program studi Teknologi Informasi. 
          Saya banyak mempelajari hal yang berkaitan dengan website, jaringan, dan lainnya. Beberapa yang sedang saya pelajari adalah Basis Data, Framework, Algoritma Pemrograman,
          Pemrograman Berbasis Objek, Jaringan Komputer, UI/UX, dan lain sebagainya.
        </p>
      </section>

      <!-- Skills Section -->
      <section class="mb-16">
        <h2 class="text-4xl font-semibold mb-6 text-transparent bg-clip-text bg-gradient-to-r from-teal-400 to-blue-500">Skills</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
            <h3 class="text-xl font-semibold">JavaScript</h3>
            <p>Advanced</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
            <h3 class="text-xl font-semibold">C++</h3>
            <p>Intermediate</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
            <h3 class="text-xl font-semibold">Node.js</h3>
            <p>Intermediate</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
            <h3 class="text-xl font-semibold">Figma</h3>
            <p>Intermediate</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
            <h3 class="text-xl font-semibold">Tailwind CSS</h3>
            <p>Intermediate</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
            <h3 class="text-xl font-semibold">HTML</h3>
            <p>Intermediate</p>
          </div>
        </div>
      </section>

      <!-- Experience Section -->
      <section class="mb-16">
        <h2 class="text-4xl font-semibold mb-6 text-transparent bg-clip-text bg-gradient-to-r from-teal-400 to-blue-500">Experience</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
            <h3 class="text-xl font-semibold">Praktikum Dasar Pemrograman</h3>
            <span class="block text-gray-400">2022</span>
            <p>Membuat Web data diri menggunakan PHP, HTML, CSS.</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
            <h3 class="text-xl font-semibold">UI/UX Designer</h3>
            <span class="block text-gray-400">2024</span>
            <p>Mendesign aplikasi pelelangan yang bernama "Bidperfect".</p>
          </div>
        </div>
      </section>

      <!-- Education, Hobbies, and Languages Section -->
      <section class="mb-16 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Education Section -->
        <div>
          <h2 class="text-4xl font-semibold mb-6 text-transparent bg-clip-text bg-gradient-to-r from-teal-400 to-blue-500">Education</h2>
          <div class="space-y-8">
            <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
              <h2 class="text-xl font-semibold">Teknologi Informasi</h2>
              <span class="block text-gray-400">2023 - Present</span>
              <p>Universitas Brawijaya</p><br>
              <h2 class="text-xl font-semibold">Teknik Informatika</h2>
              <span class="block text-gray-400">2022 - 2023</span>
              <p>Universitas Ahmad Dahlan</p>
            </div>
          </div>
        </div>

        <!-- Hobbies Section -->
        <div>
          <h2 class="text-4xl font-semibold mb-6 text-transparent bg-clip-text bg-gradient-to-r from-teal-400 to-blue-500">Hobbies</h2>
          <div class="space-y-8">
            <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
              <h2 class="text-xl font-semibold">Hobi</h2><br>
              <p>Memasak</p> <p>Menyanyi </p> <p>Membaca </p> <p>Membaca</p> <p>Berolahraga</p>
            </div>
          </div>
        </div>

        <!-- Languages Section -->
        <div>
          <h2 class="text-4xl font-semibold mb-6 text-transparent bg-clip-text bg-gradient-to-r from-teal-400 to-blue-500">Languages</h2>
          <div class="space-y-8">
            <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
              <h2 class="text-xl font-semibold">Bahasa Yang Dikuasai</h2><br>
              <p>Bahasa Indonesia (Native)</p> <p>Bahasa Jawa (Fluent)</p> <p>Bahasa Inggris (Intermediate)</p> 
              <p>Bahasa Arab (Intermediate)</p>
             <p>Melayu (Intermediate)</p>
            </div>
          </div>
        </div>
      </section>

      <!-- Contact Section -->
      <section class="mb-16">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <div>
            <h2 class="text-4xl font-semibold mb-6 text-transparent bg-clip-text bg-gradient-to-r from-teal-400 to-blue-500">Contact</h2>
            <div class="space-y-8">
              <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-neon transform transition-transform duration-500 hover:scale-105">
                <h3 class="text-xl font-semibold">Contact Information</h3>
                <p>Email: Wisuda871@gmail.com</p>
                <p>Telepon: +620123456789</p>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>

    <!-- Footer Section -->
    <footer class="bg-gray-800 py-8 text-center shadow-inner">
      <p>&copy; 2024 Dhiyaul Haq Ikbar Wisuda. All rights reserved.</p>
    </footer>
  </div>
</template>
