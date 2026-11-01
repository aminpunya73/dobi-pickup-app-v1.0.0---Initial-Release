# Dobi Alor Gajah - Release & Auto-Update Hub 🧺🚀

Repositori rasmi bagi penerbitan installer (*Release Binaries*) dan kemas kini automatik (*Auto-Update*) untuk **Aplikasi Desktop Pengurusan Dobi Pickup & Delivery Alor Gajah**.

---

## 📥 Muat Turun Versi Terkini (v1.0.1)

| Fail Pemasang (Installer) | Versi | Saiz | Keserasian |
| :--- | :--- | :--- | :--- |
| [**Dobi Alor Gajah Setup 1.0.1.exe**](./Dobi%20Alor%20Gajah%20Setup%201.0.1.exe) | `v1.0.1` | ~81.7 MB | Windows 10 / 11 (64-bit) |

### Pautan Penting:
- **Repositori Source Code**: [github.com/aminpunya73/dobi-pickup-app](https://github.com/aminpunya73/dobi-pickup-app)
- **Metadata Auto-Update**: [`latest.yml`](./latest.yml)

---

## ✨ Ciri-Ciri Utama Aplikasi (v1.0.1)
- 🧺 **Pengurusan Pickup & Delivery**: Pantau cucian mengikut zon Alor Gajah (Bandar Alor Gajah, Masjid Tanah, Simpang Empat, Rembia/Pegoh, Durian Tunggal).
- 🔄 **Penyegerakan Google Sheets**: Data tempahan bersambung secara langsung dengan Google Sheets.
- 🔐 **Sistem Pelesenan Peranti (Machine ID)**: Perlindungan lesen terikat pada perkakasan komputer.
- ⚡ **Auto-Update Automatik**: Aplikasi menyemak versi baharu dari repositori ini secara automatik semasa dibuka atau melalui butang "Semak Kemas Kini".
- ℹ️ **Popup Tentang Aplikasi (About)**: Paparan maklumat developer, logo rasmi, dan status perisian.

---

## 🛠️ Cara Pemasangan di Komputer Windows
1. Muat turun fail **`Dobi Alor Gajah Setup 1.0.1.exe`**.
2. Dwi-klik fail tersebut untuk memulakan pemasangan (*Setup Wizard*).
3. Ikuti arahan pada skrin. Pintasan desktop (*Desktop Shortcut*) akan dicipta secara automatik.
4. Buka aplikasi dan masukkan kunci lesen anda untuk memulakan operasi.

---

## 🔄 Bagaimana Auto-Update Berfungsi?
Aplikasi desktop menggunakan modul `electron-updater` yang disambungkan ke repositori ini:
1. Semasa aplikasi dijalankan, ia membaca fail `latest.yml` di GitHub Releases repositori ini.
2. Jika versi pada `latest.yml` lebih tinggi daripada versi aplikasi yang sedang berjalan, muat turun kemas kini akan dimulakan secara automatik di latar belakang.
3. Notifikasi kemas kini akan muncul dan pengguna hanya perlu klik **"Pasang & Mulakan Semula"**.

---

© 2026 Dobi Alor Gajah. Pembangun: **aminpunya73**.
