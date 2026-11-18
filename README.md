# PROYEK-ARRAY-C-C2583207005
aplikasi berbasisi bahasa C untuk mengelolah stok dan penjualan produk kantin kampus menggunakan array
# SISTEM MONITORING STOK DAN PENJUALAN KANTIN KAMPUS
# Identitas Mahasiswa
- Nama: Annisa Rizkika
- NIM: C2583207005
- Kelas: PTI 3B
- Mata kuliah: Algoritma dan Pemrograman Lanjutan
- Dosen pengampu: Taofik muhammad,M.kom
# Deskripsi proyek
Program ini merupakan aplikasi console berbasis bahasa C untuk membantu pengelola kantin kampus mengelola produk, harga, stok, transaksi penjualan, pencarian produk, pengurutan, dan laporan penjualan. Data disimpan di dalam array selama program berjalan, sehingga tidak menggunakan database atau file eksternal.
# Daftar Fitur
1. Menampilkan daftar nama produk, harga, stok, dan jumlah terjual.
2. Menambahkan produk baru dengan kapasitas maksimal 50 produk.
3. Mengubah harga dan stok produk.
4. Melakukan transaksi yang berisi beberapa jenis produk.
5. Memeriksa ketersediaan stok sebelum transaksi dikonfirmasi.
6. Menambahkan stok produk.
7. Mencari produk berdasarkan nama.
8. Mengurutkan produk berdasarkan harga termurah atau jumlah terjual terbanyak.
9. Menampilkan laporan total unit, total pendapatan, dan produk terlaris.
10. Menampilkan produk yang stoknya kurang dari 5.
11. Memvalidasi input yang salah atau tidak sesuai.
# Penerapan Array
# Program menggunakan:
- char namaProduk[50][100] sebagai array karakter dua dimensi untuk menyimpan maksimal 50 nama produk.
- long long harga[50] sebagai array satu dimensi untuk menyimpan harga.
- int stok[50] sebagai array satu dimensi untuk menyimpan stok.
- int jumlahTerjual[50] sebagai array satu dimensi untuk menyimpan jumlah produk yang sudah terjual.
Indeks yang sama pada setiap array menunjukkan satu produk yang sama. Variabel jumlahProduk digunakan untuk mencatat jumlah data produk yang aktif. Data awal terdiri dari lima produk.
## Cara Menjalankan
Kompilasi program:
gcc main.c -o kantin

Jalankan program:
./kantin

# Dokumentasi pengujian 
# Tampilan
<img width="1920" height="1080" alt="Screenshot 2026-11-17 142524" src="https://github.com/user-attachments/assets/755d010e-10d6-4b8d-bd9e-5929e6bb7a51" />

# ke 1
<img width="1920" height="1080" alt="Screenshot 2026-11-17 143524" src="https://github.com/user-attachments/assets/338791c2-1e70-466e-a25f-799ce96224e9" />

# ke 2
<img width="1920" height="1080" alt="Screenshot 2026-11-17 173231" src="https://github.com/user-attachments/assets/cb87a1e1-2faa-46c7-ba23-3cf3c67ccc3f" />

# ke 3
<img width="1920" height="1080" alt="Screenshot 2026-11-17 173451" src="https://github.com/user-attachments/assets/eaeb9e00-f23f-42ea-8431-c888c32e47ff" />

# ke 4
<img width="1920" height="1080" alt="Screenshot 2026-11-17 173736" src="https://github.com/user-attachments/assets/495f99b6-ff6a-436a-8df2-dca421b33bb0" />

# ke 5
<img width="1920" height="1080" alt="Screenshot 2026-11-17 173827" src="https://github.com/user-attachments/assets/2c3af045-2307-4f17-b595-30f76b8a0426" />

# ke 6
<img width="1920" height="1080" alt="Screenshot 2026-11-17 173924" src="https://github.com/user-attachments/assets/95e750b5-e015-4efa-84fe-dbbe41cd4a7e" />

# ke 7
<img width="1920" height="1080" alt="Screenshot 2026-11-17 174009" src="https://github.com/user-attachments/assets/b22a13ca-4733-4179-ba18-908135d89104" />







