<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PT Rudi Apriadi Lifiah</title>
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
  </style>
</head>
<body class="bg-white text-gray-800">

  <!-- Navbar -->
  <nav class="bg-green-700 text-white p-4 shadow-md z-20 relative">
    <div class="container mx-auto flex justify-between items-center">
      <div class="flex items-center space-x-4">
        <img src="LOGO PT RUDI APRIADI.jpg" alt="Logo PT" class="w-10 h-10 rounded-full bg-white p-1" />
        <h1 class="text-xl font-bold">PT RUDI APRIADI LIFIAH</h1>
      </div>
      <ul class="flex space-x-6">
        <li><a href="#beranda" class="hover:underline">Beranda</a></li>
        <li><a href="#tentang" class="hover:underline">Tentang Kami</a></li>
        <li><a href="#visi-misi" class="hover:underline">Visi & Misi</a></li>
        <li><a href="#produk" class="hover:underline">Produk</a></li>
        <li><a href="#kontak" class="hover:underline">Kontak</a></li>
      </ul>
    </div>
  </nav>

  <!-- Beranda (Video Background Bergerak) -->
  <section id="beranda" class="relative h-screen overflow-hidden text-center text-white">
    <video autoplay muted loop playsinline class="absolute inset-0 object-cover w-full h-full brightness-75">
      <source src="https://cdn.pixabay.com/video/2019/06/05/24187-345599154_tiny.mp4" type="video/mp4" />
      Maaf, browser Anda tidak mendukung video.
    </video>
    <div class="relative z-10 flex items-center justify-center h-full px-4">
      <div class="max-w-3xl bg-black bg-opacity-60 p-6 rounded leading-relaxed">
        <h2 class="text-4xl font-bold mb-2">Selamat Datang di PT RUDI APRIADI LIFIAH</h2>
        <p class="text-lg">Distributor Resmi PT Pupuk Indonesia untuk kebutuhan pertanian nasional.</p>
      </div>
    </div>
  </section>

  <!-- Tentang Kami -->
  <section id="tentang" class="relative py-10 px-4 md:px-16 text-white">
    <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1576765607924-c53aa244385b?auto=format&fit=crop&w=1470&q=80')] bg-cover bg-center brightness-75"></div>
    <div class="relative z-10 bg-black bg-opacity-60 p-6 rounded leading-relaxed">
      <h2 class="text-2xl font-bold mb-3">Tentang Kami</h2>
      <p>
        PT Rudi Apriadi Lifiah adalah perusahaan distribusi resmi yang bekerja sama dengan PT Pupuk Indonesia
        untuk menyalurkan berbagai jenis pupuk unggulan ke seluruh wilayah Indonesia. Kami berdedikasi untuk mendukung
        pertanian yang berkelanjutan dan meningkatkan hasil panen petani melalui produk berkualitas dan layanan terbaik.
      </p>
    </div>
  </section>

  <!-- Visi & Misi -->
  <section id="visi-misi" class="relative py-10 px-4 md:px-16 text-white">
    <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1528314070841-36dbb6e3c5f2?auto=format&fit=crop&w=1470&q=80')] bg-cover bg-center brightness-75"></div>
    <div class="relative z-10 bg-black bg-opacity-60 p-6 rounded leading-relaxed">
      <h2 class="text-2xl font-bold mb-3">Visi & Misi</h2>
      <div class="mb-4">
        <h3 class="text-xl font-semibold mb-1">Visi</h3>
        <p>
          Menjadi Perusahaan Dagang Terpercaya dan Terkemuka serta Mempunyai Akses Sumber dan Jaringan Pemasaran di Dalam dan Luar Negeri.
        </p>
      </div>
      <div>
        <h3 class="text-xl font-semibold mb-1">Misi</h3>
        <ol class="list-decimal pl-5 space-y-1">
          <li>Melakukan Perdagangan Umum dan Khusus yang menangani beraneka ragam produk-produk pertanian dari hulu hingga hilir secara komersial dan terukur.</li>
          <li>Melaksanakan transaksi perdagangan lokal maupun lintas negara.</li>
          <li>Melakukan produksi barang-barang yang mendukung perdagangan.</li>
          <li>Menjalin kemitraan dengan layanan yang terintegrasi dengan memanfaatkan jaringan dan sistem Teknologi Informasi yang handal.</li>
        </ol>
      </div>
    </div>
  </section>

  <!-- Produk -->
  <section id="produk" class="relative py-10 px-4 md:px-16 text-white">
    <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1586771107445-d3ca888129ff?auto=format&fit=crop&w=1470&q=80')] bg-cover bg-center brightness-75"></div>
    <div class="relative z-10 bg-black bg-opacity-60 p-6 rounded">
      <h2 class="text-2xl font-bold mb-3 leading-snug">Produk Kami</h2>
      <ul class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <li class="bg-white text-black bg-opacity-90 backdrop-blur rounded-lg p-4 shadow hover:shadow-md">
          <h3 class="font-semibold text-xl mb-1">Urea</h3>
          <p class="leading-relaxed">Pupuk nitrogen tinggi untuk pertumbuhan tanaman.</p>
        </li>
        <li class="bg-white text-black bg-opacity-90 backdrop-blur rounded-lg p-4 shadow hover:shadow-md">
          <h3 class="font-semibold text-xl mb-1">NPK</h3>
          <p class="leading-relaxed">Gabungan nutrisi penting: Nitrogen, Fosfor, dan Kalium.</p>
        </li>
        <li class="bg-white text-black bg-opacity-90 backdrop-blur rounded-lg p-4 shadow hover:shadow-md">
          <h3 class="font-semibold text-xl mb-1">ZA</h3>
          <p class="leading-relaxed">Pupuk yang membantu pembentukan protein dan klorofil.</p>
        </li>
      </ul>
    </div>
  </section>

  <!-- Kontak -->
  <section id="kontak" class="relative py-10 px-4 md:px-16 text-white">
    <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1611600974643-14cd6d91d5dc?auto=format&fit=crop&w=1470&q=80')] bg-cover bg-center brightness-75"></div>
    <div class="relative z-10 bg-black bg-opacity-60 p-6 rounded leading-relaxed">
      <h2 class="text-2xl font-bold mb-3">Hubungi Kami</h2>
      <p class="mb-2">Untuk pemesanan atau informasi lebih lanjut, silakan hubungi:</p>
      <ul class="space-y-1">
        <li>📞 Telp/WA: <strong>0812-7350-7143</strong></li>
        <li>📧 Email: <strong>ptrudiapriadilifiah1990@gmail.com</strong></li>
        <li>🏢 Alamat: Jl. Palembang-Betung KM 16 No. 90 H, Kelurahan Tanah Mas, Palembang - Sumatra Selatan</li>
      </ul>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-green-700 text-white text-center py-4">
    <p>&copy; 2025 PT Rudi Apriadi Lifiah. Seluruh hak cipta dilindungi.</p>
  </footer>

</body>
</html>
