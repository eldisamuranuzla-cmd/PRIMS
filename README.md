SENARA

Plantation Intelligence System

One Platform. All Field Operations.

SENARA adalah platform digital untuk monitoring, analisis, dan evaluasi aktivitas operasional perkebunan berbasis GPS, geospatial intelligence, dan data analytics.

SENARA mengintegrasikan aktivitas pekerjaan lapangan dalam satu dashboard untuk membantu pengawasan pekerjaan, evaluasi coverage, validasi jalur GPS, serta pengambilan keputusan operasional yang lebih akurat.

---

Main Modules

SENARA memiliki enam modul utama:

Module| Function
Manual Fertilizer Tracking| Monitoring aktivitas pemupukan manual
Mechanized Tracking| Monitoring pemupukan mekanis menggunakan Kubota dan Emdek
Rawat Pruning| Monitoring pekerjaan pruning
Manual Dongkel| Monitoring aktivitas dongkel manual
Circle Manual| Monitoring pekerjaan circle manual
Rawat Chemist| Monitoring pekerjaan rawat chemist

Core Features

1. GPS Tracking Intelligence

- Visualisasi jalur GPS pekerja dan unit mekanisasi.
- Identifikasi titik GPS di dalam dan di luar polygon.
- Pemeriksaan kualitas rekaman GPS.
- Analisis aktivitas berdasarkan lokasi dan waktu.

2. Geospatial Polygon Integration

- Menggunakan polygon blok GITA sebagai referensi spasial.
- Identifikasi aktivitas berdasarkan kode blok.
- Integrasi luas blok berdasarkan data HESTI.
- Validasi coverage berdasarkan batas polygon.

3. Coverage & Completion Analytics

- Perhitungan coverage dalam hektare.
- Perhitungan ketuntasan berdasarkan luas coverage dibandingkan luas HESTI.
- Spatial buffer dan polygon clipping.
- Penggabungan area (union) untuk mencegah penghitungan ganda.

Formula:

"Ketuntasan (%) = Coverage Unik (Ha) / Luas HESTI (Ha) × 100"

4. GPS Playback

- Simulasi perjalanan GPS berdasarkan rekaman waktu.
- Play, pause, restart, dan pengaturan kecepatan.
- Visualisasi jalur per pekerja atau unit.

5. SENARA AI Insight

- Analisis estimasi durasi kerja.
- Identifikasi jeda rekaman GPS.
- Pemeriksaan aktivitas di luar polygon.
- Indikasi pekerjaan yang memerlukan verifikasi mandor.
- Rekomendasi evaluasi operasional.

AI Insight merupakan analisis berbasis aturan dan data GPS untuk mendukung pemeriksaan lapangan, bukan pengganti verifikasi aktual.

6. Offline Map Manager

- Unduh paket peta.
- Simpan data polygon dan jalur GPS dalam paket offline.
- Buka kembali paket peta untuk kebutuhan monitoring tanpa koneksi internet.

---

Technology Stack

- HTML5
- CSS3
- JavaScript
- Leaflet.js — Interactive Mapping
- Turf.js — Geospatial Analysis
- PapaParse — CSV Processing
- GeoJSON — Spatial Data

Data Architecture

SENARA menggunakan referensi polygon GITA dan data luas HESTI sebagai dasar analisis spasial.

Alur analisis:

1. Upload data GPS.
2. Validasi kualitas rekaman GPS.
3. Identifikasi posisi GPS terhadap polygon.
4. Pengelompokan aktivitas berdasarkan blok.
5. Perhitungan coverage unik.
6. Perbandingan coverage dengan luas HESTI.
7. Penyajian hasil melalui dashboard dan AI Insight.

How to Use

1. Buka aplikasi SENARA.
2. Pilih modul aktivitas yang ingin dimonitor.
3. Upload file GPS sesuai format modul.
4. Jalankan proses analisis.
5. Periksa jalur GPS pada peta.
6. Evaluasi coverage dan ketuntasan blok.
7. Gunakan Playback dan AI Insight untuk pemeriksaan lanjutan.

Project Vision

SENARA dikembangkan sebagai integrated plantation operations intelligence platform yang menghubungkan data aktivitas lapangan, pemetaan spasial, monitoring tenaga kerja, dan analisis operasional dalam satu ekosistem digital.

From Field Tracking to Plantation Intelligence.

---

Project: SENARA
Platform: Plantation Intelligence System
Repository: PRIMS
Development: Continuous Improvement
