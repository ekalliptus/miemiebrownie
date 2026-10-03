# Miemie Brownie

Aplikasi absensi pegawai berbasis web untuk PT. NIBRAS BERKAH MULIA. Dibuat sebagai tugas akhir semester 4 mata kuliah Web Programming III.

## Fitur

- Login untuk admin dan pegawai.
- Panel admin: data pegawai, rekap absensi, ekspor data, dan pengaturan aplikasi.
- Pegawai dapat melakukan absensi dan melihat profil.

## Tech stack

- PHP dengan framework CodeIgniter 3
- mpdf dan phpspreadsheet (dependensi ekspor dokumen)
- MySQL, struktur awal database ada di `miemiebrownie.sql`

## Menjalankan

1. Import `miemiebrownie.sql` ke MySQL.
2. Sesuaikan koneksi database di `application/config/database.php`.
3. Sajikan lewat server PHP (misal XAMPP/Laragon) dengan document root mengarah ke `public/`.
