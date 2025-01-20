# praktikum_8

## Menambahkan Data Mahasiswa
![Screenshot (148)](https://github.com/user-attachments/assets/ead0aa1b-8994-4c11-a1a2-99a5a8a31fb7)

## Menambahkan Nilai Mahasiswa
![Screenshot (149)](https://github.com/user-attachments/assets/cff61073-baf5-4b57-b9dd-9cd5d17e8c95)

**Deskripsi Proyek Praktikum 8**

Proyek ini adalah aplikasi berbasis Java yang berfungsi untuk mengelola data mahasiswa dan nilai mereka. Aplikasi ini menggunakan arsitektur Model-View-Controller (MVC) untuk memisahkan logika bisnis, tampilan, dan pengendalian alur aplikasi.

### **Struktur Proyek**
- **Folder `.git`**: Menyimpan informasi kontrol versi menggunakan Git.
- **Folder `.vscode`**: Menyimpan konfigurasi untuk Visual Studio Code, termasuk pengaturan proyek dan file peluncuran.
- **Folder `classes`**: Berisi kelas-kelas dasar untuk koneksi database dan pemetaan hasil query.
- **Folder `controller`**: Berisi kelas pengendali yang menghubungkan model dan tampilan.
- **Folder `model`**: Berisi kelas yang merepresentasikan data mahasiswa dan nilai, serta model untuk interaksi dengan database.
- **Folder `view`**: Berisi kelas untuk tampilan antarmuka pengguna (UI) menggunakan Swing.
- **File `Main.java`**: Titik masuk aplikasi yang menginisialisasi koneksi database dan menampilkan antarmuka pengguna.
- **File `TestConnection.java`**: Digunakan untuk menguji koneksi ke database.

### **Fungsi Utama**
- **Koneksi Database**: Kelas `Database` mengelola koneksi ke database MySQL.
- **Model Data**: Kelas `Mahasiswa` dan `Nilai` merepresentasikan entitas mahasiswa dan nilai, sedangkan `MahasiswaModel` dan `NilaiModel` mengelola operasi CRUD (Create, Read, Update, Delete) untuk masing-masing entitas.
- **Pengendali**: Kelas `MahasiswaController` dan `NilaiController` mengatur interaksi antara model dan tampilan, menangani event dari pengguna, dan memperbarui tampilan sesuai dengan data yang diambil dari model.
- **Tampilan**: Kelas `FormMahasiswa` dan `FormNilai` menyediakan antarmuka pengguna untuk memasukkan dan menampilkan data mahasiswa dan nilai.

### **Fitur Aplikasi**
- Menambahkan, mengedit, dan menghapus data mahasiswa.
- Menampilkan daftar mahasiswa dalam tabel.
- Menambahkan, mengedit, dan menghapus nilai untuk mahasiswa tertentu.
- Validasi input untuk memastikan data yang dimasukkan sesuai dengan kriteria yang ditentukan.

### **Penggunaan**
1. **Menjalankan Aplikasi**: Pengguna dapat menjalankan aplikasi melalui `Main.java`, yang akan membuka antarmuka pengguna.
2. **Interaksi Pengguna**: Pengguna dapat menggunakan tombol untuk menyimpan, menghapus, atau melihat nilai mahasiswa.
3. **Koneksi Database**: Aplikasi terhubung ke database MySQL yang harus dikonfigurasi sebelumnya.

### **Kesimpulan**
Proyek ini adalah contoh aplikasi sederhana yang mengimplementasikan konsep OOP (Object-Oriented Programming) dan arsitektur MVC dalam pengembangan perangkat lunak. Aplikasi ini dapat dikembangkan lebih lanjut dengan menambahkan fitur-fitur tambahan seperti autentikasi pengguna, laporan, dan lain-lain.
