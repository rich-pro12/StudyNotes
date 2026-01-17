# StudyNotes
# Laporan Aplikasi Study Notes

## 1. Pendahuluan
Aplikasi **Study Notes** merupakan aplikasi mobile berbasis Android yang dibuat untuk membantu pengguna dalam mencatat, menyimpan, dan mengelola catatan belajar secara sederhana dan praktis.  
Aplikasi ini dirancang agar mudah digunakan oleh pelajar atau mahasiswa yang ingin menyimpan catatan penting langsung di dalam smartphone.

Study Notes dikembangkan menggunakan **Android Studio** dengan bahasa pemrograman **Java** serta menggunakan **SQLite** sebagai database lokal untuk menyimpan data catatan.

---

## 2. Tujuan Pembuatan Aplikasi
Tujuan utama dari pembuatan aplikasi Study Notes adalah:
- Membantu pengguna menyimpan catatan belajar secara digital
- Mempermudah pengelolaan catatan (menambah, melihat, dan menghapus)
- Melatih pemahaman konsep CRUD (Create, Read, Delete) dalam Android
- Mengimplementasikan penggunaan database SQLite dalam aplikasi Android

---

## 3. Fitur Utama Aplikasi
Aplikasi Study Notes memiliki beberapa fitur utama, yaitu:

### 3.1 Menambahkan Catatan
Pengguna dapat membuat catatan baru dengan mengisi:
- Kategori catatan
- Judul catatan
- Isi catatan

Setelah disimpan, catatan akan otomatis masuk ke database dan ditampilkan di halaman Home.

---

### 3.2 Menampilkan Daftar Catatan (Home)
Halaman Home berfungsi untuk:
- Menampilkan seluruh catatan yang telah disimpan
- Menampilkan data dalam bentuk daftar menggunakan RecyclerView
- Menampilkan catatan terbaru di urutan paling atas

Data yang ditampilkan di Home diambil langsung dari database SQLite.

---

### 3.3 Halaman Profile (Manajemen Catatan)
Halaman Profile berfungsi sebagai:
- Tempat melihat seluruh catatan yang tersimpan
- Tempat menghapus catatan yang tidak diperlukan

Jika catatan dihapus dari halaman Profile, maka:
- Catatan tersebut otomatis terhapus dari database
- Data di halaman Home juga ikut berkurang secara otomatis

Hal ini memastikan bahwa data di semua halaman selalu sinkron.

---

## 4. Penjelasan Alur Aplikasi
Berikut alur penggunaan aplikasi Study Notes:

1. Aplikasi dibuka oleh pengguna
2. Pengguna masuk ke halaman Home
3. Pengguna menekan tombol tambah untuk membuat catatan baru
4. Catatan disimpan ke database SQLite
5. Setelah disimpan, pengguna kembali ke Home
6. Catatan baru langsung tampil di Home
7. Pengguna dapat membuka halaman Profile untuk melihat atau menghapus catatan
8. Jika catatan dihapus, maka data akan otomatis terhapus di Home dan Profile

---

## 5. Penggunaan Database SQLite
Aplikasi ini menggunakan **SQLite** sebagai database lokal dengan tujuan:
- Menyimpan data catatan secara permanen
- Tidak membutuhkan koneksi internet
- Data tetap ada meskipun aplikasi ditutup

Data yang disimpan dalam database meliputi:
- ID catatan
- Judul catatan
- Kategori catatan
- Isi catatan
- Tanggal pembuatan catatan

---

## 6. Kesimpulan
Aplikasi Study Notes merupakan aplikasi pencatatan sederhana yang mampu membantu pengguna dalam menyimpan dan mengelola catatan belajar secara efektif.  
Dengan adanya fitur tambah, lihat, dan hapus catatan yang terhubung langsung dengan database SQLite, aplikasi ini mampu menerapkan konsep dasar pengembangan aplikasi Android dengan baik.

Aplikasi ini diharapkan dapat menjadi dasar pembelajaran untuk pengembangan aplikasi Android yang lebih kompleks di masa mendatang.

---

## 7. Penutup
Demikian laporan pembuatan aplikasi Study Notes ini disusun sebagai bentuk pemenuhan tugas Ujian Akhir Semester (UAS).  
Semoga aplikasi dan laporan ini dapat memberikan manfaat serta pemahaman mengenai pengembangan aplikasi Android berbasis database.
