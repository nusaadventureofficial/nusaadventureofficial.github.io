<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nusa Adventure - Open Trip & Private Trip</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body class="bg-gray-100 font-sans">
  <!-- Hero Section -->
  <section class="bg-cover bg-center h-screen" style="background-image: url('https://source.unsplash.com/featured/?mountain,hiking');">
    <div class="bg-black bg-opacity-60 h-full flex flex-col justify-center items-center text-white text-center px-4" data-aos="fade-in">
      <h1 class="text-4xl md:text-6xl font-bold mb-4">Ciptakan kenangan, Rasakan Petualangan</h1>
      <p class="text-lg md:text-xl mb-6">Bersama Nusa Adventure, jelajahi gunung-gunung terbaik di Jawa Tengah</p>
      <a href="#" id="whatsappBtn" class="bg-yellow-400 hover:bg-yellow-500 text-black font-bold py-3 px-6 rounded-full transition">Daftar Sekarang</a>
    </div>
  </section>

  <!-- Tentang Section -->
  <section class="py-20 px-6 md:px-16 bg-white" data-aos="fade-up">
    <div class="max-w-4xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-4">Kenapa Nusa Adventure?</h2>
      <p class="text-gray-700 text-lg">Kami adalah penyelenggara open trip pendakian yang fokus di kawasan gunung-gunung Jawa Tengah seperti Prau, Slamet, Sindoro, dan Sumbing. Cocok buat kamu yang ingin mendaki tanpa ribet, tinggal berangkat dan nikmati petualangan!</p>
    </div>
  </section>

  <!-- Destinasi Section -->
  <section class="bg-gray-50 py-20 px-6 md:px-16" data-aos="fade-up">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl font-bold text-center mb-12">Destinasi Trip</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Gunung Cards -->
        <div class="bg-white shadow-xl rounded-xl overflow-hidden transform transition duration-500 hover:scale-105">
          <img src="" alt="Gunung Prau" class="w-full h-48 object-cover">
          <div class="p-4">
            <h3 class="text-xl font-semibold mb-2">Gunung Prau</h3>
            <p class="text-gray-600 text-sm">Sunrise dengan view yang sangat cantik & sabana yang indah</p>
          </div>
        </div>
        <div class="bg-white shadow-xl rounded-xl overflow-hidden transform transition duration-500 hover:scale-105">
          <img src="Gambar Nusa Adventure/Slamet.jpg" alt="Gunung Slamet" class="w-full h-48 object-cover">
          <div class="p-4">
            <h3 class="text-xl font-semibold mb-2">Gunung Slamet</h3>
            <p class="text-gray-600 text-sm">Gunung tertinggi di Jawa Tengah</p>
          </div>
        </div>
        <div class="bg-white shadow-xl rounded-xl overflow-hidden transform transition duration-500 hover:scale-105">
          <img src="Gambar Nusa Adventure/Sindoro.jpg" alt="Gunung Sindoro" class="w-full h-48 object-cover">
          <div class="p-4">
            <h3 class="text-xl font-semibold mb-2">Gunung Sindoro</h3>
            <p class="text-gray-600 text-sm">View epik ke Gunung Sumbing</p>
          </div>
        </div>
        <div class="bg-white shadow-xl rounded-xl overflow-hidden transform transition duration-500 hover:scale-105">
          <img src="Gambar Nusa Adventure/Sumbing.jpeg" alt="Gunung Sumbing" class="w-full h-48 object-cover">
          <div class="p-4">
            <h3 class="text-xl font-semibold mb-2">Gunung Sumbing</h3>
            <p class="text-gray-600 text-sm">Rute menantang & pemandangan seperti di Jurassic Park</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Jadwal Trip Section -->
  <section class="py-20 px-6 md:px-16 bg-white" data-aos="fade-up">
    <div class="max-w-5xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-10">Jadwal Trip Terdekat</h2>
      <div class="overflow-x-auto">
        <table class="table-auto w-full text-left border border-gray-200">
          <thead>
            <tr class="bg-yellow-400 text-black">
              <th class="px-4 py-2">Tanggal</th>
              <th class="px-4 py-2">Destinasi</th>
              <th class="px-4 py-2">Kuota Tersisa</th>
              <th class="px-4 py-2">Harga mulai dari</th>
            </tr>
          </thead>
          <tbody>
            <tr class="border-t">
              <td class="px-4 py-2">16-17 Agustus 2025</td>
              <td class="px-4 py-2">Gunung Prau</td>
              <td class="px-4 py-2">12 orang</td>
              <td class="px-4 py-2">Rp320.000</td>
            </tr>
            <tr class="border-t">
              <td class="px-4 py-2">30-31 Agustus 2025</td>
              <td class="px-4 py-2">Gunung Slamet</td>
              <td class="px-4 py-2">12 orang</td>
              <td class="px-4 py-2">Rp350.000</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </section>

  <!-- FAQ Section -->
  <section class="py-20 px-6 md:px-16 bg-gray-100" data-aos="fade-up">
    <div class="max-w-4xl mx-auto">
      <h2 class="text-3xl font-bold text-center mb-12">Pertanyaan yang Sering Diajukan</h2>
      <div class="space-y-8">
        <div>
          <h3 class="font-semibold text-lg">Apa itu Nusa Adventure?</h3>
          <p class="text-gray-700">Nusa Adventure adalah penyelenggara open trip dan private trip ke gunung-gunung di Jawa Tengah. Kami siap mengurus semua kebutuhan trip kamu dari awal sampai akhir.</p>
        </div>
        <div>
          <h3 class="font-semibold text-lg">Apakah trip ini cocok untuk pemula?</h3>
          <p class="text-gray-700">Sangat cocok! Kami menyediakan guide berpengalaman dan itinerary yang sudah disesuaikan agar aman dan nyaman untuk semua kalangan, termasuk pemula.</p>
        </div>
        <div>
          <h3 class="font-semibold text-lg">Apa saja yang termasuk dalam paket?</h3>
          <p class="text-gray-700">Tiket masuk, tenda, guide & porter tim, dokumentasi, dan makan selama trip. Detail bisa kamu cek di setiap itinerary yang kami sediakan saat daftar.</p>
        </div>
        <div>
          <h3 class="font-semibold text-lg">Bagaimana cara mendaftar?</h3>
          <p class="text-gray-700">Cukup klik tombol "Daftar Sekarang" di bagian atas halaman ini. Nanti kamu akan diarahkan langsung ke WhatsApp admin kami untuk info lebih lanjut dan proses pendaftaran.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white py-10">
    <div class="text-center">
      <p class="text-sm">&copy; 2025 Nusa Adventure. All rights reserved.</p>
      <p class="text-sm mt-2">Follow Instagram: <a href="https://instagram.com/nusaadventure" class="underline">@nusaadventure</a></p>
    </div>
  </footer>

  <!-- JavaScript -->
  <script>
    // Inisialisasi AOS
    AOS.init({
      once: true,
      duration: 1000,
    });

    // WhatsApp button logic
    document.getElementById("whatsappBtn").addEventListener("click", function(e) {
      e.preventDefault();
      const nomor = "6283131556354"; // Ganti dengan nomor admin kamu
      const pesan = "Halo kak, saya tertarik untuk ikut open trip Nusa Adventure. Boleh minta info lengkapnya?";
      const link = `https://wa.me/${nomor}?text=${encodeURIComponent(pesan)}`;
      window.open(link, "_blank");
    });
  </script>
</body>
</html>
