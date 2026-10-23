# MITRA SL & UntungKu

Situs katalog sparepart lampu MITRA SL dan aplikasi pembukuan penjualan UntungKu.

## Aplikasi pembukuan UntungKu

- Halaman aplikasi: [`untungku/`](./untungku/)
- Catat jumlah produk terjual per tanggal.
- Simpan data produk sekali: nama, varian, modal, harga jual, dan biaya tambahan.
- Laporan keuntungan harian, mingguan, dan bulanan.
- Pengaturan estimasi biaya marketplace.
- Ekspor CSV dan cadangan/pemulihan JSON.
- PWA: manifest, ikon, dan service worker untuk cache/offline.

### Menayangkan lewat GitHub Pages

1. Buka **Settings → Pages** pada repository.
2. Pada **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch **main** dan folder **/(root)**, lalu simpan.
4. Setelah deployment selesai, buka:
   `https://vesatukio.github.io/mitraSL/untungku/`
5. Di Android, buka tautan itu melalui Chrome lalu pilih **Install app** atau **Tambahkan ke layar utama**. Di iPhone, buka melalui Safari → **Bagikan** → **Tambahkan ke Layar Utama**.

## Catatan data

Data UntungKu disimpan di penyimpanan browser pada perangkat yang digunakan, tidak otomatis tersinkron ke perangkat lain. Gunakan fitur cadangan JSON secara berkala. Perhitungan potongan marketplace merupakan estimasi dan perlu disesuaikan dengan laporan aktual.
