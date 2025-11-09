# https-alzxyshop-official-website.netlify.app
MELAYANI KEBUTUHAN HOSTING 
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>daflyShop - Jual VPS</title>
  <meta name="description" content="Platform terpercaya untuk kebutuhan VPS Anda. Harga bersahabat, performa terbaik, dan pelayanan yang cepat.">
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <nav class="navbar">
      <div class="logo">daflyShop</div>
      <ul class="menu">
        <li><a href="#home">Beranda</a></li>
        <li><a href="#services">Layanan VPS</a></li>
        <li><a href="#testimoni">Testimoni</a></li>
        <li><a href="#riwayat">Riwayat</a></li>
        <li><a href="#contact">Kontak</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <img src="assets/858ead.jpg" alt="Hero Image" class="hero-img">
    <div class="hero-content">
      <h1>Selamat Datang di <span>daflyShop</span></h1>
      <p>Platform terpercaya untuk kebutuhan VPS Anda. Harga bersahabat, performa terbaik, dan pelayanan cepat.</p>
      <a class="btn" href="#services">Mulai Membeli</a>
    </div>
  </section>

  <section id="services" class="section">
    <h2>Silakan Pilih VPS Anda</h2>
    <div class="cards">
      <div class="card">
        <h3>VPS Basic</h3>
        <p>CPU 1 core / RAM 1 GB / Bandwidth 1 TB</p>
        <a href="#" class="btn">Pilih Sekarang</a>
      </div>
      <div class="card">
        <h3>VPS Standard</h3>
        <p>CPU 2 core / RAM 2 GB / Bandwidth 2 TB</p>
        <a href="#" class="btn">Pilih Sekarang</a>
      </div>
      <div class="card">
        <h3>VPS Premium</h3>
        <p>CPU 4 core / RAM 4 GB / Bandwidth 4 TB</p>
        <a href="#" class="btn">Pilih Sekarang</a>
      </div>
    </div>
  </section>

  <section id="testimoni" class="section alt">
    <h2>Testimoni Pelanggan</h2>
    <blockquote>“Layanan cepat dan harga terjangkau – sangat puas!” <footer>– Rizky</footer></blockquote>
    <blockquote>“Uptime stabil dan support responsif.” <footer>– Andi</footer></blockquote>
  </section>

  <section id="riwayat" class="section">
    <h2>Riwayat Pemesanan</h2>
    <p>Masukkan ID atau login untuk melihat riwayat Anda.</p>
    <a class="btn" href="#">Lihat Riwayat</a>
  </section>

  <section id="contact" class="section alt">
    <h2>Hubungi Kami</h2>
    <p>Join channel WhatsApp: 
      <a href="https://wa.me/6281234567890" target="_blank" class="wa-link">Klik di sini</a>
    </p>
  </section>

  <footer>
    <p>© 2025 daflyShop. All rights reserved.</p>
  </footer>
</body>
</html>
/* Reset dasar */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  color: #333;
  background-color: #fff;
  scroll-behavior: smooth;
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 8%;
  background: #0a66c2;
  color: #fff;
  position: sticky;
  top: 0;
  z-index: 100;
}

.navbar .logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.navbar .menu {
  list-style: none;
  display: flex;
  gap: 20px;
}

.navbar .menu a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s;
}

.navbar .menu a:hover {
  color: #cce0ff;
}

/* Hero section */
.hero {
  position: relative;
  height: 80vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
  overflow: hidden;
}

.hero-img {
  position: absolute;
  width: 100%;
  height: 100%;
  object-fit: cover;
  filter: brightness(60%);
}

.hero-content {
  position: relative;
  z-index: 2;
  max-width: 600px;
  padding: 20px;
}

.hero-content h1 span {
  color: #4fc3f7;
}

.btn {
  display: inline-block;
  margin-top: 15px;
  padding: 10px 20px;
  background: #0a66c2;
  color: #fff;
  border-radius: 5px;
  text-decoration: none;
  transition: background 0.3s;
}

.btn:hover {
  background: #094e97;
}

/* Section umum */
.section {
  padding: 80px 8%;
  text-align: center;
}

.section.alt {
  background: #f9f9f9;
}

.section h2 {
  font-size: 2rem;
  margin-bottom: 30px;
  color: #0a66c2;
}

/* Kartu layanan */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.card {
  background: white;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  padding: 25px;
  transition: transform 0.3s;
}

.card:hover {
  transform: translateY(-8px);
}

.card h3 {
  margin-bottom: 10px;
  color: #0a66c2;
}

/* Testimoni */
blockquote {
  margin: 20px auto;
  max-width: 600px;
  font-style: italic;
  background: #fff;
  padding: 20px;
  border-left: 5px solid #0a66c2;
  box-shadow: 0 4px 10px rgba(0,0,0,0.05);
}

/* Footer */
footer {
  background: #0a66c2;
  color: #fff;
  text-align: center;
  padding: 20px;
  font-size: 0.9rem;
}

/* Responsif */
@media (max-width: 768px) {
  .navbar .menu {
    flex-wrap: wrap;
    justify-content: center;
  }
  .hero-content h1 {
    font-size: 1.8rem;
  }
}
