
# Sistem Informasi Inventaris Barang Toko Grosir 2R

## Deskripsi Proyek
Proyek ini merupakan Sistem Informasi Inventaris Barang yang dirancang untuk Toko Grosir 2R. Sistem ini dikembangkan sebagai bagian dari Ujian Akhir Semester Mata Kuliah Pemrograman Web. Tujuan dari sistem ini adalah untuk mempermudah pengelolaan data inventaris barang di toko grosir, seperti pencatatan, pembaruan, dan penghapusan data barang secara efisien.

## Teknologi yang Digunakan
- **Backend**: PHP dengan Framework CodeIgniter 3
- **Frontend**: CSS dengan Bootstrap 4

## Fitur Utama
1. **Pengelolaan Data**:
   - Satuan Barang
   - Jenis Barang
   - Suplier
   - Barang
   - Transaksi Masuk
   - Transaksi Keluar

2. **Pencarian**:
   - Pencarian data produk berdasarkan nama atau kategori.

3. **Laporan**:
   - Laporan berdasarkan filter tanggal.
   - Cetak laporan dalam format PDF 

## Cara Instalasi
1. Clone repositori ini ke local directory Anda:
   ```bash
   git clone https://github.com/username/Inventaris-Barang-Toko-Grosir.git
   ```

2. Masuk ke directory proyek:
   ```bash
   cd Inventaris-Barang-Toko-Grosir
   ```

3. Import database:
   - Buka aplikasi database seperti phpMyAdmin.
   - Buat database baru dengan nama `inventaris`.
   - Import file `inventaris.sql` yang ada di folder `database`.

4. Konfigurasi aplikasi:
   - Buka file `application/config/config.php` dan sesuaikan `base_url` dengan URL lokal proyek Anda.
   - Buka file `application/config/database.php` dan atur konfigurasi koneksi database sesuai dengan server Anda (hostname, username, password, database name).

5. Jalankan aplikasi:
   - Akses aplikasi melalui browser dengan URL yang sudah diatur di `base_url` (contoh: `http://localhost/Inventaris-Barang-Toko-Grosir`).

## Struktur Proyek
- **application/**: Berisi file utama dari framework CodeIgniter, termasuk konfigurasi, controller, model, dan views.
- **assets/**: Berisi file statis seperti CSS, JavaScript, dan gambar.
- **database/**: Berisi file SQL untuk struktur dan data awal database.

## Akun Demo
Gunakan akun berikut untuk mengakses sistem:
- **Username**: admin
- **Password**: admin

## Pengembang
- **Nama**: I Kadek Agus Dwiyana


## Lisensi

---
Jika Anda memiliki pertanyaan atau membutuhkan bantuan, silakan hubungi pengembang melalui email: dwiyana@example.com.


