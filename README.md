# Penghitung Nilai Siswa

# Deskripsi Proyek

Proyek ini merupakan aplikasi Java sederhana yang digunakan untuk menghitung rata-rata nilai siswa dan menentukan apakah siswa lulus atau tidak. 
Aplikasi ini mencakup dua versi kode: Sebelum refactor dan setelah refactor 
Di mana versi setelah refactor memiliki struktur kode yang lebih terorganisir dan lebih mudah dipelihara.


## Petunjuk Instalasi
1. Pastikan kita telah menginstal [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) dan [IntelliJ IDEA](https://www.jetbrains.com/idea/).
2. Clone atau unduh proyek ini ke dalam komputer kita.
3. Buka proyek di IntelliJ IDEA atau editor teks favorit kita.


## Cara Menggunakan Aplikasi
1. Jalankan program dengan menekan tombol "Run" di IntelliJ IDEA.
2. Masukkan jumlah siswa ketika diminta.
3. Masukkan nilai masing-masing siswa satu per satu.
4. Aplikasi akan menampilkan rata-rata nilai siswa dan keterangan apakah siswa "Lulus" atau "Tidak Lulus" berdasarkan nilai rata-rata tersebut.


## Penjelasan Singkat tentang Proyek Sebelum dan Sesudah Refactor
### Sebelum Refactor
- Kode belum dipisahkan ke dalam fungsi yang lebih kecil. Semua operasi dilakukan dalam satu fungsi besar (`main`).
- Penggunaan perhitungan dan tampilan masih tercampur.
- Tidak ada penggunaan parameter pada fungsi untuk membuat kode lebih modular.

### Sesudah Refactor
- Kode dipecah menjadi beberapa fungsi kecil yang masing-masing menangani satu tugas tertentu (`getJumlahSiswa`, `calculateTotalNilai`, `calculateAverage`, `displayResult`).
- Penggunaan parameter pada fungsi-fungsi untuk meningkatkan modularitas.
- Penggunaan operator ternary untuk memperpendek penulisan logika penentuan kelulusan.
- Pemisahan fungsi tampilan (`displayResult`) untuk memisahkan logika dan antarmuka pengguna.

## Informasi Tambahan
- Proyek ini ditulis dalam bahasa pemrograman Java.
- Aplikasi ini menggunakan pendekatan refactoring untuk meningkatkan keterbacaan dan pemeliharaan kode.














### Git Branch
- git checkout -b feature-branch
- git add .
- git commit -m "Added new feature to Java project"
- git checkout master
- git merge feature-branch
- git push origin master

