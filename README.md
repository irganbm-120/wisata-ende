<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Explore Indonesia - Pariwisata Indonesia</title>
    
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary-color: #2c5aa0;
            --secondary-color: #f8f9fa;
            --accent-color: #ff6b35;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
        }
        
        .hero-section {
            background: linear-gradient(rgba(44, 90, 160, 0.65), rgba(44, 90, 160, 0.65)), 
                        url('kelimutu.jpg   ');
            background-size: cover;
            background-position: center;
            min-height: 100vh;
            display: flex;
            align-items: center;
        }
        
        .navbar-brand {
            font-weight: 700;
            font-size: 1.5rem;
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        .destination-card {
            height: 300px;
            background-size: cover;
            background-position: center;
            position: relative;
            border-radius: 15px;
        }
        
        .destination-overlay {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(transparent, rgba(0,0,0,0.8));
            color: white;
            padding: 2rem 1.5rem 1.5rem;
            border-radius: 0 0 15px 15px;
        }

        .gallery-img {
            width: 100%;
            height: 240px;
            object-fit: cover;
            border-radius: 0.75rem;
        }
        
        footer {
            background: linear-gradient(135deg, var(--primary-color), #1e3a5f);
            color: white;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm fixed-top">
        <div class="container">
            <a class="navbar-brand text-primary fw-bold" href="#home">
                <i></i>Ende Explorer
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#destinasi" role="button" data-bs-toggle="dropdown">
                            Daftar Destinasi
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#sejarah">Wisata Sejarah</a></li>
                            <li><a class="dropdown-item" href="#alam">Wisata Alam</a></li>
                            <li><a class="dropdown-item" href="#kuliner">Wisata Kuliner</a></li>
                        </ul>
                    </li>
                    <li class="nav-item"><a class="nav-link" href="#gallery">Galeri</a></li>
                    <li class="nav-item"><a class="nav-link" href="#info">Informasi</a></li>
                    <li class="nav-item"><a class="nav-link" href="#kontak">Kontak</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-section text-white">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <h1 class="display-4 fw-bold mb-4 animate__animated animate__fadeInUp">
                        Jelajahi <span class="text-warning">Keindahan Ende</span><br>
                    
                    </h1>
                    <p class="lead mb-4 animate__animated animate__fadeInUp animate__delay-1s">
                        Nikmati pengalaman wisata terbaik dari wisata sejarah, alam, hingga kuliner khas Ende.
                    </p>
                    <div class="d-flex gap-3 animate__animated animate__fadeInUp animate__delay-2s">
                        <a href="#destinasi" class="btn btn-warning btn-lg px-5">
                            <i></i>Mulai Jelajah
                        </a>
                        <a href="#gallery" class="btn btn-outline-light btn-lg px-5">
                            <i></i>Lihat Galeri
                        </a>
                    </div>
                </div>
                <div class="col-lg-6 text-center animate__animated animate__zoomIn animate__delay-1s">
                    <div class="hero-image">
                        <i class="bi bi-mountain display-1 text-warning"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Daftar Destinasi -->
    <section id="destinasi" class="py-5 bg-light">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="display-5 fw-bold text-primary mb-3">Daftar Destinasi Unggulan</h2>
                <p class="lead text-muted">Pilih pengalaman wisata sesuai passion Anda</p>
            </div>

            <!-- Wisata Sejarah -->
            <div id="sejarah">
                <h3 class="h2 fw-bold text-center mb-4 text-primary">Wisata Sejarah</h3>
                <div class="row g-4 mb-5">
                    <div class="col-lg-4 col-md-6">
                        <div class="card card-hover h-100">
                            <div class="destination-card" style="background-image: url('rumah-pengasingan-bung.jpg')">
                                <div class="destination-overlay">
                                    <h5 class="fw-bold">Rumah Pengasingan Bung Karno</h5>
                                    <p class="mb-0">Perwira, Ende</p>
                                    <div class="mt-3">
                                        <a href="#kontak" class="btn btn-warning btn-sm me-2">Pesan Tiket</a>
                                        <a href="#kontak" class="btn btn-outline-light btn-sm">Atur Jadwal</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6">
                        <div class="card card-hover h-100">
                            <div class="destination-card" style="background-image: url('patung-bungkarno.jpg')">
                                <div class="destination-overlay">
                                    <h5 class="fw-bold">Taman Renungan Bung Karno</h5>
                                    <p class="mb-0">Rukun Lima, Ende</p>
                                    <div class="mt-3">
                                        <a href="#kontak" class="btn btn-warning btn-sm me-2">Pesan Tiket</a>
                                        <a href="#kontak" class="btn btn-outline-light btn-sm">Atur Jadwal</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6">
                        <div class="card card-hover h-100">
                            <div class="destination-card" style="background-image: url('taman-renungan.jpg')">
                                <div class="destination-overlay">
                                    <h5 class="fw-bold">Pohon Sukun Bung Karno</h5>
                                    <p class="mb-0">Ende</p>
                                    <div class="mt-3">
                                        <a href="#kontak" class="btn btn-warning btn-sm me-2">Pesan Tiket</a>
                                        <a href="#kontak" class="btn btn-outline-light btn-sm">Atur Jadwal</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Wisata Alam -->
            <div id="alam">
                <h3 class="h2 fw-bold text-center mb-4 text-success">Wisata Alam</h3>
                <div class="row g-4 mb-5">
                    <div class="col-lg-4 col-md-6">
                        <div class="card card-hover h-100">
                            <div class="destination-card" style="background-image: url('kelimutu.jpg')">
                                <div class="destination-overlay">
                                    <h5 class="fw-bold">Danau Kelimutu</h5>
                                    <p class="mb-0">Desa Pemo, Ende</p>
                                    <div class="mt-3">
                                        <a href="#kontak" class="btn btn-warning btn-sm me-2">Pesan Tiket</a>
                                        <a href="#kontak" class="btn btn-outline-light btn-sm">Atur Jadwal</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6">
                        <div class="card card-hover h-100">
                            <div class="destination-card" style="background-image: url('wisata-gunung-iya.jpg')">
                                <div class="destination-overlay">
                                    <h5 class="fw-bold">Gunung ia</h5>
                                    <p class="mb-0">Rate, Ende</p>
                                    <div class="mt-3">
                                        <a href="#kontak" class="btn btn-warning btn-sm me-2">Pesan Tiket</a>
                                        <a href="#kontak" class="btn btn-outline-light btn-sm">Atur Jadwal</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6">
                        <div class="card card-hover h-100">
                            <div class="destination-card" style="background-image: url('pantai-batu-biru-flores-ntt.jpg')">
                                <div class="destination-overlay">
                                    <h5 class="fw-bold">Pantai Batu Biru</h5>
                                    <p class="mb-0">Penggajawa, Ende</p>
                                    <div class="mt-3">
                                        <a href="#kontak" class="btn btn-warning btn-sm me-2">Pesan Tiket</a>
                                        <a href="#kontak" class="btn btn-outline-light btn-sm">Atur Jadwal</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Wisata Kuliner -->
            <div id="kuliner">
                <h3 class="h2 fw-bold text-center mb-4 text-warning">Wisata Kuliner</h3>
                <div class="row g-4">
                    <div class="col-lg-4 col-md-6">
                        <div class="card card-hover h-100">
                            <div class="destination-card" style="background-image: url('Uwi-Ai-Ndota.jpg')">
                                <div class="destination-overlay">
                                    <h5 class="fw-bold">Uwi Ai Ndota</h5>
                                    <p class="mb-0">Ende</p>
                                    <div class="mt-3">
                                        <a href="#kontak" class="btn btn-warning btn-sm me-2">Pesan Makanan</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6">
                        <div class="card card-hover h-100">
                            <div class="destination-card" style="background-image: url('alu-ndene.jpeg')">
                                <div class="destination-overlay">
                                    <h5 class="fw-bold">Alu Ndene</h5>
                                    <p class="mb-0">Ende</p>
                                    <div class="mt-3">
                                        <a href="#kontak" class="btn btn-warning btn-sm me-2">Pesan Makanan</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6">
                        <div class="card card-hover h-100">
                            <div class="destination-card" style="background-image: url('uta-ngeta.avif')">
                                <div class="destination-overlay">
                                    <h5 class="fw-bold">Uta Ngetta</h5>
                                    <p class="mb-0">Ende</p>
                                    <div class="mt-3">
                                        <a href="#kontak" class="btn btn-warning btn-sm me-2">Pesan Makanan</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery -->
    <section id="gallery" class="py-5 bg-dark text-white">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="display-5 fw-bold mb-3">Galeri Foto</h2>
                <p class="lead">Kenangan indah dari para traveler</p>
            </div>
            <div class="row g-3">
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="senja.png" class="img-fluid rounded shadow gallery-img" alt="Bali">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="patung.jpg" class="img-fluid rounded shadow gallery-img" alt="Raja Ampat">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="pancasila.jpeg" class="img-fluid rounded shadow gallery-img" alt="Labuan Bajo">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="foto.png" class="img-fluid rounded shadow gallery-img" alt="Bromo">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="mendaki.png" class="img-fluid rounded shadow gallery-img" alt="Bromo">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="makan.png" class="img-fluid rounded shadow gallery-img" alt="Bromo">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="gunung ia.jpg" class="img-fluid rounded shadow gallery-img" alt="Bromo">
                </div>
                <div class="col-lg-3 col-md-4 col-6">
                    <img src="petualang.png" class="img-fluid rounded shadow gallery-img" alt="Bromo">
                </div>
            </div>
    </section>

    <!-- Informasi -->
    <section id="info" class="py-5">
        <div class="container">
            <div class="row g-5">
                <div class="col-lg-8">
                    <h2 class="display-5 fw-bold mb-4 text-primary">Informasi Penting</h2>
                    <div class="accordion" id="infoAccordion">
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#info1">
                                    Cara Pemesanan Tiket
                                </button>
                            </h2>
                            <div id="info1" class="accordion-collapse collapse show" data-bs-parent="#infoAccordion">
                                <div class="accordion-body">
                                    Pesan tiket secara online melalui website resmi atau aplikasi mobile kami. Pembayaran dapat dilakukan melalui transfer bank, e-wallet, atau kartu kredit.
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#info2">
                                    Kebijakan Pembatalan
                                </button>
                            </h2>
                            <div id="info2" class="accordion-collapse collapse" data-bs-parent="#infoAccordion">
                                <div class="accordion-body">
                                    Pembatalan dapat dilakukan 24 jam sebelum keberangkatan dengan pengembalian 80% dari total pembayaran.
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#info3">
                                    Panduan Keselamatan
                                </button>
                            </h2>
                            <div id="info3" class="accordion-collapse collapse" data-bs-parent="#infoAccordion">
                                <div class="accordion-body">
                                    Ikuti instruksi pemandu wisata untuk menjaga keselamatan.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="card h-100 shadow">
                        <div class="card-body text-center">
                            <i class="bi bi-info-circle-fill display-1 text-primary mb-3"></i>
                            <h4 class="card-title">Tips Perjalanan</h4>
                            <ul class="list-unstyled">
                                <li class="mb-2"><i class="bi bi-check-circle text-success me-2"></i>Bawa identitas asli</li>
                                <li class="mb-2"><i class="bi bi-check-circle text-success me-2"></i>Gunakan pakaian nyaman</li>
                                <li class="mb-2"><i class="bi bi-check-circle text-success me-2"></i>Bawa obat pribadi</li>
                                <li><i class="bi bi-check-circle text-success me-2"></i>Patuhi protokol kesehatan</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer/Kontak -->
    <footer id="kontak" class="py-5 mt-5">
        <div class="container">
            <div class="row">
                <div class="col-lg-4 mb-4">
                    <h5 class="fw-bold mb-3">
                        <i></i>Ende Explorer
                    </h5>
                    <p class="text-light opacity-75">
                        Jelajahi keindahan Ende dengan pengalaman wisata terbaik dari Ende Explorer.
                    </p>
                    <div class="d-flex gap-3">
                        <a href="#" class="text-white"><i class="bi bi-facebook fs-4"></i></a>
                        <a href="#" class="text-white"><i class="bi bi-instagram fs-4"></i></a>
                        <a href="#" class="text-white"><i class="bi bi-twitter fs-4"></i></a>
                        <a href="#" class="text-white"><i class="bi bi-youtube fs-4"></i></a>
                    </div>
                </div>
                <div class="col-lg-2 col-md-6 mb-4">
                    <h6 class="fw-bold mb-3">Destinasi</h6>
                    <ul class="list-unstyled">
                        <li><a href="#sejarah" class="text-light text-decoration-none opacity-75">Wisata Sejarah</a></li>
                        <li><a href="#alam" class="text-light text-decoration-none opacity-75">Wisata Alam</a></li>
                        <li><a href="#kuliner" class="text-light text-decoration-none opacity-75">Wisata Kuliner</a></li>
                    </ul>
                </div>
                <div class="col-lg-3 col-md-6 mb-4">
                    <h6 class="fw-bold mb-3">Kontak Kami</h6>
                    <div>
                        <i class="bi bi-telephone me-2"></i>
                        <span>+62 812-3456-7890</span>
                    </div>
                    <div class="mt-2">
                        <i class="bi bi-envelope me-2"></i>
                        <span>endexplorer@gmail.com</span>
                    </div>
                    <div class="mt-2">
                        <i class="bi bi-geo-alt me-2"></i>
                        <span>Jl. Eltari, Ende</span>
                    </div>
                </div>
                <div class="col-lg-3 mb-4">
                    <h6 class="fw-bold mb-3">Newsletter</h6>
                    <p class="opacity-75 mb-3">Dapatkan update destinasi terbaru!</p>
                    <div class="input-group">
                        <input type="email" class="form-control" placeholder="Email Anda">
                        <button class="btn btn-warning" type="button">
                            <i class="bi bi-send"></i>
                        </button>
                    </div>
                </div>
            </div>
            <hr class="my-4 opacity-25">
            <div class="text-center">
                <p class="mb-0 opacity-75">&copy; 2024 Ende Explorer. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Bootstrap 5 JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    
    <!-- Smooth Scrolling -->
    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Navbar background on scroll
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('.navbar');
            if (window.scrollY > 100) {
                navbar.classList.add('shadow-lg');
                navbar.classList.add('bg-white');
            } else {
                navbar.classList.remove('shadow-lg');
                navbar.classList.remove('bg-white');
            }
        });
    </script>
</body>
</html>
