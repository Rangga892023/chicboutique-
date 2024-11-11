<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chic Boutique</title>
    <!-- Link Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <img src="images/logo.png" alt="Chic Boutique Logo" width="200" height="200" class="d-inline-block align-text-top">
            <a class="navbar-brand" href="#">Chic Boutique</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about-section">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#product-section">Shop</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact-section">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Home Section -->
    <section class="text-center bg-primary text-white py-5" id="home-section">
        <div class="container">
            <h1 class="display-4">Selamat Datang di Chic Boutique</h1>
            <p class="lead">Temukan koleksi jilbab yang elegan dan berkualitas tinggi untuk Anda.</p>
        </div>
    </section>

    <!-- About Section -->
    <section class="container my-5" id="about-section">
        <div class="text-center mb-5">
        <h2>About</h2>
        <p>Chic Boutique didirikan dengan tujuan untuk menyediakan jilbab berkualitas tinggi yang tidak hanya stylish tetapi juga nyaman digunakan. Kami percaya bahwa setiap wanita berhak untuk merasa cantik dan percaya diri dalam setiap kesempatan.</p>
    </div>  
    </section>

    <!-- Product Section -->
<section class="container my-5" id="product-section">
    <div class="text-center mb-5">
        <h2>Koleksi</h2>
        <p>Pilih jilbab berkualitas tinggi</p>
    </div>
    <div class="row text-center">
        <div class="col-md-4 mb-4">
            <div class="card">
                <img src="images/jilbab1.jpg" class="card-img-top img-fluid" alt="Jilbab Segi Empat">
                <div class="card-body">
                    <h3 class="card-title">Jilbab warna minty, matcha dan snow white</h3>
                    <p class="card-text">Rp 25.000</p>
                    <a href="https://s.shopee.co.id/1g19pfCHDF" target="_blank" class="btn btn-primary">Beli Sekarang</a> 
                </div>
            </div>
        </div>
        <div class="col-md-4 mb-4">
            <div class="card">
                <img src="images/jilbab2.jpg" class="card-img-top img-fluid" alt="Pashmina">
                <div class="card-body">
                    <h3 class="card-title">Jilbab Warna Light Grey, Grey, Ash Grey, Cappuccino</h3>
                    <p class="card-text">Rp 25.000</p>
                    <a href="https://s.shopee.co.id/1g19pfCHDF" target="_blank" class="btn btn-primary">Beli Sekarang</a>
                </div>
            </div>
        </div>
        <div class="col-md-4 mb-4">
            <div class="card">
                <img src="images/jilbab3.jpg" class="card-img-top img-fluid" alt="Jilbab Instan">
                <div class="card-body">
                    <h3 class="card-title">Jilbab Warna Rosegold, Red Wine, Sand Pink, Maroon</h3>
                    <p class="card-text">Rp 25.000</p>
                    <a href="https://s.shopee.co.id/1g19pfCHDF" target="_blank" class="btn btn-primary">Beli Sekarang</a>
                </div>
            </div>
        </div>
    </div>
</section>

    <!-- Contact Section -->
<section class="container my-5" id="contact-section">
    <div class="text-center mb-5">
        <h2>Contact</h2>
        <div>
            <p>Email: <a href="mailto:franggae@gmail.com">franggae@gmail.com</a></p>
            <p>Phone: +6285717136121</p>
            <p>Address: Griya Syafana Sampora, Cisauk</p>
        </div>
        <div class="social-icons mt-4">
            <a href="https://www.instagram.com/_chicboutiquefashion?igsh=MWt4eWhxdXNiM2VqNA%3D%3D&utm_source=qr" target="_blank" class="mx-2">
                <i class="fab fa-instagram fa-2x"></i>
                <p>Instagram</p>
            </a>
            <a href="https://www.tiktok.com" target="_blank" class="mx-2">
                <i class="fab fa-tiktok fa-2x"></i>
                <p>Tiktok</p>
            </a>
            <a href="https://s.shopee.co.id/1g19pfCHDF" target="_blank" class="mx-2">
                <i class="fab fa-shopping-cart fa-2x"></i> <!-- Menggunakan ikon cart sebagai simbol Shopee -->
                <p>Shopee</p>
            </a>
        </div>
    </div>
