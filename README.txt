HR FUEL-SMART — Prototipe Sistem Demo
======================================

Isi:
- index.html: prototipe web statis, responsif, dengan alur Petugas SPBU, Admin Pusat, Informasi Publik, dan Pengaduan.
- Data contoh/simulasi tersimpan di localStorage browser.

Cara mencoba:
1. Ekstrak ZIP.
2. Buka index.html di browser modern (Chrome/Edge/Firefox).
3. Pilih tab Petugas SPBU, kirim penerimaan dengan jumlah rencana berbeda dari aktual.
4. Buka Admin Pusat dan klik Verifikasi atau Tolak.
5. Buka Informasi Publik untuk melihat hanya data yang terverifikasi dan dipublikasikan.
6. Coba formulir pengaduan masyarakat.

PENTING — Batasan versi ini:
- Ini prototipe frontend, belum merupakan sistem produksi.
- Belum ada backend/server, database terpusat, autentikasi admin/petugas yang aman, kontrol akses nyata, audit log server, unggah bukti foto, sensor tangki, GPS, atau integrasi pemasok.
- Data disimpan hanya pada browser/perangkat yang sama; tidak otomatis tersinkron dengan pengguna lain.
- Tombol akses internal hanya simulasi navigasi, bukan login aman.
- Jangan memasukkan data rahasia atau menggunakan data ini untuk transaksi operasional sungguhan.
- Sebelum deployment publik/produksi, perlu backend dan database, autentikasi serta role-based access control, validasi server, penyimpanan bukti, backup, HTTPS, audit trail, dan pengujian keamanan.

Deployment statis:
- Bisa diuji lokal dengan membuka index.html.
- Untuk GitHub Pages/hosting statis, unggah index.html ke repository dan aktifkan Pages. Namun data tetap lokal di browser masing-masing sampai backend dibangun.
