<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Informasi Desa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            background: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            padding: 5px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 10px;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Informasi Desa</h1>
        <p>Selamat datang di situs informasi resmi desa kami</p>
    </header>
    <nav>
        <a href="#about">Tentang Desa</a>
        <a href="#articles">Artikel</a>
        <a href="#documents">Dokumen</a>
        <a href="#gallery">Galeri Foto</a>
        <a href="#contact">Kontak</a>
    </nav>
    <div class="container" id="about">
        <h2>Tentang Desa</h2>
        <p>Desa kami terletak di daerah yang asri dan damai...</p>
    </div>
    <div class="container" id="articles">
        <h2>Artikel</h2>
        <article>
            <h3>Judul Artikel 1</h3>
            <p>Isi artikel 1...</p>
        </article>
        <article>
            <h3>Judul Artikel 2</h3>
            <p>Isi artikel 2...</p>
        </article>
    </div>
    <div class="container" id="documents">
        <h2>Dokumen</h2>
        <ul>
            <li><a href="dokumen1.pdf" download>Dokumen 1</a></li>
            <li><a href="dokumen2.pdf" download>Dokumen 2</a></li>
        </ul>
    </div>
    <div class="container" id="gallery">
        <h2>Galeri Foto</h2>
        <div class="gallery">
            <img src="foto1.jpg" alt="Foto 1">
            <img src="foto2.jpg" alt="Foto 2">
            <img src="foto3.jpg" alt="Foto 3">
        </div>
    </div>
    <div class="container" id="contact">
        <h2>Kontak</h2>
        <p>Email: info@desa.com</p>
        <p>Telepon: 08123456789</p>
        <h3>Ikuti Kami</h3>
        <p>
            <a href="https://facebook.com/desa">Facebook</a> |
            <a href="https://twitter.com/desa">Twitter</a> |
            <a href="https://instagram.com/desa">Instagram</a>
        </p>
    </div>
    <footer>
        <p>&copy; 2024 Informasi Desa. All rights reserved.</p>
    </footer>
</body>
</html>
