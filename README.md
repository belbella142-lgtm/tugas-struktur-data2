Program ini adalah latihan dasar Python yang mencakup berbagai fungsi untuk pengolahan data dan satu aplikasi berbasis menu yang sederhana. Pengguna dapat memilih fitur tertentu, menginput data, dan program akan menampilkan hasil sesuai dengan pilihan yang dibuat.

Program ini akan berjalan secara berulang (loop) sampai pengguna memilih untuk keluar.

Penjelasan ini berhubungan dengan kode dalam file latihan soal. py

1. Fungsi `deduplikasi(lst)`

Tujuan :
Menghapus data yang sama dalam sebuah list.

Cara kerja :

Menciptakan list kosong bernama `hasil`
Melakukan loop untuk setiap elemen dalam `lst`
Jika elemen belum ada dalam `hasil`, maka elemen tersebut ditambahkan
Mengembalikan list `hasil` yang hanya berisi elemen-elemen unik

Hasil yang diharapkan :
List baru yang tidak memiliki angka yang terulang, dengan urutan tetap seperti input awal.

2. Fungsi `intersection(arr1, arr2)`

Tujuan :
Menemukan irisan (intersection) dari dua list.

Cara kerja :

Membuat list kosong `hasil`
Memeriksa setiap elemen dalam `arr1`
Jika elemen tersebut ada di `arr2` dan belum terdapat dalam `hasil`, maka ditambahkan
Menghindari kemunculan ganda dalam hasil

Hasil yang diharapkan :
List yang berisi elemen-elemen yang ada di kedua list.

3. Fungsi `is_anagram(s1, s2)`

Tujuan :
Menentukan apakah dua string dapat disebut anagram.

Cara kerja :

Mengatur karakter dari kedua string dengan menggunakan `sorted()`
Membandingkan urutan karakter yang dihasilkan
Jika hasilnya sama → `True`, jika tidak → `False`

Hasil yang diharapkan :
Nilai boolean:

`True` → kedua string merupakan anagram
`False` → bukan anagram

4. Fungsi `first_recurring_char(s)`

Tujuan :
Mencari karakter pertama yang muncul lebih dari sekali dalam sebuah string.

Cara kerja :

Memanfaatkan dua loop bersarang
Karakter pada indeks `i` dibandingkan dengan karakter sesudahnya
Jika ditemukan karakter yang sama → segera dikembalikan
Jika tidak ada karakter yang berulang → mengembalikan `None`

Hasil yang diharapkan :
Satu karakter yang muncul pertama kali secara berulang, atau `None` jika tidak ada yang berulang.

5. Fungsi `buku_telepon()`

Tujuan :
Membangun aplikasi buku telepon sederhana.

Struktur data :
Menggunakan dictionary (`kontak`)

Key → nama
Value → nomor telepon

Menu di dalam buku telepon:

1. Tambah → menyimpan nama dan nomor telepon
2. Cari → menampilkan nomor telepon berdasarkan nama
3. Tampilkan → menampilkan semua kontak yang ada
4. Keluar → kembali ke menu utama

Hasil yang diharapkan :
Pengguna bisa menyimpan, mencari, dan melihat informasi kontak selama program aktif.

6. Menu Utama Program

Tujuan :
Mengintegrasikan semua fungsi ke dalam satu sistem menu.

Cara kerja :
Menggunakan `while True` agar program tetap berjalan
Menampilkan daftar menu yang tersedia
Memanggil fungsi sesuai dengan pilihan pengguna
Program akan berhenti jika pengguna memilih opsi Keluar

Hasil keseluruhan :
Program berbasis teks yang interaktif yang memungkinkan pengguna:

Mengelola list
Memeriksa anagram
Menganalisis string
Mengorganisasi data kontak sederhana

Kesimpulan :
Mengoptimalkan fungsi dengan benar
Memanfaatkan list, string, dan dictionary
Menerapkan logika dasar Python
Mengintegrasikan menu interaktif yang terstruktur dengan baik

Program ini sangat tepat untuk latihan dasar algoritma dan struktur data Python

Jika kamu tertarik, saya bisa:

Menyusun versi analisis laporan praktikum
Menjelaskan input dan output setiap menu dalam bentuk paragraf
Atau menyederhanakan kode agar lebih efisien
