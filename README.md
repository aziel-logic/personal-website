# personal-website
website kedai coofee landing page

<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="index.html" href="index.html">
  <title>Kedai Kopi Vintage</title>
  <link rel="stylesheet" href="styles.css">
   <a reff="index.html" href="index.html"></a>
  <style>
    body {
      font-family: 'Georgia', serif;
      background: linear-gradient(135deg, #f5f5dc 0%, #e8d5c4 100%);
      color: #4b3d3d;
      margin: 0;
      padding: 20px;
      min-height: 100vh;
    }
    header {
      text-align: center;
      padding: 20px;
      background-color: #d2b48c;
      border-radius: 10px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    h1 {
      font-size: 2.5em;
      margin: 0;
    }
    .logout-nav {
      margin: 0;
    }
    .logout-nav a {
      color: #2b1b12;
      text-decoration: none;
      font-weight: 600;
      padding: 8px 16px;
      border-radius: 5px;
      background-color: #c59b54;
      transition: background-color 0.3s;
    }
    .logout-nav a:hover {
      background-color: #b88634;
    }
    .menu {
      margin: 20px 0;
    }
    .menu-item {
      background-color: #fff8dc;
      border: 1px solid #deb887;
      border-radius: 5px;
      padding: 10px;
      margin: 10px 0;
    }
    footer {
      text-align: center;
      margin-top: 20px;
      font-size: 0.8em;
    }
  </style>
  <style>
    /* let header be the positioning container */
    header { position: relative; }

    /* place logout nav at the right, vertically centered */
    .logout-nav {
      position: static;
      margin: 20px 0 0 0;
    }

    .logout-nav a {
      color: #2b1b12;
      text-decoration: none;
      font-weight: 600;
      padding: 8px 16px;
      border-radius: 5px;
      background-color: #c59b54;
      transition: background-color 0.3s;
    }

    .logout-nav a:hover {
      background-color: #b88634;
    }
  </style>

  <script>
    // create/move the logout nav into the header so it appears on the right
    document.addEventListener('DOMContentLoaded', function () {
      var header = document.querySelector('header');
      if (!header) return;

      var nav = document.querySelector('.logout-nav') || document.createElement('nav');
      nav.className = 'logout-nav';
      nav.innerHTML = '<a href="index.html">Logout</a>';

      // append (will move if it already exists elsewhere)
      header.appendChild(nav);
    });
  </script>
</head>
<body>
  <header>
    <h1>Kedai Kopi Vintage</h1>
    <p>Selamat datang di tempat kopi terbaik!</p>
  </header>
  <div class="menu">
    <h2>Menu Kami</h2>
    <div class="menu-item">Kopi Hitam - Rp20.000</div>
    <div class="menu-item">Latte - Rp25.000</div>
    <div class="menu-item">Cappuccino - Rp30.000</div>
    <div class="menu-item">Espresso - Rp15.000</div>
    <nav style="text-align:center; margin-top:20px;">
      <a href="reservasi.html" style="margin-right:12px; color:#4A90E2; text-decoration:none;">Buat Reservasi</a>
      <a href="Lihat Proyek.html" style="color:#4A90E2; text-decoration:none;">Kembali ke Beranda</a>
    </nav>
  </div>
  <footer>
    <p>&copy; 2023 Kedai Kopi Vintage. Semua hak dilindungi.</p>
  </footer>
  <div class="luxury-design">
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Montserrat:wght@300;500&display=swap');

      .luxury-design {
        font-family: 'Playfair Display', Georgia, serif;
        background: linear-gradient(135deg, #f7f1e6 0%, #efe6db 100%);
        padding: 28px;
        border-radius: 14px;
        box-shadow: 0 10px 30px rgba(0,0,0,0.12);
        max-width: 1000px;
        margin: 20px auto;
        color: #3a2a21;
        border: 1px solid rgba(197,155,84,0.18);
      }

      .luxury-header {
        display: flex;
        gap: 24px;
        align-items: center;
        flex-wrap: wrap;
      }

      .luxury-text {
        flex: 1;
        min-width: 260px;
      }

      .luxury-text h2 {
        margin: 0 0 8px;
        font-size: 1.9rem;
        color: #2b1b12;
        letter-spacing: 0.5px;
      }

      .divider {
        width: 64px;
        height: 4px;
        background: linear-gradient(90deg, #c59b54, #ffd88b);
        border-radius: 4px;
        margin: 12px 0;
      }

      .luxury-text p {
        margin: 0 0 16px;
        color: #4b3d3d;
        font-family: 'Montserrat', sans-serif;
        font-weight: 300;
      }

      .luxury-hero {
        flex: 0 0 320px;
        max-width: 320px;
        border-radius: 12px;
        overflow: hidden;
        box-shadow: 0 8px 24px rgba(0,0,0,0.18);
        border: 1px solid rgba(0,0,0,0.06);
      }

      .luxury-hero img {
        width: 100%;
        height: auto;
        display: block;
        object-fit: cover;
      }

      .luxury-features {
        display: flex;
        gap: 12px;
        margin-top: 14px;
        flex-wrap: wrap;
      }

      .feature {
        background: rgba(197,155,84,0.08);
        padding: 8px 12px;
        border-radius: 8px;
        font-family: 'Montserrat', sans-serif;
        font-size: 0.9rem;
        color: #2b1b12;
      }

      .cta {
        display: inline-block;
        margin-top: 16px;
        padding: 10px 18px;
        border-radius: 30px;
        background: linear-gradient(90deg, #b88634, #ffd27a);
        color: #2b1b12;
        font-weight: 600;
        text-decoration: none;
        box-shadow: 0 6px 18px rgba(181,132,49,0.28);
        transition: transform .15s ease, box-shadow .15s ease;
      }

      .cta:hover {
        transform: translateY(-3px);
        box-shadow: 0 10px 26px rgba(181,132,49,0.36);
      }

      @media (max-width: 720px) {
        .luxury-header { flex-direction: column-reverse; align-items: stretch; }
        .luxury-hero { max-width: 100%; }
      }
    </style>

    <div class="luxury-header">
      <div class="luxury-text">
        <h2>Pengalaman Mewah</h2>
        <div class="divider" aria-hidden="true"></div>
        <p>Rasakan secangkir kopi terbaik disajikan dalam suasana elegan dengan sentuhan klasik dan pelayanan penuh perhatian. Sempurna untuk pertemuan istimewa atau momen santai yang berkesan.</p>

        <div class="luxury-features">
          <div class="feature">☕ Biji kopi spesial</div>
          <div class="feature">🍰 Dessert artisan</div>
          <div class="feature">🎶 Live music</div>
        </div>

        <a class="cta" href="reservasi.html">Buat Reservasi</a>
        <nav style="text-align:center; margin-top:20px;">
          <a href="Lihat Proyek.html" style="margin-right:12px; color:#4A90E2; text-decoration:none;">Lihat Proyek</a>
          <a href="reservasi.html" style="color:#4A90E2; text-decoration:none;">Halaman Reservasi</a>
        </nav>

        <script>
          (function () {
            const form = document.querySelector('form');
            if (!form) return;

            // kirim data ke reservasi.html sebagai query string (tanpa backend)
            form.addEventListener('submit', function (e) {
              e.preventDefault();
              const data = new FormData(form);
              const params = new URLSearchParams();
              for (const [key, value] of data.entries()) params.append(key, value);
              window.location.href = 'reservasi.html?' + params.toString();
            });
          })();
        </script>
        <script>
          (function () {
            const form = document.querySelector('form');
            if (!form) return;

            form.addEventListener('submit', function (e) {
              e.preventDefault();
              const data = new FormData(form);
              const reservasi = {
                id: 'r_' + Date.now(),
                nama: data.get('nama') || '',
                tanggal: data.get('tanggal') || '',
                waktu: data.get('waktu') || '',
                jumlah_orang: data.get('jumlah_orang') || '',
                created_at: new Date().toISOString()
              };

              // Simpan reservasi ke localStorage sehingga "kedai coffee" (halaman lain) bisa membacanya
              const STORAGE_KEY = 'kedai_reservasi';
              const existing = JSON.parse(localStorage.getItem(STORAGE_KEY) || '[]');
              existing.push(reservasi);
              localStorage.setItem(STORAGE_KEY, JSON.stringify(existing));

              // Redirect ke halaman kedai (Lihat Proyek.html) dengan id reservasi sebagai query string
              window.location.href = 'Lihat Proyek.html?reservation=' + encodeURIComponent(reservasi.id);
            });
          })();
        </script>
      </div>

      <figure class="luxury-hero">
        <img src="gambar coofee.jpg" alt="Interior kedai kopi mewah — sofa, meja kayu, lampu gantung">
      </figure>
    </div>
  </div>
</body>
</html>
