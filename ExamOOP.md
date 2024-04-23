# Sistem Perpustakaan

## Deskripsi
Sistem perpustakaan sederhana yang dibangun menggunakan konsep OOP dalam PHP. Sistem ini menyediakan fungsi-fungsi dasar seperti menambahkan buku baru, meminjam buku, mengembalikan buku, dan mencetak daftar buku yang tersedia.

## Kelas yang Dibutuhkan

1. **Book:** Kelas ini merepresentasikan objek buku dengan atribut seperti judul, penulis, tahun terbit, dan status pinjam.
   
2. **Library:** Kelas ini merepresentasikan objek perpustakaan yang memiliki koleksi buku dan berbagai fungsi seperti menambahkan buku baru, meminjam buku, mengembalikan buku, dan mencetak daftar buku yang tersedia.

## Konsep OOP yang Digunakan

- Inheritance
- Overriding
- Constructor
- Encapsulation
- Static
- Polymorphism

## Fitur Tambahan

1. **Pencarian Buku:** Menambahkan fitur ke Library class untuk mencari buku berdasarkan judul atau penulis.
   
2. **Batasan Peminjaman:** Implementasi mekanisme untuk menangani batasan jumlah buku yang dapat dipinjam oleh satu pengguna pada satu waktu di dalam Library class.
   
3. **Subclass ReferenceBook:** Membuat subclass dari Book class yang disebut ReferenceBook dengan atribut tambahan seperti nomor ISBN dan informasi penerbit.
   
4. **Pengurutan Buku:** Tambahkan fitur ke Library class untuk mengurutkan daftar buku berdasarkan tahun terbit atau nama penulis.
   
5. **Denda Keterlambatan:** Implementasi mekanisme untuk menghitung denda keterlambatan pengembalian buku di dalam Library class.
   
6. **Penghapusan Buku:** Menambahkan method di dalam Library class untuk menghapus buku dari koleksi berdasarkan ID buku.
