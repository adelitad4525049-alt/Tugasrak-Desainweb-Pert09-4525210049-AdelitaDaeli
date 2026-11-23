# Norma Coffe — One Page Company Profile & Katalog

Website *one page* ini dibuat untuk studi kasus UMKM **Norma Coffe** sebagai media informasi produk dan penawaran kemitraan bagi pelanggan maupun calon mitra bisnis. Halaman ini dirancang responsif menggunakan **Bootstrap 5** yang dipadukan dengan **Custom CSS** guna memberikan identitas visual bernuansa kopi hangat (*dark roast*, *medium roast*, krem, dan aksen karamel). Seluruh komponen wajib telah disusun dalam satu alur halaman, meliputi *navbar* responsif, *hero section*, *alert* notifikasi promo, tiga *card* produk unggulan berbasis *grid breakpoint*, tabel ringkasan paket harga, *modal* informasi kerja sama, formulir kontak, serta *footer*.

## Masalah yang Ditemukan dan Solusi

Selama proses pembuatan website, terdapat beberapa kendala teknis yang ditemukan. Pertama, tampilan komponen bawaan Bootstrap terlihat terlalu standar sehingga kurang mencerminkan karakter merek kedai kopi. Solusinya adalah menambahkan variabel warna kustom pada file `css/style.css` untuk mengatur warna latar, tombol, *alert*, kartu produk, serta tabel agar selaras dengan identitas **Norma Coffe**. Kedua, pada layar lebar (*desktop*), bagian *hero* dan latar belakang blok utama terlihat membentang terlalu lebar dibandingkan area konten di bawahnya. Masalah ini diatasi dengan menyesuaikan pembatas lebar elemen agar sejajar dengan `.container` serta mengatur *padding* vertikal dan *breakpoint grid* (`col-12`, `col-md-6`, `col-lg-4`) sehingga tampilan tetap rapi baik di layar *desktop* maupun *mobile*.

## Struktur Folder Proyek

```text
norma-coffe/
├── index.html
├── README.md
├── css/
│   └── style.css
├── images/
│   ├── produk-1.jpg
│   ├── produk-2.jpg
│   └── produk-3.jpg
└── screenshots/
    ├── desktop.png
    └── mobile.png
```

## Pembagian Peran

Proyek ini dikerjakan secara mandiri sebagai **Tugas Individu**, mulai dari perancangan struktur HTML, penyesuaian gaya menggunakan Custom CSS, pengujian responsivitas layar *desktop* dan *mobile*, hingga penyusunan dokumentasi.


## Dokumentasi Hasil Website

### Tampilan Desktop
![Tampilan Desktop](Dokumentasi/Gambar%20hasil%20Desktop.jpeg)

### Tampilan Mobile
![Tampilan Mobile](Dokumentasi/Gambar%20hasil%20mobile.jpeg)