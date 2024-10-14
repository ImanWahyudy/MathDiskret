---
title: Algoritma

---

# Algoritma

## Definisi Algoritma

Sebelumnya, mari kita lihat pengertian algoritma menurut ahli. Donald Ervin Knuth menyebutkan algoritma adalah sekumpulan aturan-aturan berhingga yang memberikan sederetan operasi-operasi untuk menyelesaikan masalah tertentu.

Sederhananya, algoritma adalah suatu langkah atau metode yang telah direncanakan secara matang agar berurutan dan tersusun rapi, serta sering digunakan untuk menyelesaikan suatu masalah dengan  memberikan petunjuk tindakan.

### Algoritma Sequential Search

Pengertian Sequential Search
Sequential search adalah teknik pencarian data yang dilakukan dengan cara membandingkan setiap elemen data satu per satu, mulai dari elemen pertama hingga elemen yang dicari ditemukan. Proses ini terus berlanjut hingga data ditemukan atau seluruh elemen telah diperiksa.

Algoritma ini termasuk salah satu algoritma pencarian yang paling sederhana dan sering digunakan dalam situasi di mana data tidak memiliki struktur tertentu.

### Algoritma Binary Search

pencarian biner , juga dikenal sebagai pencarian setengah interval , [ 1 ] pencarian logaritmik , [ 2 ] atau binary chop , [ 3 ] adalah algoritma pencarian yang menemukan posisi nilai target dalam array yang diurutkan . [ 4 ] [ 5 ] Pencarian biner membandingkan nilai target dengan elemen tengah array. Jika keduanya tidak sama, separuh tempat target tidak dapat berada dihilangkan dan pencarian berlanjut pada separuh sisanya, sekali lagi mengambil elemen tengah untuk dibandingkan dengan nilai target, dan mengulanginya hingga nilai target ditemukan. Jika pencarian berakhir dengan separuh sisanya kosong, target tidak ada dalam array.

Pencarian biner berjalan dalam waktu logaritmik dalam kasus terburuk , membuat O(log n)}perbandingan, dimana N
{\gaya tampilan n}adalah jumlah elemen dalam array. [ a ][ 6 ] Pencarian biner lebih cepat daripada pencarian linear kecuali untuk array kecil. Namun, array harus diurutkan terlebih dahulu untuk dapat menerapkan pencarian biner. Ada struktur data khusus yang dirancang untuk pencarian cepat, seperti tabel hash , yang dapat dicari lebih efisien daripada pencarian biner. Namun, pencarian biner dapat digunakan untuk memecahkan berbagai masalah yang lebih luas, seperti menemukan elemen terkecil berikutnya atau terbesar berikutnya dalam array relatif terhadap target bahkan jika tidak ada dalam array.Definisi Algoritma

## Pseudocode adalah....

Pseudocode adalah metodologi yang memungkinkan pengembang untuk merepresentasikan implementasi suatu algoritma. Pseudocode tidak spesifik terhadap bahasa pemrograman, sehingga dapat dipahami oleh programmer tanpa memandang latar belakang atau keahlian bahasa mereka. Ini adalah representasi kode yang dapat dipahami bahkan oleh orang awam dengan pengetahuan pemrograman yang sangat sedikit.

Pseudocode adalah implementasi algoritma dalam bentuk teks dan anotasi yang ditulis dalam bahasa Inggris biasa. Pseudocode tidak memiliki sintaksis seperti bahasa pemrograman, jadi bukan sesuatu yang dapat dikompilasi atau dijalankan di komputer.

## Big O algoritma...

“Notasi Big O adalah notasi matematika yang menggambarkan perilaku pembatas suatu fungsi ketika argumennya cenderung ke nilai tertentu atau tak terhingga. Notasi ini merupakan anggota keluarga notasi yang diciptakan oleh Paul Bachmann, Edmund Landau, dan lain-lain, yang secara kolektif disebut notasi Bachmann–Landau atau notasi asimtotik.”

— Definisi Wikipedia tentang notasi Big O

Dengan kata sederhana, notasi Big O menggambarkan kompleksitas kode Anda menggunakan istilah aljabar.

