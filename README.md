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

2. Buka folder proyek dan jalankan berkas HTML utama:
* Cukup klik dua kali (double click) pada file moto-track.html di dalam file manager Anda untuk membukanya langsung di Google Chrome, Microsoft Edge, Mozilla Firefox, Brave, atau Safari.
* Opsional: Gunakan ekstensi seperti Live Server di VS Code jika Anda ingin melakukan kustomisasi kode dengan fitur auto-reload.

# MotoTrack — Motorcycle Component Lifetime Tracker & Maintenance Log

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-f06a00?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Architecture-Pure%20SPA%20%2F%20Client--Side-blue?style=for-the-badge" alt="Architecture">
  <img src="https://img.shields.io/badge/Privacy-100%25%20Offline%20%2F%20Local-success?style=for-the-badge" alt="Privacy">
</p>

---

### 📌 About MotoTrack
**MotoTrack** is a sleek, cyber-industrial web application (Single Page Application) meticulously engineered to track your motorcycle's spare part lifespans, component wear, and service intervals in real-time.

Unlike standard vehicle management tools that require cloud accounts, active internet connections, or personal data tracking, MotoTrack is built with a strict **100% Privacy-Focused & Offline-First** philosophy. Your mileage dashboard, component parameters, custom maintenance costs, and bookmarked reference QR codes are processed and stored entirely within your browser's local sandbox storage (`localStorage`). **Your data never leaves your device.**

---

### 🚀 Key Features
* **Central Odometer Synchronization:** Simply update your motorcycle's current global mileage (KM) on the main dashboard, and the application instantly re-evaluates the exact remaining safe operation lifespan for all configured spare parts.
* **Dynamic Early Warning System (EWS):** Visualizes individual component wear status using intuitive, highly responsive color-coded alert badges:
  * 🔴 **Critical:** The component's lifetime has fully expired or crossed safe operational thresholds.
  * 🟡 **Warning:** The part is approaching its replacement limit based on your customizable global or individual alert thresholds.
  * 🟢 **Good:** The component is well within its optimal operating condition.
* **Adaptive Tracking Metrics (*Fast & Slow Moving*):**
  * *Fast Moving:* Dual-tracking metric combo based on both accumulated mileage (KM) and elapsed duration (Months)—perfect for Engine Oil, Gear Oil, or Brake Fluid.
  * *Slow Moving:* Single-metric focus based strictly on custom mileage limits—ideal for V-Belts, Spark Plugs, Rollers, or Clutch Plates.
* **Detailed Maintenance Ledger:** Keep a granular, permanent logbook of all historical part replacements featuring exact calendar dates, odometer records during service, workshop locations, itemized pricing, and notes to easily evaluate total ownership costs.
* **Embedded QR Code Storage:** Store reference images (such as digital factory service manuals, online spare part catalog links, or mechanic contact information) directly inside your offline storage using local *Base64* encoding.
* **Data Sovereignty (JSON Export/Import):** Because there is no external database, you own your data completely. Backup or seamlessly migrate your database across multiple devices (e.g., phone to desktop laptop) via a single, lightweight `.json` file backup.
* **Cyber-Industrial UI Design:** Powered by a customized blend of *Barlow Condensed*, *Barlow*, and *Share Tech Mono* typography wrapped around Tailwind CSS utilities. Built with an ultra-deep industrial Dark Mode, a clean alternative Light Mode, and an ergonomic mobile-first responsive layout.
* **Native Multi-Language Support:** Instant runtime translation toggles (English & Indonesian) built right into the app without demanding page reloads.

---

### 💻 Tech Stack
* **HTML5 & CSS3** (Utilizing custom property CSS variables for responsive UI color schemes)
* **Tailwind CSS v3** (Rapid interface layout utility framework delivered via CDN)
* **Google Fonts API** (Barlow Condensed, Barlow, & Share Tech Mono)
* **Vanilla JavaScript (ES6+)** (Zero-dependency, clean reactive modern state architecture)
* **LocalStorage API** (Persistent browser storage sandbox)

---

### ⚙️ How to Run Locally
Since MotoTrack runs completely client-side in the browser, there is no need to configure complex development runtimes like Node.js, spinning up Docker containers, or managing database systems.

1. Clone or download this repository to your local computer:
   ```bash
   git clone [https://github.com/username/mototrack.git](https://github.com/username/mototrack.git)

2. Navigate into the project folder and launch the web interface:
* Simply double-click the moto-track.html file to open it instantly inside any modern web browser (Chrome, Edge, Firefox, Brave, or Safari).
* Optional: Use the Live Server extension in VS Code for an optimized local development experience.

### 📄 License / Lisensi
Distributed under the MIT License. See LICENSE for more information.
Hak Cipta dilindungi di bawah Lisensi MIT.
