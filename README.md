# Proyek Lab Pemrograman: Validasi Product-Market Fit (Uji 5 Produk)

Repositori ini memuat implementasi tahap awal proyek Lab Pemrograman: konfigurasi AI Harness lokal, katalog 5 kandidat produk digital kampus, serta instrumen pelacakan traffic dan klik minat (smoke test) sebelum tahap pemasaran dieksekusi.

---

## 1. Anggota Kelompok
* **Lufthansa Daffa Gilbran ** (12010223140054)
* **Ghiffari Muhammad** (12010223140015)
* **Farrel Eksa** (12010223140014)
* **Muhammad Indra** (12010223140067)
* **Nayla Raihanda** (12010223140005)

*Program Studi S1 Bisnis Digital, Fakultas Ekonomika dan Bisnis, Universitas Diponegoro*

---

## 2. Status & Progres Pengerjaan

### A. Konfigurasi AI Harness Lokal (`AGENTS.md`)
* Menyiapkan file panduan agen lokal (`AGENTS.md`) di direktori proyek.
* Menetapkan batasan teknis: arsitektur berbasis HTML5, TailwindCSS, dan Vanilla JS tanpa dependensi berat.
* Menerapkan aturan kepatuhan data: tidak menyimpan kredensial atau API Key pada repositori publik dan menjaga data pengujian tetap anonim.

### B. Daftar 5 Ide Produk (Uji Minat Pasar Kampus)
Kelima produk dirancang untuk menjawab permasalahan riil mahasiswa di kawasan kampus dan kos Tembalang:
1. **P1 — JasaKu Express:** Layanan titip beli dan kurir mikro area kos dengan skema ongkir terjangkau.
2. **P2 — NebengKampus:** Platform berbagi tumpangan (carpooling) antarmahasiswa terverifikasi untuk efisiensi mobilitas harian.
3. **P3 — LaundryTrack:** Layanan jemput-antar penatu dengan pembaruan status pengerjaan transparan.
4. **P4 — SplitKatering:** Layanan langganan katering harian fleksibel dengan fitur jeda (pause) saat libur/jadwal padat.
5. **P5 — SewaAlatKampus:** Peminjaman perlengkapan acara dan tugas kuliah (proyektor, kamera, audio) antarmahasiswa tanpa syarat penahanan identitas berlebih.

### C. Instrumen Pelacakan Minat & Traffic (`index.html`)
* **Deteksi Sumber Traffic:** Membaca parameter URL (`utm_source` dan `utm_campaign`) untuk memetakan efektivitas saluran distribusi promosi (WhatsApp grup, Instagram Story, TikTok).
* **Pencatatan Konversi (CTR):** Menghitung total kunjungan (pageviews), jumlah klik per produk, dan rasio minat (*Click-Through Rate*) secara otomatis melalui penyimpanan lokal (*local storage*).
* **Dasbor Metrik:** Tabel evaluasi langsung pada halaman untuk menentukan produk dengan performa minat tertinggi sebagai dasar validasi sebelum masuk ke tahap pengembangan aplikasi penuh.

---

## 3. Rencana Langkah Berikutnya
1. Melakukan deployment halaman katalog ke platform hosting statis (GitHub Pages / Cloudflare Pages).
2. Menjalankan kampanye pemasaran terarah pada saluran komunitas mahasiswa menggunakan tautan berparameter UTM.
3. Menganalisis metrik konversi klik untuk memilih satu produk final yang terbukti memiliki kebutuhan pasar tertinggi.
