# Praktikum 6: Twitter Bootstrap

Nama: Marsya Nabila Putri

NIM: 312410338

Kelas: TI.24.A4

<img width="893" height="662" alt="image" src="https://github.com/user-attachments/assets/f540f4b6-7e73-4248-aba3-20b65e7b6cbb" />

Buat folder baru dengan nama ```lab6_bootstrap```

# 1. Refactor Layout Pratikum 4

````html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Refactor Layout Praktikum 4</title>

  <!-- Link Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
        rel="stylesheet" 
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
        crossorigin="anonymous">
</head>

<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark mb-4">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Praktikum 6</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Artikel</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Container Utama -->
  <div class="container">

    <!-- Baris Heading -->
    <div class="row mb-4">
      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Heading 1</h5>
            <p class="card-text">Deskripsi singkat heading 1.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Heading 2</h5>
            <p class="card-text">Deskripsi singkat heading 2.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Heading 3</h5>
            <p class="card-text">Deskripsi singkat heading 3.</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Baris Konten Utama dan Sidebar -->
    <div class="row">
      <!-- Konten Utama -->
      <div class="col-md-8">
        <div class="card mb-4">
          <div class="card-body">
            <h4 class="card-title">Konten Utama</h4>
            <p class="card-text">
              Ini adalah area untuk artikel atau isi utama website.
              Anda dapat menambahkan teks, gambar, atau elemen lain di sini.
            </p>
          </div>
        </div>
      </div>

      <!-- Sidebar -->
      <div class="col-md-4">
        <div class="card mb-4">
          <div class="card-body">
            <h5 class="card-title">Sidebar</h5>
            <p class="card-text">
              Ini adalah bagian sidebar untuk link tambahan atau informasi lainnya.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Script Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" 
          integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" 
          crossorigin="anonymous"></script>
</body>
</html>
````

Kode HTML di atas merupakan rancangan halaman web sederhana yang menggunakan Bootstrap 5 untuk membuat tampilan lebih rapi, responsif, dan modern. Struktur halaman terdiri dari tiga bagian utama, yaitu navbar, konten utama, dan sidebar, semuanya ditempatkan di dalam container Bootstrap agar memiliki tata letak yang teratur.

Pada bagian `<body>`, terdapat **navbar** berwarna gelap di bagian atas dengan nama “Praktikum 6” dan dua menu navigasi yaitu *Home* dan *Artikel*. Navbar ini dibuat menggunakan komponen `navbar` Bootstrap.

Selanjutnya di dalam `<div class="container">`, terdapat dua bagian utama:

1. **Baris Heading** (`<div class="row">`) yang berisi tiga kolom (`col-md-4`). Masing-masing kolom menggunakan komponen `card` yang menampilkan judul “Heading 1–3” beserta deskripsi singkatnya.
2. **Baris Konten Utama dan Sidebar** yang terdiri dari dua kolom: kolom kiri (`col-md-8`) untuk konten utama dan kolom kanan (`col-md-4`) untuk sidebar. Keduanya juga menggunakan komponen `card` agar tampil rapi dan seragam.

Terakhir, Bootstrap JavaScript ditambahkan di bagian bawah agar fitur interaktif seperti tombol menu di navbar dapat berfungsi dengan baik.
Secara keseluruhan, kode ini menampilkan layout halaman web sederhana dengan struktur grid yang bersih tanpa menggunakan CSS manual.

