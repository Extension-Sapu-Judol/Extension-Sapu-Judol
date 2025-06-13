# Extension-Sapu-Judol

## Problem Statement
Maraknya komentar spam yang mempromosikan judi online (judol) di platform YouTube telah menjadi masalah serius, terutama bagi pengguna muda dan anak-anak. Komentar-komentar ini seringkali menggunakan teknik kamuflase bahasa untuk menghindari moderasi otomatis YouTube, seperti mengganti huruf dengan angka atau simbol. Hal ini membahayakan karena:
- Berpotensi mempengaruhi pengguna rentan, terutama anak-anak.
- Mengganggu kenyamanan pengguna saat membaca komentar.
- Sulit dimoderasi secara manual karena volumenya tinggi dan muncul secara terus–menerus.

## Deskripsi Produk/Aplikasi
Sapu Judol adalah sebuah ekstensi browser (Google Chrome/Brave/Edge) yang secara otomatis:
- Mendeteksi dan menyensor komentar yang mengandung promosi judi online di kolom komentar YouTube.
- Menggunakan teknik pemrosesan bahasa alami (NLP) dan pola deteksi karakter tidak lazim untuk mengidentifikasi komentar yang dimodifikasi agar lolos dari filter.
- Bertujuan untuk menjaga ekosistem digital yang sehat dan melindungi pengguna, khususnya anak-anak, dari pengaruh negatif konten komentar.

## Fitur Utama dan Teknologi yang Digunakan
- Fitur Utama:
  - Deteksi Komentar Judol: Mengidentifikasi komentar yang mengandung kata kunci terkait promosi judi online, termasuk versi tersamarkan (e.g. "jud1", "s!tus slot").
  - Sensor Komentar: Menyembunyikan atau mengganti komentar mencurigakan dengan placeholder seperti “[Komentar disensor oleh Sapu Judol]”.
  - Toggle Aktif/Non Aktif: Memungkinkan pengguna untuk mengaktifkan atau menonaktifkan penyensoran dengan mudah.
- Teknologi yang Digunakan:
  - Frontend: Plasmo Framework - framework modern berbasis React untuk mengembangkan ekstensi browser dengan lebih cepat dan terstruktur.
  - Backend: FastAPI. 
  - Bahasa Pemrograman: Python, TypeScript.
  - Ekstensi API: Chrome Extensions API (Manifest v3 via Plasmo).
  - Tools: Google Colab, VSCode, dan Postman.
 
## Tim dan perang anggota
![Gambar Contoh](https://via.placeholder.com/150)
