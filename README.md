![codingan praktikum 6 foto](https://github.com/user-attachments/assets/9eb6c96f-d264-442d-b51c-6f8e163de45f)
![codingan praktikum 6 foto 2](https://github.com/user-attachments/assets/fe12570e-4b61-4823-bd1b-6d68bcb9cbac)
![codingan praktikum 6 foto 3](https://github.com/user-attachments/assets/9ec101b2-cc50-4df3-aa42-2ee98bb39614)
![codingan praktikum 6 foto 4](https://github.com/user-attachments/assets/3c192f26-aba2-4fc1-b23e-001183357eec)



Program ini adalah sistem manajemen data mahasiswa yang dibuat menggunakan Python. Program menyimpan data mahasiswa dalam sebuah dictionary dengan NIM sebagai kunci utama.
Setiap data mahasiswa mencakup informasi nama, nilai tugas, UTS, UAS, dan nilai akhir yang dihitung secara otomatis dengan bobot tertentu (30% tugas, 35% UTS, 35% UAS).

Program memiliki beberapa fungsi utama untuk mengelola data: menambah data mahasiswa baru, mengubah data yang sudah ada, menghapus data, mencari data berdasarkan NIM, dan
menampilkan seluruh data dalam bentuk tabel yang rapi. Saat menambah atau mengubah data, program akan meminta input berupa NIM, nama, dan nilai-nilai mahasiswa, kemudian
menghitung nilai akhir secara otomatis.

Interface program menggunakan menu berbasis teks yang sederhana dengan pilihan yang dapat diakses melalui huruf L (Lihat), T (Tambah), U (Ubah), H (Hapus), C (Cari), dan 
(Keluar). Program akan terus berjalan dalam loop sampai pengguna memilih untuk keluar. Setiap operasi dilengkapi dengan validasi input dan pesan feedback yang jelas, seperti
peringatan saat mencoba menambah NIM yang sudah ada atau mencari data yang tidak ditemukan.

CARA KERJA PROGRAM

1. Fungsi tambah_data():

Program meminta user memasukkan data mahasiswa melalui input:
Nama (input string)
Nilai Tugas (input dikonversi ke float)
Nilai UTS (input dikonversi ke float)
Nilai UAS (input dikonversi ke float)
Program menghitung nilai akhir dengan rumus:
akhir = (0.3 * tugas) + (0.35 * uts) + (0.35 * uas)
Data disimpan ke dictionary data_mahasiswa dengan format:
{"nama": nama, "tugas": tugas, "uts": uts, "uas": uas, "akhir": akhir}

2. Fungsi ubah_data():
Meminta input NIM yang ingin diubah
Mengecek apakah NIM ada dalam data_mahasiswa
Jika ada, menampilkan data lama dan meminta input data baru:

Nama baru
Nilai Tugas baru
Nilai UTS baru
Nilai UAS baru

Menghitung ulang nilai akhir
Menyimpan data yang diperbarui


3. Program menampilkan menu pilihan:
[L]ihat, [T]ambah, [U]bah, [H]apus, [C]ari, [K]eluar

4. Hasil run pada gambar menunjukkan:
User menambah 2 data mahasiswa
Melihat data dalam bentuk tabel berisi NIM, nama, nilai tugas, UTS, UAS dan nilai akhir
5. Keluar dari program
   
