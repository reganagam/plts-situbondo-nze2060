# ☀️ Analisis Tekno-Ekonomi PLTS Skala Utilitas 10 MWp di Situbondo

**Penulis:** Regan Agam (NIM: 24/PTK/552177/16439)  
**Program Studi:** Magister Teknik Elektro, Universitas Gadjah Mada (UGM)  
**Mata Kuliah:** Energi Baru dan Terbarukan (EBT)

## 📌 Ringkasan Proyek
Transisi energi menuju *Net Zero Emission* (NZE) 2060 menuntut akselerasi infrastruktur Pembangkit Listrik Tenaga Surya (PLTS). Proyek ini menyajikan analisis komprehensif mengenai kelayakan tekno-ekonomi untuk perancangan PLTS skala utilitas berkapasitas **10 MWp** di Kabupaten Situbondo, Jawa Timur.

Situbondo dipilih secara strategis karena ketersediaan lahan marginal yang tidak mengganggu produktivitas agrikultur dan tingginya tingkat iradiasi matahari. Proyek ini juga merumuskan mitigasi risiko terkait fluktuasi biaya (*Levelized Cost of Energy* / LCOE), tantangan regulasi (seperti TKDN), dan integrasi grid (seperti fenomena *Duck Curve*).

## 🌍 Analisis Klimatologi & Potensi Energi
Data klimatologi ditarik menggunakan API dari **NASA Prediction of Worldwide Energy Resources (POWER)** untuk mendapatkan baseline produksi energi P50 (tingkat keyakinan 50%), yang kuat terhadap anomali cuaca ekstrem.

*   **Koordinat Lokasi:** -7.7081, 114.0044 (Situbondo, Jawa Timur).
*   **Rata-rata GHI Historis:** 5,68 kWh/m²/hari.

![Tangkapan Layar NASA POWER](assets/SS%20Website%20Dataset%20NASA%20Power.png)

Grafik di bawah ini menunjukkan profil bulanan yang ideal, di mana iradiasi tinggi terjadi konsisten sepanjang tahun dengan puncak pada bulan transisi musim (Oktober).

![Profil Iradiasi dan Suhu](assets/grafik_situbondo_profil.png)

## 🛠️ Performa Teknis Proyek (25 Tahun)
Dengan memperhitungkan metrik teknis dan faktor degradasi panel, PLTS 10 MWp diestimasikan memiliki performa sebagai berikut:

*   **Produksi Energi Tahun ke-1:** 16.180,02 MWh.
*   **Capacity Factor (CF):** 18,47% (sangat tinggi untuk *non-tracking PV* di Asia Tenggara).
*   **Kebutuhan Lahan:** ~10 - 12 Hektar.
*   **Laju Degradasi:** 0,5% per tahun.

Produksi energi dikalkulasi akan tetap solid menopang jaringan hingga akhir siklus hidup proyek (tahun ke-25), seperti yang divisualisasikan di bawah ini:

![Proyeksi Degradasi](assets/grafik_situbondo_degradasi.png)

## 💰 Analisis Sensitivitas Keekonomian (LCOE)
*Levelized Cost of Energy* (LCOE) dihitung dengan membandingkan tiga skenario kebijakan dan ekonomi makro (dengan usia proyek 25 tahun dan OPEX 1.5%).

1.  **Optimis (Dukungan penuh, bunga rendah):** LCOE turun drastis mencapai **3,53 Cent USD/kWh**, menjadikannya sangat bankable.
2.  **Base Case (Kondisi saat ini):** LCOE berada di angka **4,90 Cent USD/kWh** (lebih murah dari Biaya Pokok Penyediaan PLTU batu bara).
3.  **Pesimis (Beban bunga tinggi & pembengkakan CAPEX akibat TKDN):** LCOE melonjak hingga **7,10 Cent USD/kWh**, menandakan tingginya risiko investasi tanpa skema pendanaan yang inovatif.

![Analisis Sensitivitas LCOE](assets/grafik_sensitivitas_lcoe.png)

## 💡 Strategi Implementasi & Mitigasi Risiko
Untuk memastikan proyek ini dapat menjadi tulang punggung NZE 2060, diusulkan *roadmap* strategi berikut:

1.  **Jangka Pendek (Regulasi):** Memberikan relaksasi batas Tingkat Komponen Dalam Negeri (TKDN) sementara waktu untuk menekan *premium cost* pada CAPEX awal dan menarik *Foreign Direct Investment* (FDI).
2.  **Jangka Menengah (Teknologi):** Kewajiban integrasi *Battery Energy Storage System* (BESS) untuk menyimpan daya di siang hari dan mendistribusikannya di malam hari (*peak hour*), mengatasi isu intermitensi dan *Duck Curve*.
3.  **Jangka Panjang (Ekspansi):** Mengonversi kelebihan suplai energi (curtailment) di siang hari menuju fasilitas *electrolyzer* untuk memproduksi **Hidrogen Hijau (Green Hydrogen)** sebagai komoditas ekspor atau penyimpan energi lintas musim.
