# LAPORAN TUGAS 1: PROYEK PERANGKAT LUNAK

## A. Informasi Proyek
* **Nama Proyek:** Aplikasi Pengelolaan Kas dan Iuran Warga (SiKarsa)
* **Jenis Aplikasi:** Web-based Application (Sistem Informasi Berbasis Web)
* **Kategori Studi Kasus:** Pengelolaan Keuangan Lingkungan RT / UMKM Lokal

---

## B. Latar Belakang
Pengelolaan keuangan di tingkat Rukun Tetangga (RT) merupakan hal penting untuk menjaga transparansi dan kepercayaan antarwarga. Namun, pada kenyataannya masih banyak pengurus RT yang menggunakan pencatatan manual berbasis buku tulis atau lembaran kertas biasa. 

Sistem manual ini kerap menimbulkan berbagai kendala operasional harian. Buku kas fisik riskan rusak, basah, atau terselip, yang berujung pada hilangnya riwayat transaksi keuangan. Selain itu, warga kesulitan mengetahui penggunaan dana kas secara terbuka karena tidak adanya sistem yang dapat diakses sewaktu-waktu. Oleh karena itu, diperlukan sebuah sistem informasi berbasis web sederhana yang dapat mendigitalkan proses pencatatan iuran warga dan pengeluaran kas secara terorganisir dan transparan.

---

## C. Permasalahan
Berdasarkan kondisi nyata di lapangan, beberapa permasalahan utama yang diidentifikasi meliputi:
1. **Kurangnya Transparansi:** Warga tidak memiliki akses langsung untuk memantau saldo kas dan rincian penggunaan dana iuran bulanan.
2. **Potensi Kesalahan Pencatatan (Human Error):** Bendahara sering mengalami kesulitan dan kesalahan saat menghitung rekapitulasi transaksi bulanan secara manual.
3. **Pencatatan yang Tidak Terstruktur:** Sulit untuk mengecek dan memverifikasi siapa saja warga yang sudah atau belum membayar iuran pada bulan tertentu.
4. **Resiko Kehilangan Data:** Buku catatan fisik rentan rusak atau hilang, terutama saat ada pergantian pengurus RT baru.

---

## D. Tujuan Sistem
Tujuan dari pengembangan perangkat lunak ini adalah:
1. Membangun aplikasi web sederhana yang dapat membantu bendahara RT mencatat pemasukan dan pengeluaran kas secara digital.
2. Meningkatkan transparansi keuangan lingkungan RT agar seluruh warga dapat memantau penggunaan dana secara terbuka.
3. Meminimalkan kesalahan perhitungan kas dan mempermudah proses rekapitulasi data di setiap akhir bulan.
4. Menyediakan media penyimpanan data warga dan riwayat pembayaran iuran yang rapi serta aman.

---

## E. Ruang Lingkup Sistem (Minimal 3–4 Menu Utama)
Aplikasi ini akan dibatasi pada 4 menu utama untuk memastikan pengerjaan proyek terfokus dan selesai tepat waktu dalam 1 semester:

1. **Menu Data Warga (CRUD Data Warga)**
   * Berfungsi untuk mengelola data kepala keluarga atau warga yang terdaftar sebagai pembayar iuran (tambah data, lihat daftar, ubah data, dan hapus data).
   * Informasi yang disimpan meliputi: Nama Warga, Blok/Nomor Rumah, No. HP, dan Status Hunian.

2. **Menu Transaksi Iuran Warga**
   * Berfungsi untuk mencatat pembayaran iuran bulanan warga.
   * Fitur mencakup: Pilih Nama Warga, Bulan Pembayaran, Nominal Iuran, Tanggal Bayar, dan Status (Lunas/Belum Lunas).

3. **Menu Pencatatan Pengeluaran Kas**
   * Berfungsi untuk mencatat setiap pengeluaran kas RT (seperti biaya perbaikan pos ronda, beli lampu jalan, kerja bakti, dll).
   * Fitur mencakup: Tanggal Pengeluaran, Keterangan Keperluan, dan Nominal Pengeluaran.

4. **Menu Laporan Keuangan**
   * Berfungsi untuk menampilkan rekapitulasi total pemasukan iuran, total pengeluaran, dan sisa saldo kas RT secara otomatis.
   * Menyediakan ringkasan laporan bulanan yang siap dicetak untuk rapat warga.
