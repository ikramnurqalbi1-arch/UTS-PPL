<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Portfolio PPL PPG BK - Muhammad Ikram</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=Playfair+Display:ital,wght@0,600;0,700;1,400&display=swap" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['"Plus Jakarta Sans"', 'sans-serif'],
                        serif: ['"Playfair Display"', 'serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
        }
        .logo-container img {
            max-height: 55px;
            width: auto;
            object-fit: contain;
            transition: all 0.3s ease;
        }
        .logo-container img:hover {
            transform: translateY(-3px);
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(229, 231, 235, 0.5);
        }
    </style>
</head>
<body class="bg-[#fafbfe] text-slate-800 antialiased">

    <!-- Navbar -->
    <nav class="bg-white/80 backdrop-blur-md border-b border-slate-100 sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="font-bold text-lg text-teal-600 flex items-center gap-2">
                    <i class="fa-solid fa-graduation-cap text-2xl"></i>
                    <span class="tracking-tight text-slate-900">E-Portfolio<span class="text-teal-600 font-extrabold">.BK</span></span>
                </div>
                <!-- Menu Desktop -->
                <div class="hidden md:flex space-x-8 text-sm font-semibold text-slate-600">
                    <a href="#profil" class="hover:text-teal-600 transition">Profil</a>
                    <a href="#artefak" class="hover:text-teal-600 transition">Artefak PPL</a>
                    <a href="#refleksi" class="hover:text-teal-600 transition">Refleksi Akhir</a>
                    <a href="#filosofi" class="hover:text-teal-600 transition">Filosofi Mengajar</a>
                </div>
                <!-- Tombol Menu Mobile -->
                <button id="mobile-btn" class="md:hidden text-slate-700 text-2xl focus:outline-none">
                    <i class="fa-solid fa-bars-staggered"></i>
                </button>
            </div>
        </div>
        <!-- Menu Mobile -->
        <div id="mobile-menu" class="hidden bg-white border-b border-slate-200 px-4 py-4 space-y-3 md:hidden shadow-lg">
            <a href="#profil" class="block text-slate-700 font-medium hover:text-teal-600">Profil</a>
            <a href="#artefak" class="block text-slate-700 font-medium hover:text-teal-600">Artefak PPL</a>
            <a href="#refleksi" class="block text-slate-700 font-medium hover:text-teal-600">Refleksi Akhir</a>
            <a href="#filosofi" class="block text-slate-700 font-medium hover:text-teal-600">Filosofi Mengajar</a>
        </div>
    </nav>

    <!-- Header / Hero Banner dengan Logo Institusi -->
    <header class="bg-gradient-to-br from-teal-50 via-white to-indigo-50/30 py-16 md:py-24 border-b border-slate-100 text-center px-4 relative overflow-hidden">
        <div class="absolute inset-0 bg-[radial-gradient(#e2e8f0_1px,transparent_1px)] [background-size:16px_16px] opacity-40"></div>
        <div class="max-w-4xl mx-auto relative z-10">
            <!-- Baris Logo Resmi -->
            <div class="logo-container flex flex-wrap justify-center items-center gap-6 md:gap-10 mb-12">
                <img src="Tut-Wuri-Handayani.png" alt="Logo Kemenristekdikti" class="h-14">
                <img src="UNM.png" alt="Logo Universitas Negeri Makassar" class="h-14">
                <img src="PPG-Calon-Guru.png" alt="Logo PPG Calon Guru" class="h-14">
                <img src="DIKTISAINTEK-BERDAMPAS.png" alt="Logo Diktisaintek" class="h-14">
            </div>

            <span class="bg-teal-100/80 text-teal-800 px-4 py-1.5 rounded-full text-xs font-bold tracking-wider uppercase shadow-sm">
                📚 Program PPG Calon Guru LPTK UNM
            </span>
            <h1 class="text-4xl md:text-5xl font-extrabold text-slate-900 mt-6 mb-4 tracking-tight leading-tight">
                E-Portfolio Praktik Pengalaman Lapangan <br>
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-teal-600 to-indigo-600">Bimbingan & Konseling</span>
            </h1>
            <p class="text-slate-600 text-lg max-w-2xl mx-auto mb-8 font-normal">
                Dokumentasi terstruktur, analisis kritis, serta refleksi filosofis pelaksanaan PPL Terbimbing di SMK Negeri 3 Makassar.
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#artefak" class="bg-teal-600 hover:bg-teal-700 text-white px-6 py-3 rounded-xl font-bold shadow-md shadow-teal-100 transition-all flex items-center gap-2">
                    <i class="fa-solid fa-box-archive"></i> Jelajahi Artefak
                </a>
                <a href="#refleksi" class="bg-white hover:bg-slate-50 text-slate-700 border border-slate-200 px-6 py-3 rounded-xl font-bold transition-all flex items-center gap-2">
                    <i class="fa-solid fa-pen-fancy"></i> Baca Refleksi Akhir
                </a>
            </div>
        </div>
    </header>

    <!-- Profil & Pembimbing -->
    <section id="profil" class="py-20 px-4">
        <div class="max-w-5xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-extrabold text-slate-950 tracking-tight">Profil & Informasi Akademik</h2>
                <div class="w-12 h-1.5 bg-teal-500 mx-auto mt-3 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <!-- Foto & Identitas Utama -->
                <div class="lg:col-span-2 bg-white p-8 rounded-3xl border border-slate-100 shadow-sm flex flex-col md:flex-row gap-8 items-center">
                    <div class="relative w-44 h-56 flex-shrink-0">
                        <img src="photo-profil.jpeg" alt="Foto Profil Muhammad Ikram" class="w-full h-full object-cover rounded-2xl shadow-md border-4 border-slate-50">
                        <div class="absolute -bottom-3 -right-3 bg-teal-500 text-white w-8 h-8 rounded-full shadow-lg flex items-center justify-center">
                            <i class="fa-solid fa-check text-xs"></i>
                        </div>
                    </div>
                    
                    <div class="flex-1 text-center md:text-left">
                        <h3 class="text-2xl font-bold text-slate-900 mb-1">Muhammad Ikram, S.Pd.</h3>
                        <p class="text-teal-600 font-semibold mb-6">Mahasiswa PPG Calon Guru BK</p>
                        
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 text-sm text-slate-600">
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-id-badge text-teal-500 w-5"></i>
                                <span><strong>NIM:</strong> 2590204950906</span>
                            </div>
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-university text-teal-500 w-5"></i>
                                <span>LPTK Univ. Negeri Makassar</span>
                            </div>
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-school text-teal-500 w-5"></i>
                                <span>SMK Negeri 3 Makassar</span>
                            </div>
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-envelope text-teal-500 w-5"></i>
                                <span>ikramnurqalbi1@gmail.com</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Kolom DPL & Pamong -->
                <div class="bg-white p-8 rounded-3xl border border-slate-100 shadow-sm flex flex-col justify-between">
                    <div>
                        <h4 class="text-xs font-bold text-slate-400 uppercase tracking-widest mb-4">Pembimbing Praktik</h4>
                        <div class="space-y-4">
                            <div class="flex gap-3">
                                <div class="text-teal-600 text-lg mt-0.5"><i class="fa-solid fa-chalkboard-user"></i></div>
                                <div>
                                    <p class="text-xs text-slate-400">Dosen Pembimbing Lapangan</p>
                                    <p class="font-bold text-slate-800 text-sm">M. Amirullah, M.Pd</p>
                                    <p class="text-xs text-slate-500">NIP. 199205152022031008</p>
                                </div>
                            </div>
                            <hr class="border-slate-100">
                            <div class="flex gap-3">
                                <div class="text-indigo-500 text-lg mt-0.5"><i class="fa-solid fa-user-tie"></i></div>
                                <div>
                                    <p class="text-xs text-slate-400">Guru Pamong</p>
                                    <p class="font-bold text-slate-800 text-sm">Nasratul Khumaerah, S.Pd., Gr., M.Pd</p>
                                    <p class="text-xs text-slate-500">NIP. 198901012022212040</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-100 bg-teal-50/50 p-3 rounded-xl text-xs text-teal-800 flex items-center gap-2">
                        <i class="fa-solid fa-circle-check"></i>
                        <span>Terverifikasi oleh Tim PPG UNM</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Artefak PPL (3 Siklus) -->
    <section id="artefak" class="py-20 bg-slate-50 px-4 border-y border-slate-100">
        <div class="max-w-5xl mx-auto">
            <div class="text-center mb-16">
                <span class="text-xs font-bold uppercase tracking-widest text-teal-600 bg-teal-100/50 px-3 py-1 rounded">Rencana Pelaksanaan Layanan</span>
                <h2 class="text-3xl font-extrabold text-slate-950 mt-4">Artefak Produk Pembelajaran</h2>
                <div class="w-12 h-1.5 bg-teal-500 mx-auto mt-3 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Siklus 1 -->
                <div class="bg-white rounded-3xl border border-slate-200/60 overflow-hidden flex flex-col hover:shadow-lg transition">
                    <div class="bg-teal-600 p-5 text-white">
                        <div class="flex justify-between items-center mb-2">
                            <span class="text-xs font-bold uppercase tracking-wider bg-teal-500 px-2 py-0.5 rounded">Siklus I</span>
                            <span class="text-xs bg-white/20 px-2 py-0.5 rounded-full">Klasikal</span>
                        </div>
                        <h3 class="font-bold text-lg">Layanan Klasikal</h3>
                    </div>
                    <div class="p-6 flex-grow flex flex-col justify-between">
                        <div>
                            <p class="text-xs text-slate-500 mb-3"><strong>Fokus:</strong> Strategi Perencanaan Karir Masa Depan (BMW: Bekerja, Melanjutkan, Wirausaha)</p>
                            <!-- Dokumentasi Gambar Klasikal -->
                            <div class="grid grid-cols-2 gap-2 my-4">
                                <img src="WhatsApp Image 2026-04-16 at 09.07.45.jpeg" alt="Praktik Bimbingan Klasikal 1" class="w-full h-24 object-cover rounded-xl shadow-sm hover:scale-105 transition duration-300">
                                <img src="WhatsApp Image 2026-04-16 at 09.07.45 (1).jpeg" alt="Praktik Bimbingan Klasikal 2" class="w-full h-24 object-cover rounded-xl shadow-sm hover:scale-105 transition duration-300">
                            </div>
                        </div>
                        <a href="RPL Bimbingan Klasikal.pdf" target="_blank" class="bg-teal-50 hover:bg-teal-100 text-teal-700 font-bold py-2.5 px-4 rounded-xl text-sm flex items-center justify-center gap-2 transition">
                            <i class="fa-solid fa-file-pdf"></i> Unduh RPL Klasikal
                        </a>
                    </div>
                </div>

                <!-- Siklus 2 -->
                <div class="bg-white rounded-3xl border border-slate-200/60 overflow-hidden flex flex-col hover:shadow-lg transition">
                    <div class="bg-indigo-600 p-5 text-white">
                        <div class="flex justify-between items-center mb-2">
                            <span class="text-xs font-bold uppercase tracking-wider bg-indigo-500 px-2 py-0.5 rounded">Siklus II</span>
                            <span class="text-xs bg-white/20 px-2 py-0.5 rounded-full">Individual</span>
                        </div>
                        <h3 class="font-bold text-lg">Konseling Individual</h3>
                    </div>
                    <div class="p-6 flex-grow flex flex-col justify-between">
                        <div>
                            <p class="text-xs text-slate-500 mb-4"><strong>Fokus:</strong> Kebingungan rencana karir & peningkatan kemandirian pasca lulus.</p>
                            <div class="bg-indigo-50/50 border border-indigo-100 rounded-xl p-4 text-xs text-indigo-800 mb-6 flex gap-2">
                                <i class="fa-solid fa-circle-info text-sm mt-0.5"></i>
                                <span>Asesmen target konseli dengan skor kemandirian 69% guna perbaikan terstruktur.</span>
                            </div>
                        </div>
                        <a href="rpl-konseling-individual.pdf" target="_blank" class="bg-indigo-50 hover:bg-indigo-100 text-indigo-700 font-bold py-2.5 px-4 rounded-xl text-sm flex items-center justify-center gap-2 transition">
                            <i class="fa-solid fa-file-pdf"></i> Unduh RPL Individual
                        </a>
                    </div>
                </div>

                <!-- Siklus 3 -->
                <div class="bg-white rounded-3xl border border-slate-200/60 overflow-hidden flex flex-col hover:shadow-lg transition">
                    <div class="bg-sky-600 p-5 text-white">
                        <div class="flex justify-between items-center mb-2">
                            <span class="text-xs font-bold uppercase tracking-wider bg-sky-500 px-2 py-0.5 rounded">Siklus III</span>
                            <span class="text-xs bg-white/20 px-2 py-0.5 rounded-full">Kelompok</span>
                        </div>
                        <h3 class="font-bold text-lg">Konseling Kelompok</h3>
                    </div>
                    <div class="p-6 flex-grow flex flex-col justify-between">
                        <div>
                            <p class="text-xs text-slate-500 mb-4"><strong>Fokus:</strong> Efikasi diri karir & kecemasan menghadapi transisi dunia kerja.</p>
                            <div class="bg-sky-50/50 border border-sky-100 rounded-xl p-4 text-xs text-sky-800 mb-6 flex gap-2">
                                <i class="fa-solid fa-circle-info text-sm mt-0.5"></i>
                                <span>Metode diskusi kelompok terfokus dengan penekanan pada dinamika emosi kelompok.</span>
                            </div>
                        </div>
                        <a href="rpl-konseling-kelompok.pdf" target="_blank" class="bg-sky-50 hover:bg-sky-100 text-sky-700 font-bold py-2.5 px-4 rounded-xl text-sm flex items-center justify-center gap-2 transition">
                            <i class="fa-solid fa-file-pdf"></i> Unduh RPL Kelompok
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Refleksi Akhir PPL Terbimbing -->
    <section id="refleksi" class="py-20 px-4">
        <div class="max-w-4xl mx-auto">
            <div class="text-center mb-16">
                <span class="text-xs font-bold uppercase tracking-widest text-teal-600 bg-teal-100/50 px-3 py-1 rounded">Analisis Hasil Belajar</span>
                <h2 class="text-3xl font-extrabold text-slate-950 mt-4">Refleksi Akhir PPL Terbimbing</h2>
                <div class="w-12 h-1.5 bg-teal-500 mx-auto mt-3 rounded-full"></div>
            </div>

            <div class="space-y-8">
                <!-- Aspek 1 -->
                <div class="bg-white p-8 rounded-3xl border border-slate-100 shadow-sm relative overflow-hidden group">
                    <div class="absolute top-0 left-0 w-2 h-full bg-teal-500"></div>
                    <h3 class="text-xl font-bold text-slate-900 mb-4 flex items-center gap-3">
                        <span class="bg-teal-50 text-teal-600 w-8 h-8 rounded-full flex items-center justify-center text-sm font-extrabold">1</span>
                        Apa yang telah dipelajari selama tahapan PPL Terbimbing?
                    </h3>
                    <p class="text-slate-600 leading-relaxed text-sm mb-4">
                        Melalui rangkaian PPL Terbimbing yang dilaksanakan secara sistematis di SMK Negeri 3 Makassar, dari tahapan observasi, asistensi, hingga praktik mandiri terbimbing, saya telah memperoleh pemahaman mendalam mengenai dinamika utuh layanan Bimbingan dan Konseling (BK) di sekolah. Saya belajar bahwa peran guru BK bukan sekadar menegakkan disiplin, melainkan menjadi fasilitator perkembangan psikologis dan akademik peserta didik. Selama proses ini, saya mengintegrasikan tiga bentuk layanan utama, yaitu Layanan Klasikal (Siklus I), Konseling Individual (Siklus II), dan Konseling Kelompok (Siklus III).
                    </p>
                    <p class="text-slate-600 leading-relaxed text-sm">
                        Pada Siklus I, saya mengasah kemampuan merancang dan melaksanakan Layanan Klasikal menggunakan Strategi Perencanaan Karir Masa Depan (BMW: Bekerja, Melanjutkan, Wirausaha). Di sini saya menyadari pentingnya asesmen kebutuhan (<em>need assessment</em>) agar materi yang disampaikan selaras dengan karakteristik siswa SMK. Pada Siklus II, melalui konseling individual, saya belajar mengaplikasikan pendekatan klinis secara humanis untuk membantu siswa mengatasi kebingungan karir dan membangun kemandirian. Terakhir, pada Siklus III, melalui konseling kelompok yang berfokus pada kecemasan masa depan, saya mendalami bagaimana dinamika kelompok dapat memicu <em>vicarious learning</em> (belajar dari pengalaman rekan sebaya), sehingga siswa dapat saling menguatkan di bawah bimbingan konselor.
                    </p>
                </div>

                <!-- Aspek 2 -->
                <div class="bg-white p-8 rounded-3xl border border-slate-100 shadow-sm relative overflow-hidden group">
                    <div class="absolute top-0 left-0 w-2 h-full bg-indigo-500"></div>
                    <h3 class="text-xl font-bold text-slate-900 mb-4 flex items-center gap-3">
                        <span class="bg-indigo-50 text-indigo-600 w-8 h-8 rounded-full flex items-center justify-center text-sm font-extrabold">2</span>
                        Pengalaman yang menantang dan solusi yang diterapkan?
                    </h3>
                    <p class="text-slate-600 leading-relaxed text-sm mb-4">
                        Pengalaman paling menantang yang saya hadapi terjadi pada Siklus II dan Siklus III, di mana tingkat keterbukaan (<em>self-disclosure</em>) peserta didik pada awalnya sangat rendah. Beberapa siswa yang mengikuti sesi konseling individual maupun kelompok cenderung pasif, defensif, dan enggan menceritakan hambatan pribadi atau kecemasan mereka terkait masa depan pasca-lulus dari SMK. Hal ini disebabkan oleh adanya stigma bahwa masuk ke ruang BK berarti melakukan pelanggaran, atau adanya rasa tidak aman untuk membagikan kerentanan diri di depan orang lain.
                    </p>
                    <p class="text-slate-600 leading-relaxed text-sm">
                        Solusi yang saya terapkan adalah mengoptimalkan teknik-teknik dalam pendekatan <strong>Person-Centered Therapy</strong> dari Carl Rogers. Saya secara konsisten menunjukkan sikap empati yang mendalam, menerima siswa tanpa syarat (<em>unconditional positive regard</em>), dan membangun hubungan yang selaras serta jujur (<em>congruence</em>). Sebelum masuk ke inti konseling, saya menginvestasikan waktu untuk membangun rapor (<em>building rapport</em>) melalui <em>ice breaking</em> yang relevan dan menegaskan kembali asas kerahasiaan dalam BK. Ketika siswa mulai merasa bahwa ruang konseling adalah zona aman yang bebas dari penghakiman, mereka secara perlahan mulai terbuka dan aktif mengeksplorasi solusi atas permasalahannya sendiri.
                    </p>
                </div>

                <!-- Aspek 3 -->
                <div class="bg-white p-8 rounded-3xl border border-slate-100 shadow-sm relative overflow-hidden group">
                    <div class="absolute top-0 left-0 w-2 h-full bg-sky-500"></div>
                    <h3 class="text-xl font-bold text-slate-900 mb-4 flex items-center gap-3">
                        <span class="bg-sky-50 text-sky-600 w-8 h-8 rounded-full flex items-center justify-center text-sm font-extrabold">3</span>
                        Umpan balik & saran konstruktif untuk PPL Mandiri selanjutnya?
                    </h3>
                    <p class="text-slate-600 leading-relaxed text-sm mb-4">
                        Dalam diskusi refleksi akhir bersama Dosen Pembimbing Lapangan (DPL) dan Guru Pamong, saya menerima beberapa masukan berharga yang menjadi dasar perbaikan untuk tahapan PPL Mandiri selanjutnya. Masukan-masukan tersebut di antaranya:
                    </p>
                    <ul class="space-y-3 text-slate-600 text-sm">
                        <li class="flex items-start gap-2">
                            <span class="text-teal-500 text-sm mt-0.5"><i class="fa-solid fa-circle-arrow-right"></i></span>
                            <span><strong>Manajemen Waktu:</strong> Pengalokasian waktu 1 x 45 menit dalam layanan kelompok perlu dikelola secara lebih ketat, terutama pada tahap transisi ke tahap inti, agar proses penyimpulan dan pengambilan komitmen tindakan oleh konseli tidak terkesan terburu-buru.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <span class="text-teal-500 text-sm mt-0.5"><i class="fa-solid fa-circle-arrow-right"></i></span>
                            <span><strong>Variasi Media Kreatif:</strong> Untuk layanan klasikal, disarankan untuk lebih mengintegrasikan teknologi interaktif berbasis game atau visualisasi digital yang adaptif terhadap karakteristik siswa SMK generasi Z agar fokus belajar mereka terjaga.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <span class="text-teal-500 text-sm mt-0.5"><i class="fa-solid fa-circle-arrow-right"></i></span>
                            <span><strong>Pendalaman Teknik Konseling:</strong> Saya diharapkan terus mengeksplorasi variasi teknik di luar <em>Person-Centered</em>, seperti pengondisian kognitif (gaya <em>Cognitive Behavior Therapy</em> atau <em>Gestalt Therapy</em>), untuk menghadapi variasi kasus siswa yang lebih kompleks pada PPL Mandiri.</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Filosofi Mengajar -->
    <section id="filosofi" class="py-20 bg-gradient-to-br from-teal-900 via-[#0d2e2b] to-slate-950 text-slate-100 px-4">
        <div class="max-w-3xl mx-auto">
            <div class="text-center mb-12">
                <span class="text-xs font-bold uppercase tracking-widest text-teal-300 bg-teal-800/50 px-3 py-1 rounded">Ideologi Guru BK</span>
                <h2 class="text-3xl font-extrabold text-white mt-4 font-serif">Filosofi Mengajar</h2>
                <div class="w-12 h-1 bg-teal-400 mx-auto mt-3 rounded-full"></div>
            </div>

            <!-- Paragraf 1 -->
            <div class="mb-8 relative">
                <div class="absolute -top-6 -left-6 text-6xl text-teal-700/30 font-serif">“</div>
                <p class="text-teal-100/90 text-md leading-relaxed font-sans mb-6">
                    Filosofi mengajar saya berakar pada keyakinan bahwa setiap peserta didik adalah individu yang unik, utuh, dan memiliki potensi kodrati untuk berkembang secara optimal. Sebagai seorang calon guru Bimbingan dan Konseling, saya tidak memandang tugas saya sebagai bentuk pengajaran instruksional yang berfokus pada transfer kognitif, melainkan sebagai proses menuntun (<em>educere</em>) dan memfasilitasi pertumbuhan pribadi. Saya meyakini bahwa pondasi utama dari pendidikan yang efektif adalah terciptanya rasa aman secara psikologis. Ketika siswa merasa dihargai, didengar, dan dipahami tanpa adanya syarat, mereka akan memiliki keberanian untuk mengenali kelemahan diri sekaligus melejitkan potensi terbaik yang mereka miliki. Ideologi ini menjadi kompas moral dan profesional saya dalam menavigasi setiap interaksi dengan siswa di sekolah.
                </p>
            </div>

            <!-- Paragraf 2 -->
            <div class="mb-8">
                <p class="text-teal-100/90 text-md leading-relaxed font-sans mb-6">
                    Dalam mengimplementasikan prinsip tersebut, saya menyelaraskan diri dengan pemikiran luhur Ki Hadjar Dewantara mengenai konsep "Sistem Among", di mana seorang pendidik harus mampu bertindak sebagai pamong yang membimbing dengan semboyan <em>Ing Ngarso Sung Tulodo, Ing Madyo Mangun Karso, Tut Wuri Handayani</em>. Di dalam ruang bimbingan maupun di lingkungan sekolah, hal ini berarti saya harus menjadi teladan dalam berempati, hadir di tengah-tengah siswa untuk membangun motivasi dan rasa percaya diri mereka, serta memberikan dorongan dari belakang agar mereka mampu mengambil keputusan karir dan pribadi secara mandiri. Peran ini menuntut saya untuk melepaskan otoritas kediktatoran dan menggantinya dengan kemitraan yang setara, membantu siswa SMK mengarahkan jalan hidup mereka secara bertanggung jawab, baik untuk bekerja, melanjutkan studi, maupun berwirausaha.
                </p>
            </div>

            <!-- Paragraf 3 -->
            <div class="mb-10">
                <p class="text-teal-100/90 text-md leading-relaxed font-sans">
                    Secara teoretis, filosofi mengajar dan pelayanan saya ini didukung kuat oleh konsep <strong>Growth Mindset</strong> yang dikembangkan oleh Carol Dweck, serta prinsip neuroplastisitas dalam psikologi perkembangan. Saya percaya bahwa kapasitas, kecerdasan, dan keterampilan emosional siswa tidak bersifat statis, melainkan dapat terus dilatih dan dikembangkan melalui refleksi, kerja keras, dan strategi bimbingan yang tepat. Oleh karena itu, melalui bimbingan klasikal dan konseling, saya berkomitmen untuk mereduksi <em>fixed mindset</em> yang sering membuat siswa SMK merasa tidak mampu akibat kegagalan akademis di masa lalu. Dengan mengintegrasikan teori belajar sosial dan pendekatan humanistik, saya memandang proses bimbingan sebagai seni merajut harapan dan melatih resiliensi siswa, sehingga mereka tidak hanya siap menghadapi tantangan di dunia kerja, tetapi juga tumbuh menjadi pribadi pembelajar sepanjang hayat yang tangguh.
                </p>
            </div>

            <div class="border-t border-teal-800/80 pt-6 text-center">
                <p class="text-teal-400 italic text-sm font-serif">"Menjadi Guru BK adalah tentang menuntun siswa menemukan jalan ninjanya sendiri secara mandiri dan bertanggung jawab."</p>
            </div>
        </div>
    </section>

    <!-- Footer Resmi -->
    <footer class="bg-slate-900 text-white py-12 px-4 border-t border-slate-800">
        <div class="max-w-5xl mx-auto text-center">
            <div class="flex justify-center items-center gap-6 mb-8 opacity-30 grayscale hover:grayscale-0 transition duration-500">
                <img src="Tut-Wuri-Handayani.png" alt="Logo" class="h-10">
                <img src="UNM.png" alt="Logo" class="h-10">
                <img src="PPG-Calon-Guru.png" alt="Logo" class="h-10">
                <img src="DIKTISAINTEK-BERDAMPAS.png" alt="Logo" class="h-10">
            </div>
            <p class="text-sm text-slate-500">© 2026 IKRAM NUR QALBI, S.Pd - PPG Calon Guru LPTK Universitas Negeri Makassar</p>
        </div>
    </footer>

    <!-- Script Menu Mobile -->
    <script>
        const btn = document.getElementById('mobile-btn');
        const menu = document.getElementById('mobile-menu');
        btn.addEventListener('click', () => menu.classList.toggle('hidden'));
    </script>
</body>
</html>
