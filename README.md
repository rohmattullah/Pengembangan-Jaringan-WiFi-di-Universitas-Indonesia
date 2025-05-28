# Rencana Channel Wi-Fi 5 GHz (40 MHz) untuk Lingkungan Padat (Studi Kasus: Universitas di Indonesia)

Dokumen ini menyajikan panduan dan rekomendasi untuk merancang penempatan Channel Wi-Fi (RLAN) pada Frekuensi 5 GHz dengan Channel Width 40 MHz untuk lingkungan dengan kepadatan tinggi (Very High Density - VHD), seperti ruang kelas universitas di Indonesia.

**Studi Kasus:**
* **Lingkungan:** Ruang Kelas Universitas
* **Kepadatan AP:** Tinggi (Jarak antar AP ± 7 meter)
* **Lebar Channel:** 40 MHz
* **Tujuan:** Meminimalkan interferensi antar-channel dan *co-channel*.
* **Regulasi:** Berdasarkan Peraturan Menteri Komunikasi dan Digital RI No. 2 Tahun 2025.

---

## Dasar Regulasi (Indonesia)

Penggunaan spektrum frekuensi radio untuk RLAN di Indonesia diatur oleh Peraturan Menteri Komunikasi dan Digital. Untuk pita 5 GHz dan 6 GHz, pita yang relevan adalah:

* **UNII-1:** 5150-5250 MHz (Hanya Indoor, Maks 200 mW EIRP)
* **UNII-2A:** 5250-5350 MHz (Hanya Indoor, Maks 200 mW EIRP, **Wajib DFS**)
* **UNII-3:** 5725-5825 MHz (Indoor Maks 200 mW EIRP / Outdoor Maks 4W EIRP)
* **Wi-Fi 6E (UNII-5 hingga UNII-8):** 5925-7125 MHz (Secara umum, regulasi Indonesia di Permen No. 2 Tahun 2025 mencakup 5925-6425 MHz untuk RLAN Indoor LPI Maks 200 mW EIRP / Indoor/Outdoor VLP Maks 25 mW EIRP)

Peraturan ini mengizinkan penggunaan bandwidth hingga 160 MHz di UNII-1/2A, hingga 80 MHz di UNII-3 (untuk indoor), dan hingga 320 MHz di Wi-Fi 6E (5925-6425 MHz).

---
