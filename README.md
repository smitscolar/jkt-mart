# 🛒 JKT MART — Sistem Kasir & Manajemen Toko

Aplikasi Point of Sale (POS) lengkap untuk Toko Sembako **JKT MART**.

## ✅ Fitur Utama

### 📦 9 Modul Aktif:
| Modul | Fitur |
|-------|-------|
| **Dashboard** | Omset harian, stok kritis, produk terlaris, transaksi terakhir |
| **Kasir / POS** | Barcode scanner, keranjang, hitung kembalian, cetak struk |
| **Produk** | Tambah/edit produk, barcode EAN-13 auto-generate, stok minimum |
| **Manajemen Stok** | Stok masuk via scan barcode, riwayat pergerakan, nilai inventori |
| **Purchase Order** | Buat PO, riwayat PO per supplier |
| **Supplier** | Daftar supplier, kontak, riwayat pembelian |
| **Pelanggan** | Daftar pelanggan, manajemen hutang/piutang |
| **Laporan** | Omset bulanan, grafik 7 hari, per kategori, export PDF/Excel |
| **Pengaturan** | Profil toko, scanner, metode bayar, pajak & struk |

### 🔴 Fitur Barcode Scanner:
- **Kasir**: Scan barcode → produk otomatis masuk keranjang
- **Stok Masuk**: Scan barcode produk → nama & harga beli otomatis terisi
- **Manajemen Produk**: Scan untuk cari/edit produk
- **Auto Generate**: Barcode EAN-13 di-generate otomatis untuk produk baru
- **Simulasi Kamera**: Mode simulasi scanner kamera tersedia

## 🚀 Cara Deploy ke GitHub Pages

### 1. Upload ke GitHub
```bash
git init
git add index.html
git commit -m "Initial: JKT Mart POS System v1.0"
git remote add origin https://github.com/USERNAME/jktmart-pos.git
git push -u origin main
```

### 2. Aktifkan GitHub Pages
- Buka repository di GitHub
- Klik **Settings** → **Pages**
- Source: **Deploy from branch** → branch: `main` → folder: `/ (root)`
- Klik **Save**
- Tunggu 2-3 menit → akses di: `https://USERNAME.github.io/jktmart-pos`

## 📱 Cara Pakai

1. **Buka `index.html`** di browser (atau akses via GitHub Pages)
2. **Tab Kasir** → Klik tombol "Kamera" → Pilih produk untuk scan
3. Atau ketik barcode di kotak scan → tekan Enter
4. Isi jumlah bayar → klik **Bayar & Cetak Struk**
5. Struk muncul otomatis dengan nama **JKT MART**

## 🛍️ Data Produk Contoh
- Beras Ramos 5kg — `8992388005102`
- Minyak Goreng Bimoli 2L — `8993014042036`
- Gula Pasir 1kg — `8993014010011`
- Indomie Goreng — `8996001411173`
- Aqua 600ml — `8993001120021`
- ...dan 7 produk lainnya

## 🛠️ Tech Stack
- **Frontend**: HTML5, CSS3, Vanilla JavaScript (Pure, tanpa framework)
- **Storage**: In-Memory (session) — siap diintegrasikan Supabase/Firebase
- **Deployment**: GitHub Pages (gratis)

---
**JKT MART v1.0** | Build: June 2025 | Made with ❤️ for Toko Sembako Indonesia
