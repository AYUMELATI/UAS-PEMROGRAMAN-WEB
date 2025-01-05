# UAS-PEMROGRAMAN-WEB
Laporan minggu ke3 uas pemrograman web

# Website Profil Kelas B Teknik Informatika

## Deskripsi Proyek
Jelaskan secara detail mengenai proyek anda, termasuk : 
- Tujuan proyek
  Web profil kelas dirancang untuk menjadi representasi digital sebuah kelas, baik di tingkat sekolah, universitas, atau pelatihan khusus. Tujuannya adalah untuk:
  a. Memperkenalkan identitas kelas, seperti nama, email, atau hobi.
  b. Menampilkan  informasi penting terkait data pribadi seseorang.
  c. Mempererat hubungan antaranggota kelas melalui dokumentasi dan interaksi online.
- Masalah yang Ingin Diselesaikan:
  a. Kurangnya Dokumentasi Terpusat: Mengatasi masalah penyimpanan dan akses informasi terkait kelas.
  b. Identitas Digital Kelas yang Kurang Menonjol: Membantu kelas memiliki platform digital yang profesional untuk menunjukkan keunikan dan pencapaiannya.

## Cara Instalasi dan Penggunaan
Berikan langkah-langkah untuk menginstal dan menjalankan proyek anda.
Contoh :
- Download proyek kami dari github ini
- Masuk ke folder xampp
  C:\Xampp\htdocs\
- Buat folder profile dan pastekan semua file pada github ini
- Create database profil_db lalu import
  profil_db.sql yang kami sediakan
- jalankan aplikasi dengan membuka Xampp dan tinggal membuka
- http://localhost/Profile/index.php

## Struktur File Proyek
/uploads/
- **add_profiles** : halaman untuk tambah profil, dimana didalamnya mencakup nama, email, deskripsi, hobi, foto dan submit
- **crud** : halaman untuk mengunggah foto, memindahkan file foto ke folder uploads, menyimpan data ke database, update foto lama ke baru, dan delete
- **detail** : halaman berisi light box data mahasiswa
- **edit_profile** : halaman untuk mengedit halaman web profil kelas
- **export** : halaman berisi export data dengan memilih format file
- **index** : halaman utama aplikasi
- **profile** : gaya untuk halaman website profil
- **save_profile** : gaya untuk mengambil data dari form, mengunggah foto, memindah file foto, dan menyimpan data ke database
