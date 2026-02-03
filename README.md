# Jaya-Mandiri
Jasa buang puing
<!DOCTYPE h6ftml>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jaya Mandiri | Jasa Buang Puing & Sampah Proyek</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/dist/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .hero-gradient {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1541888946425-d81bb19240f5?q=80&w=2070&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header / Navbar -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fas fa-truck-pickup text-orange-600 text-2xl"></i>
                <span class="text-xl font-bold tracking-tight">JAYA MANDIRI</span>
            </div>
            <div class="hidden md:flex space-x-6 font-medium">
                <a href="#beranda" class="hover:text-orange-600 transition">Beranda</a>
                <a href="#layanan" class="hover:text-orange-600 transition">Layanan</a>
                <a href="#tentang" class="hover:text-orange-600 transition">Tentang Kami</a>
                <a href="#kontak" class="hover:text-orange-600 transition">Kontak</a>
            </div>
            <a href="https://wa.me/6282188885773" class="bg-green-500 hover:bg-green-600 text-white px-4 py-2 rounded-full flex items-center transition">
                <i class="fab fa-whatsapp mr-2 text-lg"></i> Hubungi Kami
            </a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="beranda" class="hero-gradient h-[600px] flex items-center justify-center text-center text-white px-4">
        <div class="max-w-3xl">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-4">Puing Menumpuk? Kami Solusinya!</h1>
            <p class="text-lg md:text-xl mb-8 opacity-90">Jasa buang puing bangunan, sampah proyek, dan bongkaran rumah profesional di Jabodetabek. Cepat, Bersih, dan Terpercaya.</p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="https://wa.me/6282188885773" class="bg-orange-600 hover:bg-orange-700 text-white text-lg font-bold px-8 py-4 rounded-lg shadow-lg transition">
                    Pesan Jasa Sekarang
                </a>
                <a href="#layanan" class="bg-white text-gray-900 text-lg font-bold px-8 py-4 rounded-lg hover:bg-gray-100 transition">
                    Lihat Layanan
                </a>
            </div>
        </div>
    </section>

    <!-- Kenapa Memilih Kami -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-12">Mengapa Memilih Jaya Mandiri?</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-6 bg-gray-50 rounded-xl">
                    <div class="w-16 h-16 bg-orange-100 text-orange-600 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-bolt text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Respon Cepat</h3>
                    <p class="text-gray-600">Tim kami siap meluncur ke lokasi segera setelah Anda melakukan pemesanan.</p>
                </div>
                <div class="p-6 bg-gray-50 rounded-xl">
                    <div class="w-16 h-16 bg-orange-100 text-orange-600 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-hand-holding-usd text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Harga Kompetitif</h3>
                    <p class="text-gray-600">Tarif transparan dan terjangkau untuk pembersihan puing skala kecil maupun besar.</p>
                </div>
                <div class="p-6 bg-gray-50 rounded-xl">
                    <div class="w-16 h-16 bg-orange-100 text-orange-600 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-broom text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Kerja Bersih</h3>
                    <p class="text-gray-600">Kami menjamin lokasi proyek Anda kembali rapi dan bersih dari sisa material.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Layanan -->
    <section id="layanan" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold">Layanan Kami</h2>
                <p class="text-gray-600 mt-2">Solusi lengkap untuk limbah konstruksi Anda.</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Item 1 -->
                <div class="bg-white rounded-lg overflow-hidden shadow hover:shadow-xl transition">
                    <img src="https://images.unsplash.com/photo-1590059132213-f915228ec3e8?auto=format&fit=crop&q=60&w=400" alt="Buang Puing" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h4 class="font-bold text-lg mb-2">Buang Puing Bangunan</h4>
                        <p class="text-sm text-gray-600">Sisa semen, batu bata, keramik, dan beton dari renovasi.</p>
                    </div>
                </div>
                <!-- Item 2 -->
                <div class="bg-white rounded-lg overflow-hidden shadow hover:shadow-xl transition">
                    <img src="https://images.unsplash.com/photo-1532996122724-e3c354a0b15b?auto=format&fit=crop&q=60&w=400" alt="Sampah Proyek" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h4 class="font-bold text-lg mb-2">Sampah Proyek</h4>
                        <p class="text-sm text-gray-600">Plastik cor, potongan kayu, besi bekas, dan sampah umum proyek.</p>
                    </div>
                </div>
                <!-- Item 3 -->
                <div class="bg-white rounded-lg overflow-hidden shadow hover:shadow-xl transition">
                    <img src="https://images.unsplash.com/photo-1589939705384-5185137a7f0f?auto=format&fit=crop&q=60&w=400" alt="Urugan" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h4 class="font-bold text-lg mb-2">Pengadaan Tanah Urug</h4>
                        <p class="text-sm text-gray-600">Menyediakan tanah merah atau puing bersih untuk urugan lahan.</p>
                    </div>
                </div>
                <!-- Item 4 -->
                <div class="bg-white rounded-lg overflow-hidden shadow hover:shadow-xl transition">
                    <img src="https://images.unsplash.com/photo-1503387762-592dec5832f2?auto=format&fit=crop&q=60&w=400" alt="Bongkaran" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h4 class="font-bold text-lg mb-2">Jasa Bongkaran</h4>
                        <p class="text-sm text-gray-600">Bongkar dinding, lantai, atau bangunan kecil secara total.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Galeri/Portfolio -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-8 text-center">Dokumentasi Kerja</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <div class="aspect-square bg-gray-200 rounded-lg overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1581094794329-c8112a89af12?auto=format&fit=crop&q=60&w=400" class="w-full h-full object-cover grayscale hover:grayscale-0 transition duration-500">
                </div>
                <div class="aspect-square bg-gray-200 rounded-lg overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&q=60&w=400" class="w-full h-full object-cover grayscale hover:grayscale-0 transition duration-500">
                </div>
                <div class="aspect-square bg-gray-200 rounded-lg overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1621905252507-b354bcadcabc?auto=format&fit=crop&q=60&w=400" class="w-full h-full object-cover grayscale hover:grayscale-0 transition duration-500">
                </div>
                <div class="aspect-square bg-gray-200 rounded-lg overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1429497419816-9ca5cfb4571a?auto=format&fit=crop&q=60&w=400" class="w-full h-full object-cover grayscale hover:grayscale-0 transition duration-500">
                </div>
            </div>
        </div>
    </section>

    <!-- CTA & Kontak -->
    <section id="kontak" class="py-16 bg-orange-600 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-4">Konsultasi & Penawaran Gratis</h2>
            <p class="text-xl mb-8">Kirim foto lokasi Anda ke WhatsApp untuk mendapatkan estimasi harga tercepat.</p>
            <div class="flex flex-col items-center space-y-4">
                <a href="https://wa.me/6282188885773" class="bg-white text-orange-600 px-10 py-5 rounded-full text-2xl font-bold shadow-2xl hover:scale-105 transition transform flex items-center">
                    <i class="fab fa-whatsapp mr-3 text-3xl"></i> 0821-8888-5773
                </a>
                <p class="text-orange-200">Melayani area: Jakarta, Bekasi, Tangerang, Depok, Bogor.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-10">
        <div class="container mx-auto px-4 text-center">
            <div class="flex justify-center items-center space-x-2 mb-4 text-white">
                <i class="fas fa-truck-pickup text-xl"></i>
                <span class="text-lg font-bold">JAYA MANDIRI</span>
            </div>
            <p class="max-w-md mx-auto mb-6 text-sm">
                Spesialis jasa pembersihan puing bangunan dan limbah konstruksi. Kami membantu Anda menciptakan area proyek yang bersih dan tertata.
            </p>
            <div class="border-t border-gray-800 pt-8 mt-8">
                <p>&copy; 2024 Jaya Mandiri. Hak Cipta Dilindungi.</p>
            </div>
        </div>
    </footer>

    <!-- Floating WA Button (Mobile) -->
    <a href="https://wa.me/6282188885773" class="fixed bottom-6 right-6 bg-green-500 text-white w-16 h-16 rounded-full flex items-center justify-center text-3xl shadow-2xl z-50 md:hidden animate-bounce">
        <i class="fab fa-whatsapp"></i>
    </a>

</body>
</html>
