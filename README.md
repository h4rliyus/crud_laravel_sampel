# crud_laravel_sampel
CRUD_Laravel_Sampel merupakan aplikasi web sederhana yang dibangun menggunakan framework Laravel 12 dengan bahasa pemrograman PHP 8.2 dan database MySQL. Aplikasi ini digunakan untuk mengelola data mahasiswa melalui fitur dasar CRUD (Create, Read, Update, Delete).

Sistem menyediakan fasilitas untuk menambah data mahasiswa, menampilkan daftar data mahasiswa, mengubah data mahasiswa, dan menghapus data mahasiswa yang tersimpan dalam database. Antarmuka pengguna dirancang menggunakan Bootstrap 5 sehingga tampilan menjadi lebih responsif, rapi, dan mudah digunakan. Selain itu, JavaScript digunakan untuk mendukung interaksi pengguna, seperti konfirmasi penghapusan data dan validasi sederhana pada form.

# Fitur Utama
# Tambah Data (Create)
Menambahkan data mahasiswa baru ke dalam database.
Data yang diinput meliputi NIM, Nama, Tanggal Lahir, dan Program Studi.
# Tampil Data (Read)
Menampilkan seluruh data mahasiswa dalam bentuk tabel.
Data diambil secara langsung dari database MySQL menggunakan Eloquent ORM Laravel.
# Edit Data (Update)
Mengubah data mahasiswa yang telah tersimpan.
Perubahan data akan langsung diperbarui pada database.
# Hapus Data (Delete)
Menghapus data mahasiswa dari database.
Dilengkapi dengan konfirmasi penghapusan menggunakan JavaScript untuk menghindari kesalahan pengguna.

<img width="928" height="223" alt="image" src="https://github.com/user-attachments/assets/edeb3f41-781d-41a3-a06a-ad50cc2772b4" />


# Teknologi yang Digunakan
PHP 8.2	Bahasa pemrograman utama
Laravel 12	Framework PHP berbasis MVC
MySQL	Sistem manajemen basis data
Bootstrap 5	Framework CSS untuk tampilan responsif
JavaScript	Interaktivitas dan validasi sisi klien
HTML5	Struktur halaman web

#Struktur Data
Tabel mahasiswa terdiri dari beberapa atribut, yaitu:

nim : Nomor Induk Mahasiswa
nama : Nama Mahasiswa
tanggal_lahir : Tanggal Lahir Mahasiswa
program_studi : Program Studi Mahasiswa

# Tujuan Pengembangan
Aplikasi CRUD_Laravel_Sampel dibuat sebagai contoh implementasi dasar framework Laravel dalam pengembangan aplikasi berbasis web yang menerapkan konsep MVC (Model-View-Controller). Proyek ini dapat digunakan sebagai media pembelajaran untuk memahami integrasi antara Laravel, MySQL, Bootstrap, dan JavaScript dalam membangun aplikasi pengelolaan data yang sederhana namun terstruktur.

Berdasarkan tampilan yang ditunjukkan, aplikasi menampilkan data mahasiswa dalam bentuk tabel dengan tombol Tambah Data, Edit, dan Hapus, sehingga seluruh proses pengelolaan data dapat dilakukan melalui antarmuka web secara mudah dan efisien.