Untuk memahami apa itu notasi Big O, kita dapat melihat contoh umum, O(n²) , yang biasanya diucapkan “Big O kuadrat” . Huruf “n” di sini mewakili ukuran input , dan fungsi “g(n) = n²” di dalam “O()” memberi kita gambaran tentang seberapa rumit algoritme tersebut sehubungan dengan ukuran input.

Algoritme umum yang memiliki kompleksitas O(n²) adalah algoritme sortir pilihan . Sortir pilihan adalah algoritme sortir yang mengulangi daftar untuk memastikan setiap elemen pada indeks i adalah elemen terkecil/terbesar ke-i dari daftar.

## Hitung Big O dari ALgoritma Sequential Search
* Waktu kompleksitas (time complexity)
  Time complexity menyatakan berapa lama suatu algoritma berjalan berdasarkan banyaknya inputan yang diberikan dengan asumsi waktu yang konstan untuk tiap operasinya. Dengan kata lain jika kita memiliki inputan n=5 dan asumsi waktu 0.1 detik tiap operasi maka algoritma memerlukan waktu 0.5 detik.

Pada umumnya ketika menganalisis kompleksitas suatu algoritma akan dibagi menjadi 3 case : best-case, average-case dan worst-case.

Sebagai contoh kita akan mencari index dari sebuah angka dari list berikut [1, 4, 3, 5, 6, 9, 8, 2, 7] menggunakan linear search.

best-case: dari kasus yang kita buat, best case akan terjadi ketika inputan (angka yang dicari) bernilai 1. karena 1 merupakan value pertama dari list, sehingga program hanya membutuhkan 1 kali pencarian.
average-case: berdasarkan dari contoh diatas, kita dapat mengasumsikan bahwa average-case akan terjadi ketika value yang kita cari terletak di tengah list, pada contoh dengan value 6.
worst-case: dari contoh list diatas worst-case akan terjadi ketika value yang kita cari berada pada posisi terakhir dari list, yaitu 7.
Untuk mendeskripsikan time complexity pada suatu algoritma, umumnya kita akan menggunakan kemungkinan terburuk yang akan terjadi pada algoritma tersebut dan dideskripsikan dengan notasi Big-0.
* Ruang kompleksitas (space complexity)
  Kompleksitas Ruang adalah
Pemecahan masalah menggunakan komputer memerlukan memori untuk menampung data sementara atau hasil akhir saat program sedang dijalankan. Jumlah memori yang dibutuhkan oleh algoritma untuk menyelesaikan masalah yang diberikan disebut kompleksitas ruang algoritma.
Kompleksitas ruang suatu algoritma mengukur jumlah ruang yang diambil oleh suatu algoritma untuk dijalankan sebagai fungsi dari input panjang. Mengingatkan sebuah contoh: Memikirkan sebuah masalah untuk menemukan frekuensi elemen array .

Ini adalah jumlah memori yang dibutuhkan untuk menyelesaikan suatu algoritma. 

Untuk memenuhi kebutuhan memori, kita perlu fokus pada dua bagian: 

(1) Bagian tetap: Bagian yang tidak bergantung pada ukuran input. Bagian ini mencakup memori untuk instruksi (kode), konstanta, variabel, dll.

(2) Bagian variabel: bergantung pada ukuran input. Termasuk memori untuk tumpukan rekursi, variabel referensi, dll

## REFRENSI
https://bakrie.ac.id/programstudi-teknik-informatika
https://fikti.umsu.ac.id/algoritma-sequential-search-pengertian-fungsi-dan-cara-kerjanya/
https://en.wikipedia.org/wiki/Binary_search
https://www.ilearnengineering.com/computer/what-is-pseudocode-and-why-do-we-use-it-in-programming
https://www.freecodecamp.org/news/big-o-notation-why-it-matters-and-why-it-doesnt-1674cfa8a23c/
https://medium.com/codemi-blog/time-complexity-dan-big-o-notation-d345015d2f49
https://www.geeksforgeeks.org/time-complexity-and-space-complexity/