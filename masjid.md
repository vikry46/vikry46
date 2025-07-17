## Sistem Pengelolaan Data Masjid

**Proyek pertama saya: Aplikasi Pengelolaan Masjid.**  
Dibuat sebagai Tugas Akhir dengan tujuan membantu masyarakat perantau memantau kegiatan, laporan keuangan, dan informasi masjid secara online. Sistem ini menggantikan proses manual, menuju manajemen yang lebih efisien, transparan, dan akuntabel.

Aplikasi ini dibangun menggunakan **framework Laravel** dan telah saya unggah ke repository dengan judul **Finising Mesjid**.

---

### 🎯 Fitur Utama

- **Halaman Home** berisi visi dan misi masjid.
- **Halaman Berita**: Informasi keuangan, kegiatan, dan berita penting lainnya.
- **Halaman Kontak**: Formulir pesan dari user untuk pihak masjid.
- **Halaman Login Admin**: Akses ke sistem manajemen internal.

---

### 📸 Tampilan Aplikasi

#### 🏠 Halaman Home (Visi & Misi)
![Home](img/Home.PNG)

#### 🔐 Halaman Login
![Login](img/login.PNG)

#### 📊 Dashboard Utama
![Dashboard](img/dasbord.PNG)

#### 👥 Pengurus & Jabatan
Terdapat CRUD data pengurus serta jabatan:
![Pengurus](img/pengurus.PNG)  
![Create Jabatan](img/createjabatan.PNG)  
![Create Pengurus](img/createpengurus.PNG)

#### 👳‍♂️ Data Ustadz
CRUD nama ustadz yang akan mengisi kegiatan seperti khutbah Jumat (ditampilkan juga di halaman berita):
![Ustadz](img/ust.PNG)

#### 📅 Jenis Kegiatan
Berisi CRUD jenis kegiatan sebagai relasi ke halaman kegiatan:
![Jenis Kegiatan](img/kegiatan.PNG)

#### 🗓️ Kegiatan
CRUD kegiatan dalam bentuk kalender agar efisien, dengan fitur klik tanggal untuk melihat detail acara:
![Kalender Kegiatan](img/tangal.PNG)  
![Detail Kegiatan](img/tgcrud.PNG)

#### 💰 Keuangan
Terdapat halaman laporan dan CRUD transaksi keuangan:
![Laporan Keuangan](img/keuangan.PNG)  
![CRUD Keuangan](img/mesjid.PNG)

#### 🔐 Hak Akses (Role Management)
Tampilan CRUD hak akses, diatur oleh Super Admin (Ketua Pengurus), contoh: Bendahara hanya bisa mengelola keuangan:
![Role List](img/role.PNG)  
![Role Detail](img/rolrole.PNG)

#### 👤 Manajemen Akun Login
Form untuk membuat akun login user lain, dikelola oleh Super Admin:
![Login User](img/login.PNG)

#### 💬 Pesan dari User (Kontak)
Halaman untuk membaca pesan dari pengguna umum:
![Pesan](img/pesan.PNG)

---

📬 **Terima kasih** telah melihat proyek ini.  
Saya sangat menghargai saran, kritik, dan masukan untuk pengembangan lebih lanjut.

