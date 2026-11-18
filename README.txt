LAPORAN HARIAN v3.0 - JURUKUR MAHABOB & CO SDN BHD
===================================================

Isi folder:
  index.html            App laporan harian
  manifest.webmanifest  Maklumat app (nama, ikon, warna)
  sw.js                 Service worker (app jalan tanpa internet)
  icons/                Ikon app dari logo company
  .htaccess             Tetapan untuk hosting cPanel (fail tersembunyi)

PENTING: Semua fail mesti di-upload bersama ke laman HTTPS.
Buka index.html terus dari folder (double-click) TAK boleh dipasang.

CARA PUBLISH (GitHub Pages, percuma)
1. Daftar / login github.com
2. Klik "+" > New repository. Nama: laporan-harian. Pilih Public. Create.
3. Klik "uploading an existing file". Seret SEMUA fail dan folder icons. Commit.
4. Settings > Pages > Source: Deploy from a branch > Branch: main, folder / (root) > Save.
5. Tunggu 1-2 minit. Link: https://NAMA-GITHUB.github.io/laporan-harian/

CARA PASANG DALAM PHONE
Android (Chrome): buka link > tekan "Pasang app" dalam page, atau menu (titik tiga) > Install app.
iPhone (Safari):  buka link > butang Share > Add to Home Screen.

KEMAS KINI APP
1. Ganti fail yang berubah dalam GitHub.
2. Dalam sw.js, tukar VERSION (contoh v3.0.0 -> v3.0.1).
3. Staff buka app sekali ketika ada internet. Versi baru masuk sendiri.

DATA
- Data disimpan dalam phone setiap staff. Tiada server, tiada data dikongsi.
- Buang app / clear data browser = data hilang. Tekan "Backup data" seminggu sekali.