</section>


    <!-- Footer -->
    <footer class="bg-light py-3">
        <div class="container text-center">
            <p>&copy; 2024 Chic Boutique. All Rights Reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
    <script>// Wait for the DOM to fully load
        document.addEventListener("DOMContentLoaded", function () {
            // Smooth scrolling for navigation links
            const navLinks = document.querySelectorAll('.navbar-nav a');
        
            navLinks.forEach(link => {
                link.addEventListener('click', function (event) {
                    event.preventDefault(); // Prevent default anchor click behavior
                    const targetId = this.getAttribute('href'); // Get target section ID
                    const targetSection = document.querySelector(targetId); // Select the target section
        
                    // Scroll to the target section
                    targetSection.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                });
            });
        
            // Highlight the current section in the navbar
            const sections = document.querySelectorAll('section');
            const nav = document.querySelector('.navbar-nav');
        
            window.addEventListener('scroll', () => {
                let current = '';
        
                sections.forEach(section => {
                    const sectionTop = section.offsetTop; // Get the top position of the section
                    const sectionHeight = section.clientHeight; // Get the height of the section
        
                    // Check if the current scroll position is within the section
                    if (scrollY >= sectionTop - sectionHeight / 3) {
                        current = section.getAttribute('id');
                    }
                });
        
                navLinks.forEach(link => {
                    link.classList.remove('active'); // Remove active class from all links
                    if (link.getAttribute('href') === `#${current}`) {
                        link.classList.add('active'); // Add active class to the current link
                    }
                });
            });
        });
        </script>
</body>
</html>

/* General Styles */
body {
    background-color: #f0f4f8;
    font-family: 'Poppins', sans-serif;
    color: #2d3436;
    line-height: 1.6;
    padding-top: 40px;
}

h1, h2, h3 {
    color: #2d3436;
    font-weight: bold;
}

a {
    text-decoration: none;
    transition: color 0.3s ease;
}

/* Navbar */
.navbar {
    background-color: #ffffff;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    padding: 15px 0;
}

.navbar .navbar-brand {
    font-size: 1.8rem;
    font-weight: 700;
    color: #08c240;
    display: flex;
    align-items: center;
}

.navbar .navbar-brand img {
    width: 50px; /* Ukuran logo */
    height: 50px; /* Ukuran logo */
    margin-right: 10px; /* Jarak antara logo dan teks */
    transition: transform 0.3s ease; /* Efek saat hover */
}

.navbar .navbar-brand img:hover {
    transform: scale(1.1); /* Memperbesar logo saat hover */
}

.navbar .nav-link {
    color: #2d3436;
    margin-left: 15px;
    font-weight: 500;
    position: relative;
}

.navbar .nav-link::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    background-color: #08c240;
    left: 0;
    bottom: -5px;
    transition: width 0.3s;
}

.navbar .nav-link:hover::after {
    width: 100%;
}

.navbar .nav-link:hover {
    color: #08c240;
}

/* Hero Section */
section.text-center.bg-primary {
    background: linear-gradient(135deg, #08c240, #10f2ae);
    color: #acabab;
    padding: 100px 0;
    position: relative;
    overflow: hidden;
    z-index: 1;
}

section.text-center.bg-primary h1 {
    font-size: 3rem;
    font-weight: 800;
    letter-spacing: 2px;
    margin-bottom: 20px;
    text-transform: uppercase;
}

section.text-center.bg-primary p {
    font-size: 1.3rem;
    margin-bottom: 0;
    max-width: 700px;
    margin-left: auto;
    margin-right: auto;
    line-height: 1.8;
}
/* About Section Styles */
#about-section {
    background-color: #c9c2c2; /* Light background for contrast */
    padding: 50px 0; /* Padding for spacing */
    border-radius: 10px; /* Rounded corners */
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
}

#about-section h2 {
    font-size: 2.5rem; /* Larger font for the title */
    color: #000000; /* Blue color for the title */
    margin-bottom: 20px; /* Space below the title */
    font-weight: bold; /* Bold font for emphasis */
}

#about-section p {
    font-size: 1.2rem; /* Slightly larger font for the paragraph */
    color: #555; /* Darker gray for better readability */
    line-height: 1.6; /* Improved line height for readability */
    max-width: 800px; /* Maximum width for the paragraph */
    margin: 0 auto; /* Center align the paragraph */
}


/* Product Section */
section.container.my-5 h2 {
    color: #2d3436;
    font-size: 2.8rem;
    font-weight: 700;
    margin-bottom: 20px;
    text-transform: uppercase;
}

