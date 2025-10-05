# 🔑 Manajemen API

Layar **Manajemen API** memungkinkan Anda mengelola kunci API TradeGrub Anda — yang digunakan untuk integrasi aman dengan layanan eksternal seperti **TradingView** atau **API REST kustom**.

---

## 📋 Tabel Kunci API

Semua kunci API yang ada ditampilkan dalam tabel yang sederhana dan mudah dibaca.

### Kolom Tabel
- **Nama** → Label yang Anda tetapkan saat membuat kunci.
- **Kunci** → Pengidentifikasi unik yang digunakan untuk autentikasi.
- **Izin** → Menentukan apa yang dapat diakses oleh kunci (misalnya, `TradingView`, `REST`).
- **Tanggal Dibuat** → Tanggal pembuatan kunci.
- **Tindakan** → Gunakan ikon 🗑️ **Hapus** untuk menghapus kunci API secara permanen.

> ⚠️ **Penting:** Menghapus kunci API akan segera mencabut aksesnya.
> Layanan apa pun yang terhubung (seperti webhook TradingView) yang menggunakan kunci tersebut akan berhenti berfungsi.

---

## ➕ Membuat Kunci API Baru

Ketuk tombol **“+” (Tambah)** di pojok kanan atas untuk membuat kunci baru.
Anda akan diminta untuk menentukan:

| Kolom | Deskripsi |
|--------|--------------|
| **Nama** | Nama yang mudah diingat untuk mengidentifikasi kunci ini (misalnya, *Sinyal TradingView*). |
| **Izin** | Pilih salah satu atau keduanya: - **TradingView** → Diperlukan untuk menerima dan memproses sinyal webhook TradingView. - **REST** → Diperlukan untuk mengakses API REST TradeGrub. |

Setelah dibuat, kunci API baru akan langsung muncul di tampilan tabel Anda.

> 💡 Anda dapat membuat beberapa kunci — misalnya, satu untuk akun TradingView pribadi Anda dan satu lagi untuk integrasi REST otomatis Anda.

---

## 🔐 Visibilitas Rahasia API

Saat kunci API baru dibuat, **rahasia** dibuat dan ditampilkan **hanya sekali** demi alasan keamanan.
Anda akan memiliki opsi untuk **menyalin** kunci tersebut selama pembuatan — pastikan untuk menyimpannya dengan aman.

> ⚠️ **Catatan:** 
> Rahasia **tidak dapat dilihat lagi nanti**.
> Anda harus menyimpannya dengan aman, karena akan diperlukan saat menggunakan kunci API dalam integrasi **TradingView** atau **REST API**.

---

## ⚙️ Praktik Terbaik

- Jaga kerahasiaan dan keamanan kunci API Anda**.
- Gunakan **kunci terpisah** untuk integrasi yang berbeda.
- Segera cabut (hapus) kunci yang tidak digunakan atau yang telah disusupi.
- Jangan pernah membagikan kunci API Anda secara publik atau dalam bentuk tangkapan layar.

---

## 🧩 Contoh Kasus Penggunaan

| Skenario | Izin yang Diperlukan |
|-----------|---------------------|
| Mengirim sinyal beli/jual TradingView | TradingView |
| Melakukan panggilan REST API ke TradeGrub | REST |
| Pengaturan otomatisasi perdagangan gabungan | TradingView + REST |

---

## 🆘 Tips
- Ketuk ikon **info (ℹ️)** di pojok kanan atas untuk bantuan cepat.
- Anda selalu dapat membuat ulang kunci jika terhapus secara tidak sengaja.
- Tindakan kunci API disinkronkan secara instan dengan akun Anda — tidak perlu memulai ulang aplikasi.
