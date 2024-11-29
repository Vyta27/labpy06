# latihan 1
![Screenshot 2024-11-29 133746](https://github.com/user-attachments/assets/c5b158fc-903c-4d23-b30d-f6b39e577b4f)


- lambda a
   - Fungsi ini mengembalikan list baru yang berisi kuadrat dari setiap elemen dalam list.
     Contoh penggunaan: a([1, 2, 3, 4]) menghasilkan [1, 4, 9, 16].
- lambda b
   - Fungsi ini menghitung jarak Euclidean dari titik (x, y)ke (0, 0)
     Contoh penggunaan: b([(3, 4), (5, 12), (0, 0)])menghasilkan `[5.0, 13.0, 0.0].
- lambda c
   - Fungsi ini menghitung rata-rata dari elemen dalam list
     Contoh penggunaan: c([10, 20, 30, 40])menghasilkan 25.0.
- lambda d
   - Fungsi ini menghilangkan duplikat karakter dari setiap string dalam list.
     Contoh penggunaan: d(["hello", "world", "hello"])menghasilkan ['helo', 'wrd'].

# praktikum 6
![Screenshot 2024-11-29 140527](https://github.com/user-attachments/assets/617b769f-b6d6-4797-8385-25e2e77aa814)
![Screenshot 2024-11-29 140639](https://github.com/user-attachments/assets/264f5c45-5f25-44d0-b681-337e399581eb)
![Screenshot 2024-11-29 140738](https://github.com/user-attachments/assets/61c7a386-1269-45f2-860b-4c7068b5c1b2)

-Fungsitambah(nama, nilai) :
   -Menambahkan data siswa baru ke dalam daftar
Membuat kamus baru dengan nama dan nilai
Menggunakan append()untuk menambahkan ke daftarmahasiswa
Mencetak pesan konfirmasi bahwa data berhasil ditambahkan


Fungsitampilkan() :

Memeriksa apakah daftar mahasiswa kosong
Jika kosong, mencetak pesan "Tidak ada data siswa"
Jika ada data, menampilkan daftar siswa dengan nomor urut
Menggunakan enumerate()untuk menambahkan nomor urut pada saat mencetak


Fungsihapus(nama) :

Menghapus data siswa berdasarkan nama
Menggunakan pemahaman daftar untuk membuat daftar baru tanpa nama yang dimaksud
Memeriksa apakah data berhasil dihapus dengan membandingkan panjang daftar
Memperbarui variabel globalmahasiswa
Mencetak pesan konfirmasi atau pesan bahwa data tidak ditemukan


Fungsiubah(nama, nilai_baru) :

Mengubah nilai siswa berdasarkan nama
Melakukan iterasi di seluruh daftar siswa
Jika nama ditemukan, mengubah nilai
Mencetak pesan konfirmasi atau pesan bahwa data tidak ditemukan


Fungsimenu() :

Menampilkan menu interaktif untuk berinteraksi dengan program
Menggunakan loop while Trueuntuk terus menampilkan menu
Pilihan menu:

1: Tambah Data Mahasiswa
2: Tampilkan Semua Data
3: Hapus Data Mahasiswa
4: Ubah Data Mahasiswa
5: Keluar dari Program


Meminta masukan pengguna untuk memilih opsi
Memanggil fungsi yang sesuai berdasarkan pilihan
Memiliki validasi sederhana untuk pilihan yang tidak valid
