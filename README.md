# Lab9Web
# Praktikum 9: PHP Modular
# Nama : Fitri Ramadhani
# NIM : 312410085
# Kelas : TI.24.A.1
# Mata Kuliah : Pemrograman Web 1 (Tugas Pert-11)
# Dosen Pengampu : Agung Nugroho, S.Kom., M.Kom.

# Tujuan
1. Mahasiswa mampu memahami konsep dasar Modularisasi Program.
2. Mahasiswa mampu memahami konsep dasar Fungsi pada PHP.
3. Mahasiswa mampu membuat program Modular sederhana menggunakan PHP.
4. Mahasiswa mampu mengimplementasikan penggunaan fungsi pada PHP
Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab9_php_modular pada docroot webserver (htdocs)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

# Langkah-langkah Praktikum
Buat file baru dengan nama header.php
```PHP
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contoh Modularisasi</title>
<link href="style.css" rel="stylesheet" type="text/stylesheet"
media="screen" />
</head>
<body>
<div class="container">
<header>
<h1>Modularisasi Menggunakan Require</h1>
</header>
<nav>
<a href="home.php">Home</a>
<a href="about.php">Tentang</a>
<a href="kontak.php">Kontak</a>
</nav>
```

Buat file baru dengan nama footer.php
```PHP
<footer>
<p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
</footer>
</div>
</body>
</html>
```

Buat file baru dengan nama home.php
```PHP
<?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman Home</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
```

Buat file baru dengan nama about.php
```PHP
<?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman About</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
```

# Tampilan Web
<img width="545" height="277" alt="image" src="https://github.com/user-attachments/assets/f213ddc5-f587-4a74-8804-494793c4d7f8" />

# Pertanyaan dan Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang database,
sehingga setiap halamannya memiliki template tampilan yang sama. Dan terapkan
penggunaan Routing agar project menjadi lebih modular.
Gunakan struktur direktory seperti berikut:
<img width="614" height="415" alt="image" src="https://github.com/user-attachments/assets/a7e6d003-6a1e-4778-afa0-7ce7d2c87460" />

Routing menggunakan url: index.php?page=user/list
Opsional: Gunakan htaccess agar url lebih SEO Friendly.
Contoh URL: (base-domain)/user/list

# Jawab:

<img width="1234" height="268" alt="image" src="https://github.com/user-attachments/assets/68a611b7-84ec-4daa-a9ce-b0a880daceda" />
<img width="397" height="402" alt="image" src="https://github.com/user-attachments/assets/8457c161-6fb9-4830-9096-f56d8b07f77c" />
<img width="1252" height="290" alt="image" src="https://github.com/user-attachments/assets/f2800972-5bed-44fc-990a-4a3b0dda3f52" />
<img width="431" height="382" alt="image" src="https://github.com/user-attachments/assets/78bfd33d-36b7-441d-a67e-a0e5cc71b896" />
<img width="1161" height="266" alt="image" src="https://github.com/user-attachments/assets/f4ac69f2-d011-481b-a796-2782759109d1" />
<img width="1131" height="274" alt="image" src="https://github.com/user-attachments/assets/d354356d-e632-4c66-abf2-a2d75ead591c" />
<img width="1200" height="242" alt="image" src="https://github.com/user-attachments/assets/55af5245-847c-454d-a1ee-1f12f465e7d0" />
