# MotoTrack — Motorcycle Component Lifetime Tracker & Maintenance Log

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-f06a00?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Architecture-Pure%20SPA%20%2F%20Client--Side-blue?style=for-the-badge" alt="Type">
  <img src="https://img.shields.io/badge/Privacy-100%25%20Offline%20%2F%20Local-success?style=for-the-badge" alt="Privacy">
</p>

---

## 🇮🇩 Bahasa Indonesia

### 📌 Tentang MotoTrack
**MotoTrack** adalah aplikasi berbasis web (*Single Page Application*) modern dengan estetika industri-cyberpunk yang dirancang khusus untuk memantau sisa masa pakai (umur) komponen serta jadwal perawatan sepeda motor secara *real-time*. 

Berbeda dengan aplikasi pelacak kendaraan lain yang mewajibkan pendaftaran akun atau koneksi internet, MotoTrack mengusung prinsip **100% Privacy-Focused & Offline-First**. Seluruh data motor, parameter komponen, QR Code eksternal, hingga catatan finansial servis Anda diproses dan disimpan sepenuhnya di dalam penyimpanan lokal (*localStorage*) browser Anda sendiri. **Tidak ada data yang dikirim ke server luar, bebas pelacakan, dan sepenuhnya aman.**

---

### 🚀 Fitur Utama
* **Odometer Sentral Terintegrasi:** Cukup perbarui angka odometer utama (KM) motor Anda pada dashboard, dan sistem akan langsung mengalkulasi ulang sisa jarak tempuh aman untuk seluruh komponen secara instan.
* **Early Warning System (EWS):** Visualisasi status keausan komponen yang interaktif menggunakan indikator warna intuitif:
  * 🔴 **Kritis:** Masa pakai komponen telah habis atau melewati batas toleransi aman.
  * 🟡 **Peringatan:** Komponen mendekati batas penggantian berdasarkan persentase ambang batas (*alert threshold*) yang dapat dikonfigurasi.
  * 🟢 **Bagus:** Komponen masih dalam kondisi optimal.
* **Kategori Fleksibel (*Fast & Slow Moving*):**
  * *Fast Moving:* Pelacakan ganda berdasarkan kombinasi jarak tempuh (KM) dan batas waktu (Bulan), seperti Oli Mesin, Oli Gardan, atau Minyak Rem.
  * *Slow Moving:* Pelacakan fokus berdasarkan interval jarak tempuh saja, seperti Vanbelt (V-Belt), Kampas Kopling, Roler, atau Busi.
* **Log Perawatan Komprehensif (Finansial & Mekanik):** Catat riwayat penggantian komponen lengkap dengan tanggal, posisi odometer saat servis, nama bengkel, rincian biaya itemized, serta catatan khusus dari mekanik untuk memantau total pengeluaran servis berkala.
* **Penyimpanan Gambar QR Code:** Menyimpan gambar QR Code referensi (seperti link manual servis digital, tautan toko sparepart langganan, atau nomor kontak mekanik) langsung di dalam aplikasi menggunakan konversi *Base64*.
* **Portabilitas Data (Ekspor/Impor JSON):** Anda memiliki kendali penuh atas data Anda. Ekspor seluruh basis data ke dalam satu berkas `.json` ringkas kapan saja sebagai cadangan (*backup*) atau untuk migrasi data antar-perangkat (misal dari HP ke Laptop) secara instan.
* **Antarmuka Modern & Responsif:** Menggunakan font *Barlow Condensed*, *Barlow*, dan *Share Tech Mono* dipadukan dengan utility-first styling dari Tailwind CSS. Dilengkapi mode gelap (*Dark Mode*) industrial yang pekat dan mode terang (*Light Mode*) yang bersih, serta sepenuhnya responsif untuk perangkat seluler maupun desktop.
* **Dukungan Dua Bahasa Native:** Pengalihan bahasa dinamis antara Bahasa Indonesia dan Bahasa Inggris secara langsung tanpa memuat ulang halaman.

---

### 💻 Teknologi yang Digunakan
* **HTML5 & CSS3** (Custom Properties / Variabel warna CSS lokal)
* **Tailwind CSS v3** (Utility-first styling framework via CDN)
* **Google Fonts** (Barlow Condensed, Barlow, & Share Tech Mono)
* **Vanilla JavaScript (ES6+)** (Arsitektur SPA murni berbasis *state* tanpa dependensi framework berat)
* **LocalStorage API** (Penyimpanan data lokal yang persisten di sandbox browser)

---

### ⚙️ Cara Penggunaan Lokal
Karena aplikasi ini murni berjalan di sisi klien (*client-side*), Anda tidak memerlukan instalasi *runtime* Node.js, Web Server, Docker, atau konfigurasi database yang rumit.

1. Unduh atau klon repositori ini ke komputer Anda:
   ```bash
   git clone [https://github.com/username/mototrack.git](https://github.com/username/mototrack.git)
