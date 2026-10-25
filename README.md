# Lab4Web — Praktikum 4: CSS Layout

Folder ini berisi implementasi latihan berdasarkan Modul Praktikum Pemrograman Web, Praktikum 4: CSS Layout.

## Struktur folder

- `lab4_box.html` — contoh box element, `float`, dan `clear`.
- `lab4_layout/home.html` — halaman utama layout sederhana.
- `lab4_layout/artikel.html` — halaman artikel.
- `lab4_layout/about.html` — halaman About berisi profil, hal yang dipelajari, dan portfolio.
- `lab4_layout/kontak.html` — halaman Contact dengan form nama, email, subjek, dan pesan.
- `lab4_layout/style.css` — stylesheet untuk halaman layout.

## Cara menjalankan

1. Ekstrak folder `Lab4Web`.
2. Buka folder menggunakan Visual Studio Code.
3. Buka `lab4_box.html` di browser untuk melihat contoh float dan clear.
4. Buka `lab4_layout/home.html` di browser untuk halaman utama.
5. Gunakan menu navigasi untuk membuka Artikel, About, dan Kontak.
6. Ubah CSS atau HTML untuk bereksperimen dengan layout.

## Ringkasan langkah praktikum

1. **Box Element:** elemen HTML ditampilkan sebagai kotak dan diberi padding serta warna latar.
2. **CSS Float:** tiga kotak pertama menggunakan `float: left`.
3. **Clearfix / Clear:** kotak keempat menggunakan `clear: left` dan `float: none` agar turun ke baris berikutnya.
4. **Semantic HTML:** halaman menggunakan elemen seperti `header`, `nav`, `section`, `main`, `article`, `aside`, dan `footer`.
5. **Layout:** halaman utama menggabungkan hero panel, tiga kotak konten, artikel, sidebar widget, dan footer.
6. **About:** halaman tunggal berisi deskripsi, materi yang dipelajari, dan portfolio.
7. **Contact:** formulir berisi nama, email, subjek, dan pesan. Form belum tersambung ke backend sehingga belum benar-benar mengirim data.

## Validasi

Validasi dokumen HTML melalui [W3C Nu HTML Checker](https://validator.w3.org/nu/). Periksa setiap file HTML dan perbaiki jika ada peringatan atau error.

## Git

Untuk membuat repository dan melakukan commit:

```bash
git init
git add .
git commit -m "Praktikum 4 CSS Layout"
```

Buat repository baru bernama `Lab4Web` di GitHub, lalu ikuti instruksi GitHub untuk menambahkan remote dan melakukan `git push`.

## Screenshot laporan

Tambahkan screenshot hasil browser pada laporan praktikum. Screenshot perlu diambil langsung dari hasil yang dijalankan di komputer sendiri; folder ini tidak mengklaim menyertakan screenshot browser yang belum diambil.
