# TugasPraktikum6
tugaspertemuan11

# Nama    : Dhani Naufal Habibie
# Kelas   : TI.24.A4
# NIM     : 312410300
# Matkul  : Bahasa Pemrograman
# Dosen Pengampu : Agung Nugroho, S.Kom., M.Kom.


# Latihan 1

<img width="542" alt="image" src="https://github.com/user-attachments/assets/3cc7fafd-4927-4672-afc9-8eed6ad09509">

# Kode Program

<img width="449" alt="image" src="https://github.com/user-attachments/assets/39640d69-89d8-4772-a5f3-7fb6f665ca69">

<img width="390" alt="image" src="https://github.com/user-attachments/assets/8047361f-3cca-4489-b4cd-1746a6a8d74c">

# Penjelasan kode

# 1. Variabel daftar_nilai_mahasiswa
daftar_nilai_mahasiswa = {}
- Fungsi: Variabel ini berupa dictionary kosong yang digunakan untuk menyimpan data mahasiswa.
- Key: Nama mahasiswa.
- Value: Tuple yang berisi NIM, nilai tugas, nilai UTS, dan nilai UAS.

# 2. Fungsi tambah_data()
def tambah_data():
- Fungsi: Menambahkan data mahasiswa ke dalam daftar_nilai_mahasiswa.
- Penjelasan langkah-langkah:
1. Meminta input nama, NIM, nilai tugas, UTS, dan UAS dari pengguna.
2. Memeriksa apakah nilai yang dimasukkan valid (menggunakan try dan except untuk menangani input yang bukan angka).
3. Menyimpan data mahasiswa dalam bentuk tuple ke dalam dictionary dengan nama sebagai key.
4. Menampilkan pesan bahwa data berhasil ditambahkan.     

# 3. Fungsi tampil_data()
def tampil_data():
- Fungsi: Menampilkan daftar seluruh data mahasiswa yang tersimpan di daftar_nilai_mahasiswa.
- Penjelasan langkah-langkah:
1. Mengecek apakah dictionary berisi data atau kosong.
2. Jika data ada:
    * Menampilkan header tabel.
    * Melakukan iterasi pada dictionary menggunakan for, dan menampilkan data dalam format tabel.
3. Jika kosong, menampilkan pesan bahwa tidak ada data yang tersedia.

# 4. Fungsi hapus_data()
def hapus_data():
- Fungsi: Menghapus data mahasiswa berdasarkan nama yang dimasukkan.
- Penjelasan langkah-langkah:
1. Meminta nama mahasiswa yang ingin dihapus.
2. Mengecek apakah nama ada dalam dictionary:
    * Jika ada, menghapus data dengan del.
    * Jika tidak ada, menampilkan pesan bahwa data tidak ditemukan.    

# 5. Fungsi ubah_data()
def ubah_data():
- Fungsi: Mengubah data mahasiswa yang sudah ada.
- Penjelasan langkah-langkah:
1. Meminta input nama mahasiswa.
2. Mengecek apakah nama mahasiswa ada di dictionary.
3. Jika nama ditemukan:
    * Meminta input nilai tugas, UTS, dan UAS baru.
    * Memperbarui nilai mahasiswa di dictionary.
4. Jika nama tidak ditemukan, menampilkan pesan bahwa data tidak ditemukan.    

# 6. Menu Utama (while True)
while True:
- Fungsi: Membuat menu interaktif untuk pengguna.
- Penjelasan langkah-langkah:
1. Menampilkan pilihan menu:
    - 1: Tambah data.
    - 2: Tampilkan data.
    - 3: Hapus data.
    - 4: Ubah data.
2. Meminta input dari pengguna untuk memilih opsi menu.
3. Berdasarkan pilihan:
    - Memanggil fungsi yang sesuai.
    - Jika pengguna memasukkan angka di luar 1-4, menampilkan pesan kesalahan.

# Hasil Kode Program

TAMBAH DATA

<img width="248" alt="image" src="https://github.com/user-attachments/assets/f59bbe53-7472-4839-8b3e-886ed3a5a941">

TAMPILKAN DATA

<img width="317" alt="image" src="https://github.com/user-attachments/assets/9de21f4a-a8bf-4a78-9c4d-a724515acfad">

HAPUS DATA

<img width="143" alt="image" src="https://github.com/user-attachments/assets/f9d54ef5-0b6a-43e5-b206-1f516844ecf0">

UBAH DATA

<img width="197" alt="image" src="https://github.com/user-attachments/assets/29e35960-8800-4ab8-b9e1-fbdd3ad40b97">

KELUAR

<img width="236" alt="image" src="https://github.com/user-attachments/assets/55d64db5-5abe-4946-9a35-8aa30d27c50d">

# Flowchart

![image](https://github.com/user-attachments/assets/81a83a46-7d46-4ac2-a794-82329e929c5a)




















































