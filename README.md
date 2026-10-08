# Sistem Informasi Pengelolaan dan Audit Stok Barang

**Perpetual Inventory System | Studi Kasus: Toko Andre Jaya Ban**

Proyek skripsi S1 Sistem Informasi, Universitas Bandar Lampung, 2026.

> Kode sumber disimpan di repositori privat. Repositori ini berisi penjelasan dan tampilan sistem.
> Untuk keperluan akademik atau rekrutmen, silakan hubungi penulis.

## Tampilan Sistem

**Monitoring**
[![Demo Dashboard](images/thumbnail.png)](youtu.be/vz8k2z3LEow)
| Dashboard Pemilik | Dashboard Admin Cabang |
|---|---|
| ![Dashboard Pemilik](docs/dashboardpemilik.png) | ![Dashboard Admin](docs/dashboardadmin.png) |

**Transaksi dan laporan**

| Transaksi Barang Keluar | Laporan Stok |
|---|---|
| ![Transaksi Keluar](docs/transaksikeluar.png) | ![Laporan Stok](docs/laporanstok.png) |

**Audit stok**

| Input Opname (Admin Cabang) | Verifikasi Audit (Pemilik) |
|---|---|
| ![Input Opname](docs/inputopname.png) | ![Verifikasi Audit](docs/verifikasipemilik.png) |

## Latar Belakang

Pencatatan stok di toko dengan tiga cabang sebelumnya semi-manual di Microsoft Excel, sehingga rawan *human error* dan sering terjadi selisih antara catatan dan stok fisik. Sistem ini memperbarui stok otomatis pada setiap transaksi dan menyediakan alur audit stok yang terdokumentasi.

## Fitur

- Login berbasis peran: **Pemilik** (memantau semua cabang) dan **Admin Cabang** (mengelola cabangnya sendiri)
- Dashboard monitoring dengan pembaruan stok real-time untuk Pemilik
- Kelola data cabang, barang, dan jasa
- Transaksi barang masuk (pembelian) dan barang keluar (penjualan)
- Stok bertambah dan berkurang otomatis di setiap transaksi; penjualan ditolak jika stok tidak cukup
- Riwayat transaksi dan cetak nota
- Laporan stok, barang masuk, dan barang keluar
- Audit stok: Admin Cabang mengisi stok fisik, barang dikunci dari penjualan, lalu Pemilik memverifikasi dan stok disesuaikan

## Teknologi

Laravel 12, PHP, MySQL, Tailwind CSS, Laravel Reverb, Vite. Metode pengembangan: Waterfall.

## Hasil Pengujian

- White Box dan Black Box Testing: seluruh fungsi modul berjalan sesuai rancangan.
- Pre-test dan post-test kepuasan operasional: naik 42% (Pemilik) dan 40,67% (Admin Cabang).

## Catatan

Repositori ini hanya berisi data contoh, bukan data asli Toko Andre Jaya Ban.

## Penulis

**Ester Belen Wijaya** | Program Studi Sistem Informasi, Universitas Bandar Lampung
LinkedIn: (https://www.linkedin.com/in/ester-belen-wijaya-857951233/?isSelfProfile=true)

## Hak Cipta

Hak cipta © 2026 Ester Belen Wijaya. Seluruh hak dilindungi. Konten dalam repositori ini tidak boleh disalin atau didistribusikan tanpa izin tertulis dari penulis.
