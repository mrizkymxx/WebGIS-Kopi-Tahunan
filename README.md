# WebGIS Kopi Tahunan

Selamat datang di aplikasi WebGIS Kopi Tahunan! Aplikasi ini adalah Sistem Informasi Geografis (SIG) berbasis web yang menampilkan lokasi-lokasi kedai kopi di Kecamatan Tahunan, Jepara, lengkap dengan fitur interaktif dan analisis sederhana.

---

## Panduan Penggunaan Rinci

### 1. Membuka Aplikasi
- Buka aplikasi melalui browser (misal: link Vercel atau buka file `index.html`).

### 2. Navigasi Peta
- Peta utama dapat digeser (drag) dan di-zoom menggunakan mouse atau tombol (+) dan (–) di pojok kiri bawah.
- Terdapat beberapa pilihan tampilan peta (Peta Jalan, Satelit, Mode Gelap) yang bisa dipilih di pojok kanan bawah.
- MiniMap (peta kecil di pojok kanan bawah) membantu melihat posisi global.

### 3. Sidebar Kiri (Informasi & Filter)
- Berisi informasi aplikasi, statistik mini (total lokasi, rata-rata rating, dominasi jenis kedai), filter jenis booth (Menetap/Mobile), legenda peta, tombol unduh data GeoJSON, dan tombol reset tampilan peta.
- Statistik akan otomatis berubah sesuai filter dan pencarian.
- Filter jenis booth untuk menampilkan hanya "Kedai Menetap", "Kopi Keliling", atau semua.
- Tombol "Unduh Data GeoJSON" untuk mengunduh data lokasi dalam format GIS.
- Tombol "Kembali ke Tengah" untuk mengembalikan tampilan peta ke posisi awal.

### 4. Sidebar Kanan (Daftar Lokasi & Pencarian)
- Terdapat kolom pencarian nama kedai kopi.
- Daftar lokasi akan otomatis terfilter sesuai pencarian dan filter jenis booth.
- Klik nama lokasi di daftar untuk langsung menuju dan membuka popup detail di peta.

### 5. Marker & Popup Lokasi
- Setiap lokasi kopi ditandai marker dengan ikon berbeda:
  - Ikon toko (coklat): Kedai Menetap
  - Ikon sepeda (oranye): Kopi Keliling
- Klik marker untuk melihat popup detail: nama, foto, rating, tipe, jam buka, menu best seller, dan tombol rute ke Google Maps.

### 6. Analisis Heatmap
- Aktifkan layer "Analisis Kepadatan (Heatmap)" di kontrol layer (pojok kanan bawah) untuk melihat sebaran kepadatan lokasi kopi.

### 7. Wilayah Administratif
- Area Kecamatan Tahunan digambarkan dengan poligon biru transparan di peta.

### 8. Fitur Akademis
- Skala peta (pojok kanan bawah) untuk melihat jarak.
- Koordinat kursor (pojok kanan bawah) menampilkan posisi mouse secara real-time.
- MiniMap (peta kecil) untuk orientasi global.

### 9. Fitur Lain
- Geocoder (pojok kiri bawah): Cari lokasi secara global.
- Tombol "Lokasi Saya" (ikon crosshair, kiri bawah): Zoom ke lokasi pengguna (memerlukan izin lokasi browser).
- Tombol "Mode Gelap/Terang" (ikon bulan/matahari, kiri bawah): Mengubah tampilan aplikasi ke dark mode atau light mode.

### 10. Responsif
- Tampilan otomatis menyesuaikan untuk perangkat mobile, sidebar menjadi lebih kecil dan MiniMap disembunyikan.

---

## Daftar Fitur Lengkap

- Peta interaktif dengan beberapa pilihan basemap
- Marker lokasi kedai kopi dengan ikon berbeda sesuai tipe
- Popup detail lokasi (nama, foto, rating, jam, menu, rute Google Maps)
- Statistik mini dashboard (total lokasi, rata-rata rating, dominasi jenis)
- Filter jenis booth (Menetap/Mobile)
- Pencarian nama lokasi
- Daftar lokasi interaktif (klik untuk zoom dan buka popup)
- Analisis heatmap sebaran lokasi
- Poligon wilayah administratif Kecamatan Tahunan
- Download data lokasi dalam format GeoJSON
- Skala peta
- Koordinat kursor real-time
- MiniMap (peta kecil)
- Geocoder (pencarian lokasi global)
- Lokasi pengguna (zoom ke posisi user)
- Mode gelap/terang (dark mode)
- Tampilan responsif untuk mobile

---

## Tips Penggunaan
- Pastikan koneksi internet stabil untuk memuat peta dan gambar.
- Jika peta tidak muncul, refresh halaman atau pastikan browser mendukung JavaScript.
- Untuk fitur lokasi pengguna, izinkan akses lokasi pada browser.

---

## Kontak & Bantuan
Jika mengalami kendala atau ingin memberikan masukan, silakan hubungi pengembang melalui halaman GitHub project ini.

Selamat menjelajah informasi kopi di Tahunan!
