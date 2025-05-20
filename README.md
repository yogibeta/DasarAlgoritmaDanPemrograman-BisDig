# DasarAlgoritmaDanPemrograman-BisDig

penjelasan dalam soal uts

Untuk memberikan diskon dalam konteks sistem e-commerce, kita dapat menggunakan struktur kontrol percabangan dalam Python, yaitu if statement. Struktur ini memungkinkan kita untuk memeriksa apakah total belanja memenuhi syarat untuk mendapatkan diskon.

Logika Pemberian Diskon

Jika total belanja lebih dari Rp500.000, maka pelanggan berhak mendapatkan diskon 10%.

Jika tidak, total belanja tetap dan tidak ada diskon.

Program Python untuk Menghitung Total Bayar Setelah Diskon

Tipe data menentukan jenis nilai yang dapat disimpan dalam variabel. Dalam studi kasus ini: • Integer (int): digunakan untuk menyimpan nilai ujian (misalnya: 80, 75, 90). • Float (float): digunakan jika nilai ujian mengandung desimal (misalnya: 76.5). • Boolean (bool): digunakan untuk menyimpan hasil logika, seperti apakah siswa lulus atau tidak (True/False). • String (str) (opsional): bisa digunakan untuk menyimpan nama siswa atau keterangan seperti “Lulus” / “Tidak Lulus”.

Manfaat Penggunaan Fungsi dalam Menghitung Faktorial

Modularitas: Fungsi memungkinkan kita memecah program menjadi bagian-bagian yang lebih kecil. Ini membuat kode lebih mudah dibaca, dimengerti, dan dirawat.

Reusabilitas: Sekali kita mendefinisikan fungsi untuk menghitung faktorial, kita dapat menggunakannya berulang kali tanpa menulis ulang kode, yang menghemat waktu dan upaya.

Abstraksi: Dengan fungsi, pengguna tidak perlu mengetahui detail implementasi untuk menggunakan fungsionalitas. Mereka cukup memanggil fungsi dengan parameter yang sesuai.

Pengurangan Kesalahan: Menggunakan fungsi dapat mengurangi kesalahan, karena logika faktorial terpusat dalam satu tempat. Jika ada kesalahan, kita hanya perlu memperbaiki fungsi tersebut.

Cara Kerja Rekursi dalam Menghitung Faktorial Untuk menghitung faktorial menggunakan rekursi, kita perlu mendefinisikan dua hal:

Kasus Dasar: Ini adalah kondisi untuk menghentikan pemanggilan fungsi. Untuk faktorial, kita dapat menetapkan bahwa ( 0! = 1 ) dan ( 1! = 1 ).

Kasus Rekursif: Ini menjelaskan bagaimana fungsi berfungsi untuk bilangan yang lebih besar berdasarkan nilai yang lebih kecil. Untuk faktorial, kita dapat mendefinisikan bahwa ( n! = n \times (n-1)! ). Contoh Implementasi Rekursif

Berikut adalah contoh kode dalam Python untuk menghitung faktorial dengan rekursi:
python def faktorial(n): if n == 0 or n == 1: # Kasus dasar return 1 else: # Kasus rekursif return n * faktorial(n - 1)

Contoh penggunaan print(faktorial(5)) # Output: 120

Penggunaan Array Array (atau list dalam Python) digunakan untuk menyimpan nilai-nilai yang dimasukkan oleh siswa. Kita akan membuat sebuah list yang akan menyimpan 5 nilai yang diinput oleh pengguna. Dengan cara ini, semua nilai dapat diakses dan dikelola dengan mudah.

Penggunaan Perulangan Perulangan akan digunakan untuk meminta input dari pengguna sebanyak 5 kali. Kita dapat menggunakan for loop untuk melakukannya. Setiap nilai yang dimasukkan akan disimpan dalam array (list).

Langkah-langkah Algoritma

Inisialisasi Variabel:
Siapkan variabel untuk menyimpan harga masing-masing barang. Misalnya, harga_barang1, harga_barang2, dan harga_barang3.
Siapkan variabel untuk menyimpan total harga, misalnya total_harga.
Input Harga Barang:
Minta pengguna untuk memasukkan harga barang ke-1.
Simpan harga ke dalam variabel harga_barang1.
Minta pengguna untuk memasukkan harga barang ke-2.
Simpan harga ke dalam variabel harga_barang2.
Minta pengguna untuk memasukkan harga barang ke-3.
Simpan harga ke dalam variabel harga_barang3.
Hitung Total Harga:
Jumlahkan harga ketiga barang untuk mendapatkan total harga.
Total_harga = harga_barang1 + harga_barang2 + harga_barang3.
Tampilkan Total Harga:
Tampilkan hasil total harga kepada pengguna.
