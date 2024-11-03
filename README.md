
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplikasi Profil</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
        }
        .container {
            max-width: 800px;
            margin: 100px auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }
        .banner {
            width: 100%;
            height: 200px;
            background-image: url('https://storage.googleapis.com/proyek_bucket/dos-8e0bb567524d816f8930296559927ac920240503154742.png');
            background-size: cover;
            background-position: center;
            border-radius: 10px;
            position: relative;
        }
        .profile-img {
            width: 250px;
            height: 300px;
            border-radius: 75px;
            margin: -75px auto 20px;
            display: block;
            border: 4px solid #fff;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
        }
        h1, h2 {
            text-align: center;
            color: #343a40;
        }
        p {
            text-align: center;
            margin: 5px 0;
            color: #495057;
        }
        .gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .gallery img {
            width: 220px;
            height: 150px;
            margin: 5px;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
        }
        .social-links {
            text-align: center;
            margin-top: 20px;
        }
        .social-links a {
            margin: 0 10px;
            text-decoration: none;
            color: #007BFF;
            transition: color 0.3s ease;
        }
        .social-links a:hover {
            color: #0056b3;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
            color: #6c757d;
        }
        .description {
            margin-top: 20px;
            padding: 10px;
            background-color: #f8f9fa;
            border-radius: 5px;
            line-height: 1.6;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="banner"></div>
        <img class="profile-img" src="https://storage.googleapis.com/proyek_bucket/profil.jpg" alt="Foto Profil" />
        
        <h1>Mutiara Novitasari</h1>
        <h2>Mahasiswa di Universitas Jenderal Achmad Yani</h2>
        <p><strong>Email:</strong> mutiaranovitasari0811@gmail.com</p>

        <div class="description">
            <p><strong>Deskripsi Diri:</strong></p>
            <p>Saya adalah seorang mahasiswa yang antusias dalam pengembangan aplikasi dan teknologi informasi. Saat ini, saya sedang fokus pada pembelajaran cloud computing dan pengembangan web.</p>
            <p>Saya memiliki ketertarikan dalam bidang energi terbarukan dan pengembangan aplikasi yang dapat membantu masyarakat dalam menggunakan sumber daya secara efisien. Selain itu, saya juga aktif di berbagai komunitas teknologi untuk memperluas pengetahuan dan jaringan saya.</p>
            <p>Di luar studi, saya suka membaca buku, mengikuti seminar teknologi, dan menjelajahi tempat-tempat baru untuk memperkaya pengalaman hidup saya.</p>
        </div>

        <div class="gallery">
            <img src="https://storage.googleapis.com/proyek_bucket/image1.jpg" alt="Gambar 1" />
            <img src="https://storage.googleapis.com/proyek_bucket/image2.jpg" alt="Gambar 2" />
            <img src="https://storage.googleapis.com/proyek_bucket/image3.jpg" alt="Gambar 3" />
            <img src="https://storage.googleapis.com/proyek_bucket/image4.jpg" alt="Gambar 4" />
            <img src="https://storage.googleapis.com/proyek_bucket/image5.jpg" alt="Gambar 5" />
        </div>

        <div class="social-links">
            <a href="https://linkedin.com/in/mutiara-novitasari-0ba060250/" target="_blank">LinkedIn</a>
            <a href="https://instagram.com/mutiaranvtsri_" target="_blank">Instagram</a>
            <a href="https://tiktok.com/@inimutiyaw" target="_blank">Tiktok</a>
        </div>
    </div>

    <footer>
        &copy; 2024 Mutiara Novitasari. All rights reserved.
    </footer>

</body>
</html>
