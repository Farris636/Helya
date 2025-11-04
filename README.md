<div align="center">

# 🩺 **Selamat Datang di Panduan**

### 🧠 **APLIKASI SISTEM INFORMASI PENGADUAN LAYANAN KESEHATAN**

*Meningkatkan Efektivitas dan Transparansi Pelayanan Publik*

</div>

---

## 📚 **Daftar Isi**

- [👥 Profil Anggota](#-profil-anggota)
- [📌 Deskripsi Project](#-deskripsi-project)
- [🎯 Tujuan Pengembangan](#-tujuan-pengembangan)
- [⚙️ Fitur Program](#️-fitur-program)
- [🧱 Penerapan OOP](#-penerapan-oop-object-oriented-programming)
- [📊 Flowchart](#-flowchart)
- [🗂️ ERD](#️-erd)
- [🧩 Use Case Diagram](#-use-case-diagram)
- [📁 Struktur Project](#-struktur-project)
- [💻 Cara Penggunaan Program](#-cara-penggunaan-program)
- [📅 Informasi Tambahan](#-informasi-tambahan)

---

## 👥 **Profil Anggota**

**Kelompok 22**

| **Nama** | **NIM** | **Kelas** | **GitHub Username** |
|-----------|----------|------------|----------------------|
| Taufik Ramadhani | 2409116001 | Sistem Informasi A '24 | [![GitHub](https://img.shields.io/badge/-Oxcyy-black?logo=github&style=flat-square)](https://github.com/Oxcyy) |
| Moch. Farris Alfiansyah | 2409116079 | Sistem Informasi B '24 | [![GitHub](https://img.shields.io/badge/-Farris636-black?logo=github&style=flat-square)](https://github.com/Farris636) |
| Ghifari Al Azhar | 2409116059 | Sistem Informasi B '24 | [![GitHub](https://img.shields.io/badge/-gfarlz-black?logo=github&style=flat-square)](https://github.com/gfarlz) |
| Yulius Pune | 2409116110 | Sistem Informasi C '24 | [![GitHub](https://img.shields.io/badge/-Oxcyy-black?logo=github&style=flat-square)](https://github.com/Oxcyy) |

---

## 📌 **Deskripsi Project**

Pelayanan publik yang **efektif, cepat tanggap, dan transparan** merupakan hal penting dalam meningkatkan kesejahteraan masyarakat. Namun, di banyak daerah terutama wilayah perbatasan proses pengaduan masyarakat masih dilakukan secara manual melalui surat, kotak saran, atau penyampaian langsung.  
Kondisi ini menyebabkan proses penanganan keluhan menjadi lambat, data mudah hilang, dan menyulitkan pihak berwenang dalam melakukan tindak lanjut laporan.

Sebagai solusi, dikembangkanlah **Sistem Informasi Pengaduan Layanan Kesehatan** berbasis online yang memungkinkan masyarakat menyampaikan pengaduan kapan saja dan di mana saja tanpa batas waktu dan jarak. Sistem ini menyimpan seluruh data secara **terpusat** menggunakan **basis data relasional (DB_HELIA)** sehingga setiap laporan dapat ditangani dengan lebih cepat, transparan, dan terukur.

Sistem ini dilengkapi dengan:
- Fitur pengaduan masyarakat dan pengaduan fasilitas kesehatan.  
- Fitur log status untuk memantau perkembangan laporan.  
- Fitur tips otomatis yang memberikan saran kesehatan sesuai keluhan.  
- Fitur admin dan ketua RT untuk mengelola dan memverifikasi pengaduan masyarakat.  

---

## 🎯 **Tujuan Pengembangan**
a. Meningkatkan efektivitas pelayanan publik dalam proses penanganan dan tindak lanjut pengaduan masyarakat di sektor kesehatan.  
b. Meningkatkan transparansi dan akuntabilitas dalam pengelolaan data pengaduan melalui sistem basis data terintegrasi.  
c. Mendukung partisipasi aktif masyarakat dalam pemantauan dan evaluasi pelayanan kesehatan di lingkungannya.

---

## ⚙️ FITUR PROGRAM
### 👤 Pengguna (Masyarakat)
- Registrasi dan login akun.
- Mengirimkan laporan pengaduan terkait fasilitas kesehatan.
- Melihat status tindak lanjut laporan secara real time.
- Mendapatkan tips otomatis sesuai jenis pengaduan.

### 🧑‍💼 Admin
- Melihat seluruh laporan yang masuk dari masyarakat.
- Memverifikasi dan memperbarui status laporan (*Menunggu, Diproses, Selesai*).
- Mengelola data pengguna dan wilayah kerja.
- Menyediakan riwayat dan statistik pengaduan.

### 👥 Ketua RT
- Mengelola laporan dari wilayahnya.
- Menjadi penghubung antara masyarakat dan admin.
- Memantau perkembangan tindak lanjut laporan.

---

## 🧱 PENERAPAN OOP (Object-Oriented Programming)
Program ini menerapkan **5 Pilar OOP**:
1. **Encapsulation** → Setiap entitas seperti *Admin*, *Pengaduan*, *RT*, dan *Tips* dibuat dalam class terpisah dengan atribut privat dan method publik.  
2. **Inheritance** → Class `Pengaduan_Faskes` dan `Pengaduan_Masyarakat` mewarisi atribut umum dari class `Pengaduan`.  
3. **Abstraction** → Fungsi-fungsi pengelolaan data (CRUD) disembunyikan di balik antarmuka database.  
4. **Polymorphism** → Method `tampilkanInfo()` digunakan secara berbeda pada setiap subclass pengaduan.  
5. **Interface** → Interface `DatabaseOperation` diterapkan untuk mengatur method standar (insert, update, delete, select).

---

## 📊 **Flowchart**
### 1. Login
<img width="416" height="603" alt="image" src="https://github.com/user-attachments/assets/30f25f36-bedf-4eee-b2aa-cc21ef1899b4" />

### 2. Menu User
<img width="826" height="726" alt="image" src="https://github.com/user-attachments/assets/3e2d73fb-531f-47e5-b67c-19859f59aabb" />

### 3. Menu Admin
<img width="990" height="732" alt="image" src="https://github.com/user-attachments/assets/a633ac51-4339-4735-863d-81825682d2b4" />

### 4. Kelola User
<img width="579" height="676" alt="image" src="https://github.com/user-attachments/assets/009f6c74-2333-4e31-8d80-d47289766b5a" />

📎 [Klik di sini untuk melihat Flowchart Lengkap](https://app.diagrams.net/?src=about#G1l_0vRv375RYu1bvGWVfsu-FzTx-2HyA5#%7B%22pageId%22%3A%22YSO67Ypj2ylAbOuhdHeY%22%7D)

---

## 🗂️ **ERD**
Entitas utama sistem:
- **Admin**
- **Ketua_RT**
- **Pengaduan_Faskes**
- **Pengaduan_Masyarakat**
- **Log_Status**
- **Tips_Otomatis**

Relasi utama:
- `Users` ↔ `Admin` (1:1)  
- `Users` ↔ `Ketua_RT` (1:1)  
- `Users` ↔ `Pengaduan` (1:N)  
- `Pengaduan` ↔ `Log_Status` (1:N)  
- `Pengaduan_Masyarakat` ↔ `Tips_Otomatis` (N:M)
  

📌 **ERD LOGICAL**

<img width="491" height="772" alt="image" src="https://github.com/user-attachments/assets/563eefd2-d33a-4f38-864b-2d4c26030152" />


📌 **ERD RELATIONAL**

<img width="569" height="785" alt="image" src="https://github.com/user-attachments/assets/07dae1e0-0166-4830-a278-d5d173b74e04" />

📎 [Klik di sini untuk melihat ERD Logical dan Relasional](https://app.diagrams.net/)

---

## 🧩 **Use Case Diagram**
> Berikut merupakan ilustrasi hubungan antara aktor (Admin, Ketua RT, dan Pengguna) dengan fungsionalitas utama dalam sistem pengaduan layanan kesehatan.

<img width="1002" height="636" alt="image" src="https://github.com/user-attachments/assets/e5f203c9-59b0-4439-a096-949e50e1d6f8" />

## 📁 **Struktur Project**


## 💻 **Cara Penggunaan Program**
### 👥 Ketua RT
**🔐Login**
<img width="1000" height="750" alt="image" src="https://github.com/user-attachments/assets/8e7ca564-19c0-43c6-b0e0-fdd2f6844dcf" />

Panduan awal penggunaan aplikasi HELYA dimulai dengan proses login melalui halaman utama. Pengguna diminta untuk mengisi kolom Username dan Password sesuai data yang telah terdaftar, kemudian menekan tombol Login untuk mengakses sistem. Setelah berhasil masuk, pengguna dapat melanjutkan ke fitur utama seperti pelaporan kondisi kesehatan pribadi maupun fasilitas kesehatan di lingkungan sekitar. Tampilan yang sederhana dan terpusat memudahkan proses autentikasi awal serta memastikan pengalaman penggunaan yang cepat dan efisien.

<img width="999" height="750" alt="image" src="https://github.com/user-attachments/assets/791d11ac-5729-4072-94c9-ca0083ff39c2" />

<img width="1003" height="751" alt="image" src="https://github.com/user-attachments/assets/aedffaea-10bb-491f-a4bb-5ee8d2731d93" />

**👨🏻‍💼Admin**

Halaman Dashboard Admin HELYA menampilkan ringkasan data pengaduan kesehatan masyarakat dan fasilitas kesehatan, termasuk jumlah laporan, status penanganan, serta grafik perbandingan. Menu di sisi kiri memudahkan akses ke fitur Dashboard, Manajemen Akun, dan Manajemen Pengaduan, dengan desain sederhana dan informatif untuk mendukung pemantauan data secara efisien.

<img width="991" height="701" alt="image" src="https://github.com/user-attachments/assets/641636c9-f6a5-476d-b6c3-63ecaa120acc" />

<details>
  <summary>1️⃣ Dashboard</summary>

  <img width="986" height="700" alt="image" src="https://github.com/user-attachments/assets/d0602f5d-3270-4bdd-bf68-98ddbb63caf1" />

  Halaman Dashboard Admin HELYA berfungsi sebagai pusat pemantauan seluruh aktivitas pengaduan kesehatan di wilayah kerja. Tampilan ini menampilkan informasi statistik berupa jumlah pengaduan dari masyarakat dan fasilitas kesehatan, status penanganan laporan, serta grafik perbandingan jenis pengaduan dan jumlah pengaduan berdasarkan sumbernya. Desain dashboard menggunakan warna yang kontras untuk membedakan kategori dan status, seperti hijau untuk laporan selesai, kuning untuk sedang diproses, dan merah untuk belum diperiksa. Melalui tampilan ini, admin dapat dengan mudah memantau, menganalisis, dan mengevaluasi perkembangan penanganan pengaduan secara cepat dan efisien.
</details>

<details>
  <summary>2️⃣ Manajemen Akun</summary>

  <img width="988" height="696" alt="image" src="https://github.com/user-attachments/assets/4b063a16-da5d-4f3e-ab4d-5a05600fdcf4" />

  Halaman Manajemen Akun berfungsi untuk mengelola data pengguna dalam sistem HELYA, khususnya akun ketua RT yang bertugas memantau dan menindaklanjuti laporan kesehatan di wilayahnya. Tampilan ini menyediakan fitur pencarian berdasarkan nama, serta tombol untuk menambah, memperbarui, dan menghapus akun pengguna. Setiap data ditampilkan dalam tabel berisi nomor, nama, nomor RT, serta opsi tindakan. Desain halaman dibuat sederhana dan terstruktur agar admin dapat melakukan pengelolaan akun dengan cepat, akurat, dan efisien.
  

<img width="986" height="701" alt="image" src="https://github.com/user-attachments/assets/5e9174eb-c608-482e-99be-0061f6ff2042" />

Admin dapat mencari akun pengguna dengan mengetikkan nama akun penggunanya.


<img width="994" height="697" alt="image" src="https://github.com/user-attachments/assets/096617f5-c8ca-4d38-811f-2ba82d4419fd" />

Admin dapat menambahkan akun pengguna baru dengan mengklik tanda +(plus).


<img width="988" height="703" alt="image" src="https://github.com/user-attachments/assets/5ad64552-ba60-4c57-b37b-9c12fc2a324b" />

Admin dapat mengubah data dari akun pengguna dengan mengklik tanda pensil.


<img width="989" height="700" alt="image" src="https://github.com/user-attachments/assets/200af82b-e454-452b-baf8-b115bb1e9bda" />

Admin dapat menghapus akun pengguna yang sudah ada dengan mengklik icon sampah.
</details>

<details>
  <summary>3️⃣ Manajemen Pengaduan</summary>

  <img width="988" height="703" alt="image" src="https://github.com/user-attachments/assets/cf78a4cd-645d-45b9-aa1f-df984ea2732a" />

  Halaman Manajemen Pengaduan digunakan untuk memantau dan memperbarui data laporan kesehatan masyarakat maupun fasilitas kesehatan. Setiap pengaduan ditampilkan dalam tabel berisi nama pelapor, tipe aduan, serta status penanganan yang ditandai dengan warna berbeda agar mudah diidentifikasi. Fitur pencarian dan pembaruan data disediakan untuk mempermudah admin dalam mengelola dan menindaklanjuti setiap laporan secara cepat dan efisien.


  <img width="986" height="698" alt="image" src="https://github.com/user-attachments/assets/06b56d3f-8c8e-4641-bd79-cb45027247f5" />
  
  Admin dapat mencari jenis pengaduan yang ada dengan memasukkan kata kunci pada search bar.


  <img width="989" height="701" alt="image" src="https://github.com/user-attachments/assets/e424cf55-7ef8-485c-933c-28e80345b805" />

  Admin dapat menggunakan filter untuk menampilkan data sesuai dengan yang diinginkan seperti sesuai urutan nama, pengaduan dan statusnya.


  <img width="985" height="700" alt="image" src="https://github.com/user-attachments/assets/0198715e-045c-481a-971f-33b229bdffa2" />

  Admin dapat mengudah status dari pengaduan yang telah diinput oleh ketua rt.
</details>

<details>
  <summary>4️⃣ Keluar</summary>

  <img width="986" height="704" alt="image" src="https://github.com/user-attachments/assets/271b6452-1e0c-405b-ab5b-aca4b6f38fe6" />

  Untuk keluar dari program silahkan klik icon pintu pada pojok kiri bawah dengan label keluar.  
</details>


**👨🏻‍💻Ketua_RT**

<img width="1001" height="875" alt="image" src="https://github.com/user-attachments/assets/a2e8b0fc-14cf-4575-b6ee-0be2285211b5" />

Tampilan awal ketika login sebagai Ketua RT menampilkan halaman utama layanan pengaduan kesehatan dan fasilitas masyarakat di wilayah Kalimantan Timur. Halaman ini menyediakan dua pilihan utama, yaitu Pengaduan Kesehatan dan Pengaduan Fasilitas, yang memudahkan pengguna untuk melaporkan permasalahan sesuai kategori. Di bagian bawah, terdapat tabel Riwayat Pengaduan yang menampilkan daftar laporan sebelumnya lengkap dengan nama pelapor, tipe aduan, status, dan tombol detail. Desain dibuat sederhana, informatif, dan responsif agar Ketua RT dapat mengakses data dan mengirim laporan dengan mudah serta cepat.


<details>
  <summary>1️⃣ Pengaduan Kesehatan Masyarakat</summary>

  <img width="988" height="705" alt="image" src="https://github.com/user-attachments/assets/8a9ad65c-7a97-4905-a4f9-d8642de0b691" />

  Ketua rt dapat membuat pengaduan kesehatan masyarakat dengan mengklik pengaduan kesehatan dan memasukkan data yang diminta.
</details>

<details>
  <summary>2️⃣ Pengaduan Fasilitas</summary>
  <img width="984" height="705" alt="image" src="https://github.com/user-attachments/assets/c431e094-efa8-487b-a3cf-e22134646016" />

  Ketua rt dapat membuat pengaduan tentang fasilitas yang ada pada daerahnya masing-masing dengan mengklik pengaduan fasilitas.
</details>

<details>
  <summary>4️⃣ Keluar</summary>

  <img width="1001" height="869" alt="image" src="https://github.com/user-attachments/assets/b7c23722-f35d-4efd-9f95-0f86349036d8" />


  Untuk keluar dari program silahkan klik icon pintu pada pojok kanan atas dengan label keluar.  
</details>


## 📅 **Informasi Tambahan**
🧩 **Kebutuhan Sistem**

Sebelum menjalankan program **Sistem Informasi Pengaduan Layanan Kesehatan**, pastinya kami menggunakan beberapa perangkat yang sudah memenuhi beberapa kebutuhan sistem berikut:

- **🧱 JDK 23**  
  Java Development Kit (JDK) berisi kompiler *javac*, pustaka standar Java, serta alat bantu lain yang diperlukan untuk menulis, menjalankan, dan menguji program berbasis Java.

- **🖥️ NetBeans IDE 22**  
  NetBeans merupakan lingkungan pengembangan terintegrasi (IDE) yang mendukung berbagai bahasa pemrograman seperti Java, PHP, dan C++.  
  Versi terbaru memiliki fitur untuk *debugging*, integrasi Git, dan pengembangan aplikasi berbasis web maupun desktop.

- **⚙️ XAMPP**  
  Diperlukan untuk menjalankan aplikasi yang membutuhkan server web, basis data, serta bahasa pemrograman *server-side*.  
  XAMPP mempermudah proses konfigurasi dan pengelolaan lingkungan pengembangan.

- **💾 MySQL**  
  Merupakan sistem manajemen basis data relasional (RDBMS) yang menggunakan bahasa SQL.  
  MySQL berfungsi untuk menyimpan, mengatur, dan mengelola data agar tetap akurat, aman, serta mudah diakses kapan pun dibutuhkan.

- **🔗 MySQL Connector (JDBC)**  
  Pustaka tambahan yang digunakan untuk menghubungkan aplikasi Java dengan basis data MySQL.  
  Dengan konektor ini, aplikasi dapat melakukan proses komunikasi dan pertukaran data dengan database secara langsung.

---


###

[⬆️ Kembali ke Awal](#-selamat-datang-di-panduan)