section.container.my-5 p {
    font-size: 1.2rem;
    color: #636e72;
    max-width: 600px;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 40px;
}

.row .col-md-4 {
    margin-bottom: 30px;
}

.row .col-md-4 img {
    border-radius: 15px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.row .col-md-4 img:hover {
    transform: scale(1.05);
    box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
}

.row .col-md-4 h3 {
    font-size: 1.8rem;
    font-weight: 600;
    margin-top: 15px;
    color: #2d3436;
}

.row .col-md-4 p {
    color: #27ae60;
    font-size: 1.4rem;
    font-weight: 500;
}

.row .col-md-4 .btn {
    margin-top: 10px;
    background-color: #08c240;
    border: none;
    border-radius: 30px;
    padding: 10px 20px;
    font-weight: 600;
    text-transform: uppercase;
    transition: background-color 0.3s ease;
}

.row .col-md-4 .btn:hover {
    background-color: #08c240;
    box-shadow: 0 8px 15px rgba(0, 123, 255, 0.2);
}

body {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

/* Contact Section Styles */
#contact-section {
    background-color: #c5c5c5; /* White background for cleanliness */
    padding: 50px 0; /* Padding for spacing */
    border-radius: 5px; /* Rounded corners */
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
}

#contact-section h2 {
    font-size: 2.5rem; /* Larger font for the title */
    color: #08c240; /* Blue color for the title */
    margin-bottom:10px; /* Space below the title */
    font-weight: bold; /* Bold font for emphasis */
}

#contact-section p {
    font-size: 1.2rem; /* Larger font size for readability */
    color: #333; /* Darker gray for better readability */
    line-height: 1; /* Improved line height */
}

#contact-section a {
    color: #08c240; /* Blue color for links */
    text-decoration: none; /* Remove underline from links */
}

#contact-section a:hover {
    text-decoration: underline; /* Underline on hover for interactivity */
}
/* Social Icons Styles */
.social-icons {
    display: flex; /* Menyusun ikon dalam baris */
    justify-content: center; /* Menyelaraskan ikon ke tengah */
    align-items: center; /* Menyelaraskan ikon secara vertikal */
    margin-top: 20px; /* Ruang di atas ikon sosial media */
}

.social-icons a {
    display: flex; /* Menyusun ikon dan teks dalam kolom */
    flex-direction: column; /* Mengatur ikon di atas dan teks di bawah */
    align-items: center; /* Menyelaraskan item di tengah */
    margin: 0 15px; /* Ruang horizontal antara ikon */
    color: #333; /* Warna teks default */
    text-decoration: none; /* Menghilangkan garis bawah pada tautan */
    transition: color 0.3s; /* Efek transisi saat hover */
}

.social-icons a:hover {
    color: #08c240; /* Warna saat hover */
}

.social-icons a i {
    font-size: 2rem; /* Ukuran ikon */
    margin-bottom: 5px; /* Ruang di bawah ikon */
}

.social-icons a p {
    font-size: 0.9rem; /* Ukuran font untuk teks di bawah ikon */
    color: #08c240; /* Warna teks untuk nama platform */
    text-align: center; /* Memastikan teks berada di tengah */
}


footer {
    background-color: #1cdf67; /* Warna latar belakang yang lembut */
    color: #343a40; /* Warna teks */
    padding: 40px 0; /* Ruang di atas dan bawah */
    text-align: center; /* Teks rata tengah */
    border-top: 1px solid #08c240; /* Garis atas footer */
}

footer h5 {
    font-size: 1.5rem; /* Ukuran font untuk subjudul */
    margin-bottom: 20px; /* Jarak bawah untuk subjudul */
    font-weight: bold; /* Tebal */
}

footer p {
    margin: 1px 0; /* Jarak antara paragraf */
}

footer a {
    color: #08c240; /* Warna link */
    text-decoration: none; /* Menghilangkan garis bawah */
}

footer a:hover {
    text-decoration: underline; /* Garis bawah saat hover */
}

footer .container {
    max-width: 800px; /* Lebar maksimum kontainer */
    margin: 0 auto; /* Pusatkan kontainer */
}

@media (max-width: 768px) {
    footer {
        padding: 30px 15px; /* Ruang di footer pada layar kecil */
    }
}

