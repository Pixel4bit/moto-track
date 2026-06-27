# MotoTrack — Motorcycle Health, Maintenance & Fuel Management System

<p align="center">
  <img src="https://img.shields.io/badge/Version-v3u-f06a00?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Architecture-Pure%20SPA%20%2F%20Client--Side-blue?style=for-the-badge" alt="Architecture">
  <img src="https://img.shields.io/badge/Privacy-100%25%20Offline-success?style=for-the-badge" alt="Privacy">
  <img src="https://img.shields.io/badge/Storage-LocalStorage-orange?style=for-the-badge" alt="Storage">
</p>

---

# 🇮🇩 Bahasa Indonesia

## 📌 Tentang MotoTrack

**MotoTrack** adalah aplikasi web modern berbasis **Single Page Application (SPA)** yang dirancang untuk membantu pemilik sepeda motor memantau kondisi komponen, jadwal perawatan, riwayat servis, dan konsumsi bahan bakar dalam satu dashboard terintegrasi.

MotoTrack mengusung filosofi **Offline-First** dan **Privacy-Focused**. Semua data disimpan langsung di browser pengguna menggunakan LocalStorage tanpa server, tanpa akun, dan tanpa pelacakan pihak ketiga.

> Pantau kesehatan motor, prediksi kebutuhan servis, dan analisis konsumsi BBM dari satu aplikasi ringan yang dapat berjalan sepenuhnya secara offline.

---

## 🚀 Fitur Utama

### 🔧 Component Health Tracking

Pantau umur pakai komponen berdasarkan odometer kendaraan.

* Tracking umur komponen berbasis kilometer
* Progress bar kesehatan komponen
* Status kondisi:

  * 🟢 Good
  * 🟡 Warning
  * 🔴 Critical
* Kalkulasi otomatis sisa umur pakai
* Threshold peringatan yang dapat disesuaikan

---

### ⚡ Fast Moving & Slow Moving Components

Pisahkan komponen berdasarkan karakteristik perawatan.

**Fast Moving Components**

Contoh:

* Oli Mesin
* Oli Gardan
* Minyak Rem
* Coolant

**Slow Moving Components**

Contoh:

* V-Belt
* Roller
* Kampas Kopling
* Busi
* Kampas Rem

---

### ⛽ Fuel Consumption Tracking

Pantau efisiensi bahan bakar kendaraan.

Fitur:

* Log pengisian BBM
* Riwayat konsumsi bahan bakar
* Analisis efisiensi kendaraan
* Perhitungan KM/L
* Monitoring perubahan konsumsi dari waktu ke waktu

---

### 📜 Maintenance History

Simpan seluruh riwayat perawatan motor.

* Riwayat servis
* Riwayat penggantian komponen
* Riwayat pengisian BBM
* Pencarian data historis
* Filter berdasarkan kategori

---

### 📊 Smart Dashboard

Dashboard terpusat yang menampilkan:

* Status kesehatan komponen
* Komponen yang mendekati masa servis
* Statistik kendaraan
* Ringkasan konsumsi BBM
* Prioritas perawatan

---

### 🔍 Sorting & Filtering System

Kelola komponen dengan lebih mudah.

Filter:

* All
* Critical
* Warning
* Good

Sorting:

* Urgency
* Alphabetical (A–Z)
* Default

---

### 🌐 Multi Language

Dukungan bahasa bawaan:

* Bahasa Indonesia
* English

Pergantian bahasa dilakukan secara real-time tanpa reload halaman.

---

### 🎨 Advanced UI Customization

MotoTrack v3s menghadirkan sistem personalisasi tampilan yang fleksibel.

#### Theme Customization

* Dark Theme
* Light Theme
* Custom Accent Colors

#### Layout System

* Default Dashboard
* Sidebar Layout
* Centered Layout

#### Design System

* Minimalist
* Premium Automotive
* Material Design

#### UI Density

* Compact
* Default
* Spacious

---

### 💾 Import & Export Data

Seluruh data dapat dicadangkan dan dipindahkan antar perangkat.

* Export JSON
* Import JSON
* Backup lokal
* Migrasi data antar browser/perangkat

---

### 🔒 Privacy First

MotoTrack tidak menggunakan:

* Login
* Account
* Cloud Database
* Analytics
* Tracking Scripts

Semua data tetap berada di perangkat pengguna.

---

## 💻 Technology Stack

* HTML5
* CSS3
* Tailwind CSS
* Vanilla JavaScript (ES6+)
* LocalStorage API
* Google Fonts

---

## ⚙️ Run Locally

Clone repository:

```bash
git clone https://github.com/yourusername/mototrack.git
```

Masuk ke folder project:

```bash
cd mototrack
```

Buka file HTML utama:

```text
moto-track-v3s.html
```

Atau gunakan:

* Live Server (VS Code)
* Chrome
* Edge
* Firefox
* Brave

Tidak memerlukan:

* Node.js
* Database
* Backend Server
* Docker

---

## 🎯 Why MotoTrack?

Sebagian besar aplikasi motor hanya fokus pada:

* Navigasi
* Ride Tracking
* Komunitas

MotoTrack fokus pada hal yang paling sering dilupakan pemilik motor:

✅ Kapan harus servis

✅ Komponen apa yang harus diganti

✅ Seberapa sehat kondisi motor

✅ Berapa konsumsi BBM sebenarnya

MotoTrack menggabungkan **Maintenance Management** dan **Fuel Analytics** dalam satu aplikasi offline yang ringan dan mudah digunakan.

---

# 🇺🇸 English

## 📌 About MotoTrack

**MotoTrack** is a modern motorcycle maintenance and fuel management web application designed to help riders monitor component health, maintenance schedules, service history, and fuel consumption in a single integrated dashboard.

Built as a **Pure Client-Side SPA**, MotoTrack follows an **Offline-First** and **Privacy-Focused** philosophy. All data is stored locally in your browser using LocalStorage.

No accounts.

No servers.

No tracking.

No subscriptions.

---

## 🚀 Key Features

### 🔧 Component Health Monitoring

* Mileage-based component lifespan tracking
* Health percentage visualization
* Automatic wear calculations
* Good / Warning / Critical status indicators
* Custom alert thresholds

### ⚡ Fast & Slow Moving Components

Organize maintenance items by service characteristics.

Examples:

**Fast Moving**

* Engine Oil
* Gear Oil
* Brake Fluid
* Coolant

**Slow Moving**

* V-Belt
* Rollers
* Spark Plugs
* Brake Pads
* Clutch Components

### ⛽ Fuel Consumption Analytics

* Fuel refill logging
* Fuel history
* KM/L calculations
* Efficiency monitoring
* Long-term fuel trend analysis

### 📜 Maintenance History

* Service records
* Component replacement logs
* Fuel records
* Search and filtering system

### 📊 Smart Dashboard

Monitor:

* Component health
* Service priorities
* Fuel performance
* Motorcycle status overview

### 🎨 Extensive UI Customization

* Multiple themes
* Accent color customization
* Layout switching
* Design systems
* Density controls

### 💾 Data Portability

* JSON Export
* JSON Import
* Local Backup
* Device Migration

### 🔒 Privacy Focused

MotoTrack never sends your data to external servers.

Everything stays on your device.

---

## 💻 Tech Stack

* HTML5
* CSS3
* Tailwind CSS
* Vanilla JavaScript (ES6+)
* LocalStorage API
* Google Fonts

---

## 📄 License

Released under the MIT License.

Feel free to use, modify, and distribute.
