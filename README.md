# GajiPro - Kalkulator Gaji Karyawan & Lembur 💼📱

Aplikasi mobile modern untuk menghitung estimasi **Gaji Pokok** dan **Kompensasi Upah Lembur** karyawan berdasarkan standar grade/golongan secara cepat, transparan, dan akurat.

---

## ✨ Fitur Utama
1. **Pemilihan Golongan Karyawan:**
   - **Golongan A (Staff Junior):** Gaji Pokok Rp 5.000.000
   - **Golongan B (Staff Senior):** Gaji Pokok Rp 6.500.000
   - **Golongan C (Supervisor):** Gaji Pokok Rp 9.500.000
2. **Kalkulasi Upah Lembur Akurat:**
   - Stepper interaktif (+ / - jam lembur)
   - Pintas cepat (0 Jam, 1 Jam, 2 Jam, 3 Jam, 4 Jam, 5+ Jam)
   - Persentase kompensasi otomatis:
     - 0 Jam: 0%
     - 1 Jam: 30% dari Pokok
     - 2 Jam: 32% dari Pokok
     - 3 Jam: 34% dari Pokok
     - 4 Jam: 36% dari Pokok
     - ≥ 5 Jam: 38% dari Pokok
3. **Rincian Slip Gaji & Salin Instan:**
   - Rincian transparan gaji pokok, durasi lembur, persentase pengali, dan nominal kompensasi.
   - Tombol satu klik **"Salin Rincian Slip"** untuk dikirim via WhatsApp / Email / Catatan.
4. **Tabel Ketentuan & Tarif Lembur:**
   - Tabel acuan perhitungan yang dapat dibuka-tutup.
5. **Siap Pakai di HP (Mobile Ready):**
   - **Download File APK Android (.apk)** langsung dari GitHub Releases.
   - **Progressive Web App (PWA):** Bisa langsung dipasang ke Layar Utama (Add to Home Screen) di Android & iOS tanpa perlu instalasi rumit.

---

## 📲 Cara Download & Pasang Jadi Aplikasi HP

### Pilihan 1: Download File APK Android Langsung (.apk)
1. Buka menu **[Releases](https://github.com/fajarcreative/kalkulator-gaji-karyawan/releases)** di repositori GitHub ini.
2. Unduh file **`KalkulatorGaji-v1.0.apk`**.
3. Buka file di HP Android Anda dan pasang aplikasi.

### Pilihan 2: Pasang Langsung dari Browser HP (PWA)
1. Buka link web di HP: **[https://fajarcreative.github.io/kalkulator-gaji-karyawan/](https://fajarcreative.github.io/kalkulator-gaji-karyawan/)**
2. **Di Android (Google Chrome):**
   - Tekan tombol **"Pasang di HP"** di header aplikasi atau tekan menu titik tiga (⋮) lalu pilih **"Install Aplikasi"** / **"Tambahkan ke Layar Utama"**.
3. **Di iPhone (Safari):**
   - Tekan tombol **Bagikan (Share)** di bagian bawah Safari, lalu pilih **"Tambah ke Layar Utama (Add to Home Screen)"**.

---

## 💻 Cara Menjalankan di Komputer / Laptop (Lokal)

1. Pastikan Node.js sudah terpasang.
2. Buka terminal di folder proyek:
   ```bash
   npm start
   ```
3. Buka browser di:
   ```
   http://localhost:3000
   ```

---

## 🛠️ Arsitektur Proyek
- `index.html` & `code.html`: Antarmuka mobile-first responsif berbasis Tailwind CSS.
- `manifest.json`: Web App Manifest untuk instalasi PWA di smartphone.
- `sw.js`: Service worker untuk caching dan dukungan offline.
- `capacitor.config.json` & `android/`: Proyek native Android berbasis Capacitor untuk kompilasi APK.
- `.github/workflows/build-apk.yml`: Otomasi GitHub Actions untuk meng-compile Android APK dan menerbitkan rilis otomatis.
- `.github/workflows/deploy-pages.yml`: Otomasi deployment ke GitHub Pages.

---

Dikembangkan oleh **[fajarcreative](https://github.com/fajarcreative)**.
