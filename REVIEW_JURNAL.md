# REVIEW JURNAL ILMIAH

## Judul Penelitian Penulis:
**"Prediksi Kualitas Udara Menggunakan Metode Regresi dan Machine Learning Berbasis Data Meteorologi Kota Bandung"**

---
> **Disusun oleh:** Vany Salsabila Putri (123450022)  
> **Tanggal Review:** 22 Juni 2026

---

## DAFTAR ISI

1. [Jurnal 1 – Prediksi Kualitas Udara dengan LSTM dan ANN](#jurnal-1)
2. [Jurnal 2 – Air Quality Forecasting Using Machine Learning: Comparative Analysis and Ensemble Strategies](#jurnal-2)
3. [Jurnal 3 – Air Quality Prediction by ML Models: Indian Coastal City Visakhapatnam](#jurnal-3)
4. [Jurnal 4 – Analisis Prediksi Kualitas Udara Berbasis Indeks Menggunakan IoT dan Algoritma ML](#jurnal-4)
5. [Jurnal 5 – Analisis dan Prediksi Indeks Kualitas Udara Jakarta: Penerapan Algoritma XGBoost](#jurnal-5)
6. [Jurnal 6 – Aplikasi Monitor dan Prediksi Tingkat Polusi Udara Berbasis Web dengan Streamlit](#jurnal-6)
7. [Jurnal 7 – Comprehensive Evaluation of ML Models for Real-World Air Quality Prediction and AirQ+](#jurnal-7)
8. [Jurnal 8 – Enhancing Air-Quality Predictions on University Campuses: PM2.5 Forecasting at University of Petroșani](#jurnal-8)
9. [Jurnal 9 – Forecasting Urban Air Quality: A Comparative Study of ML Models for PM2.5 and AQI in Smart Cities](#jurnal-9)
10. [Jurnal 10 – Global Air Quality Index Prediction Using Machine Learning on Major Pollutants](#jurnal-10)
11. [Jurnal 11 – Klasifikasi Indeks Kualitas Udara DKI Jakarta dengan Multinomial Logistic Regression](#jurnal-11)
12. [Jurnal 12 – Machine Learning Models for Advanced Air Quality Prediction](#jurnal-12)
13. [Jurnal 13 – Machine Learning-Based Forecasting of AQI: XGBoost, LightGBM, and SVM](#jurnal-13)
14. [Jurnal 14 – Next Gen AQI Forecasting with Hybrid ML Models and Cloud Synergy](#jurnal-14)
15. [Jurnal 15 – PM2.5 Air Quality Index Prediction Using ML: Evidence from Kuwait](#jurnal-15)
16. [Jurnal 16 – PM2.5 Concentration Prediction Using ML: Virtual Monitoring Stations](#jurnal-16)
17. [Jurnal 17 – Pengujian Algoritma LSTM untuk Prediksi Kualitas Udara dan Suhu Kota Bandung](#jurnal-17)
18. [Jurnal 18 – Prediction of Air Quality Index Using Ensemble Models](#jurnal-18)
19. [Jurnal 19 – Prediksi Kualitas Udara Malang Menggunakan Gradient Boosting Regression](#jurnal-19)
20. [Jurnal 20 – Systematic Review of ML and Deep Learning Techniques for Spatiotemporal Air Quality Prediction](#jurnal-20)
21. [Jurnal 21 – Teknik Machine Learning untuk Analisa Klasifikasi Kualitas Udara: A Review](#jurnal-21)
22. [Kesimpulan Umum & Gap Research](#kesimpulan-umum)

---

<a name="jurnal-1"></a>
## Jurnal 1

**Judul:** Prediksi Kualitas Udara dengan Menggunakan Metode Long Short-Term Memory dan Artificial Neural Network  
**Penulis:** I Gusti Ayu Nandia Lestari, I Nyoman Dwi Arysna Mahendra  
**Sumber:** Jurnal Sistem dan Informatika (JSI), Vol. 17, No. 2, Mei 2023  
**DOI/ISSN:** p-ISSN: 1858-473X, e-ISSN: 2460-3732  
**Nama File:** `565-Article Text-2132-1-10-20230515.PDF`

### Fokus Utama
Jurnal ini berfokus pada perbandingan dua metode deep learning, yaitu Long Short-Term Memory (LSTM) dan Artificial Neural Network (ANN), untuk memprediksi konsentrasi PM2.5 sebagai indikator kualitas udara di DKI Jakarta. Dataset berasal dari Portal Satu Data yang dipublikasikan oleh Dinas Lingkungan Hidup DKI Jakarta, mencakup parameter PM2.5, PM10, CO, SO2, NO2, dan O3.

### Kekuatan
- Menggunakan dua metode berbeda (LSTM dan ANN) sehingga memungkinkan perbandingan langsung yang objektif.
- Data bersumber dari instansi pemerintah resmi (Dinas Lingkungan Hidup DKI Jakarta), sehingga terjamin kualitas dan validitasnya.
- Menyajikan metrik evaluasi yang lengkap: RMSE, MAE, dan MAPE, sehingga memudahkan penilaian performa model secara menyeluruh.
- LSTM terbukti lebih unggul dari ANN dengan RMSE 23.311, MAE 19.391, dan MAPE 0.176, menunjukkan kemampuan pemodelan temporal yang lebih baik.
- Memberikan analisis korelasi antarvariabel yang berguna untuk seleksi fitur (PM2.5 dengan PM10: 0.91).

### Kelemahan
- Lokasi studi hanya mencakup DKI Jakarta, sehingga tidak dapat langsung digeneralisasikan ke kota lain seperti Bandung.
- Tidak mengintegrasikan data meteorologi (suhu, kelembapan, curah hujan, kecepatan angin) yang merupakan faktor penting dalam dispersi polutan.
- Tidak dilakukan perbandingan dengan metode regresi klasik (linear regression, random forest, dll.), sehingga tidak diketahui apakah deep learning benar-benar lebih unggul dibanding ML konvensional.
- Nilai RMSE dan MAPE yang dihasilkan masih relatif tinggi, menunjukkan masih ada ruang perbaikan.
- Tidak membahas tuning hyperparameter secara mendalam.

### Relevansi terhadap Judul Penelitian
Jurnal ini relevan karena memperkenalkan pendekatan prediksi kualitas udara berbasis machine learning. Namun, penelitian ini tidak menggunakan data meteorologi sebagai fitur prediktor, sementara judul penelitian penulis secara eksplisit menyebutkan "berbasis data meteorologi." Jurnal ini dapat menjadi referensi metodologi prediksi berbasis time series (LSTM) untuk dibandingkan dengan regresi.

### Gap Resource
- Tidak ada penggunaan data meteorologi (suhu, tekanan udara, kelembapan, kecepatan angin).
- Tidak ada konteks spasial spesifik selain Jakarta secara umum.
- Tidak membandingkan dengan metode regresi konvensional.
- Tidak menyertakan analisis feature importance untuk mengetahui variabel paling berpengaruh.

### Kesimpulan
Jurnal ini memberikan kontribusi yang baik dalam konteks prediksi PM2.5 menggunakan LSTM dan ANN di Jakarta. Penelitian penulis dapat memperluas cakupannya dengan menggunakan data meteorologi Kota Bandung dan metode regresi sebagai pembanding, serta mempertimbangkan LSTM sebagai salah satu metode alternatif.

---

<a name="jurnal-2"></a>
## Jurnal 2

**Judul:** Air Quality Forecasting Using Machine Learning: Comparative Analysis and Ensemble Strategies for Enhanced Prediction  
**Penulis:** (Tim Peneliti Internasional)  
**Sumber:** Water, Air, & Soil Pollution (2025) 236:464  
**DOI:** https://doi.org/10.1007/s11270-025-08122-8  
**Nama File:** `Air Quality Forecasting Using Machine Learning - Comparative Analysis and Ensemble Strategies for Enhanced Prediction.pdf`

### Fokus Utama
Jurnal ini melakukan analisis komparatif berbagai model machine learning untuk peramalan kualitas udara, termasuk strategi ensemble untuk meningkatkan akurasi prediksi. Penelitian mengevaluasi berbagai model ML dan menggabungkannya dengan pendekatan ensemble (stacking, voting, boosting) untuk mencapai performa prediksi terbaik.

### Kekuatan
- Cakupan metodologi yang sangat luas, mencakup berbagai algoritma ML dan strategi ensemble secara komprehensif.
- Terbit di jurnal internasional bereputasi tinggi (Water, Air, & Soil Pollution, Springer).
- Pendekatan ensemble yang diusulkan mampu meningkatkan akurasi dibanding model tunggal.
- Analisis dilakukan secara mendalam dengan metrik evaluasi yang beragam.
- Kontribusi nyata pada pengembangan sistem prediksi kualitas udara yang lebih robust.

### Kelemahan
- Tidak spesifik pada satu kota atau wilayah tertentu, sehingga kurang memberikan insight lokal.
- Tidak secara khusus mengintegrasikan data meteorologi sebagai fitur dominan.
- Kompleksitas model ensemble menyulitkan interpretasi dan implementasi praktis.
- Data yang digunakan bersifat umum, tidak mencerminkan karakteristik iklim tropis seperti Indonesia.

### Relevansi terhadap Judul Penelitian
Sangat relevan sebagai referensi metodologi komparatif ML. Penelitian penulis dapat mengadopsi pendekatan ensemble strategies untuk meningkatkan akurasi prediksi kualitas udara Kota Bandung berbasis data meteorologi. Jurnal ini juga mendukung pemilihan beberapa algoritma ML untuk dibandingkan.

### Gap Resource
- Tidak ada fokus pada data meteorologi lokal sebagai variabel prediktor utama.
- Tidak ada studi kasus di kota-kota Asia Tenggara atau wilayah beriklim tropis.
- Tidak ada implementasi berbasis platform web atau sistem monitoring real-time.
- Tidak membahas karakteristik musiman/iklim yang spesifik.

### Kesimpulan
Jurnal ini merupakan referensi metodologi yang kuat untuk pendekatan komparatif ML dalam prediksi kualitas udara. Penelitian penulis dapat mengisi gap dengan mengaplikasikan pendekatan serupa namun difokuskan pada data meteorologi Kota Bandung yang memiliki karakteristik iklim tropis khas.

---

<a name="jurnal-3"></a>
## Jurnal 3

**Judul:** Air Quality Prediction by Machine Learning Models: A Predictive Study on the Indian Coastal City of Visakhapatnam  
**Penulis:** (Tim Peneliti India)  
**Sumber:** Chemosphere, 338 (2023) 139518, Elsevier  
**DOI:** Available online 14 July 2023  
**Nama File:** `Air quality prediction by machine learning models - A predictive study on the indian coastal city of Visakhapatnam.pdf`

### Fokus Utama
Penelitian ini mengembangkan model prediksi kualitas udara menggunakan berbagai algoritma ML di kota pesisir Visakhapatnam, India. Studi ini mengeksplorasi hubungan antara data polutan udara dan variabel meteorologi lokal untuk memprediksi AQI dengan lebih akurat.

### Kekuatan
- Diterbitkan di jurnal Chemosphere (Elsevier) yang sangat bereputasi dan terindeks Scopus Q1.
- Mengintegrasikan variabel meteorologi (suhu, kelembapan, kecepatan angin) bersama data polutan.
- Memberikan studi kasus pada kota spesifik dengan karakteristik geografis unik (kota pesisir).
- Membandingkan beberapa algoritma ML secara sistematis.
- Memberikan wawasan tentang pengaruh kondisi meteorologi terhadap dispersi polutan.

### Kelemahan
- Lokasi studi (Visakhapatnam, India) sangat berbeda karakteristik iklimnya dibanding Kota Bandung (dataran tinggi tropis).
- Tidak membahas aspek prediksi berbasis ISPU (Indeks Standar Pencemar Udara) sesuai standar Indonesia.
- Data yang digunakan mungkin tidak mencerminkan pola polusi di kota-kota Indonesia.
- Bahasa penulisan dalam Inggris, sehingga memerlukan adaptasi konteks untuk penelitian Indonesia.

### Relevansi terhadap Judul Penelitian
Sangat relevan karena mengintegrasikan data meteorologi dalam prediksi kualitas udara, sesuai dengan fokus penelitian penulis. Meskipun lokasi berbeda (Visakhapatnam vs Bandung), metodologi penggunaan variabel meteorologi sebagai prediktor dapat diadopsi langsung.

### Gap Resource
- Tidak ada studi pada kota Indonesia, khususnya Kota Bandung.
- Tidak mempertimbangkan karakteristik iklim dataran tinggi tropis.
- Tidak menggunakan parameter ISPU Indonesia.
- Tidak membahas sumber data meteorologi BMKG atau NASA POWER.

### Kesimpulan
Jurnal ini merupakan salah satu referensi terkuat untuk penelitian penulis karena secara langsung membahas penggunaan data meteorologi dalam prediksi kualitas udara dengan ML. Penelitian penulis dapat menjadi versi lokal dari studi ini yang disesuaikan dengan konteks Kota Bandung dan standar Indonesia.

---

<a name="jurnal-4"></a>
## Jurnal 4

**Judul:** Analisis Prediksi Kualitas Udara Berbasis Indeks Menggunakan Internet of Things dan Algoritma Machine Learning  
**Penulis:** (Peneliti Indonesia)  
**Sumber:** Jurnal Indonesia  
**Nama File:** `Analisis Prediksi Kualitas Udara Berbasis Indeks Menggunakan Internet Of Things dan Algoritma ML.pdf`

### Fokus Utama
Jurnal ini mengintegrasikan teknologi Internet of Things (IoT) dengan algoritma machine learning untuk memantau dan memprediksi kualitas udara secara real-time berbasis indeks. Sensor IoT digunakan untuk pengumpulan data kualitas udara secara otomatis yang kemudian diproses dengan algoritma ML.

### Kekuatan
- Inovatif dalam mengintegrasikan IoT dengan ML untuk monitoring kualitas udara secara real-time.
- Relevan dengan perkembangan teknologi smart city di Indonesia.
- Berbasis data aktual yang dikumpulkan langsung dari sensor lapangan.
- Menggunakan pendekatan berbasis indeks yang sesuai dengan standar ISPU Indonesia.
- Memberikan kontribusi pada pengembangan sistem peringatan dini kualitas udara.

### Kelemahan
- Implementasi IoT memerlukan infrastruktur dan biaya yang tidak selalu tersedia.
- Akurasi sangat bergantung pada kualitas sensor yang digunakan.
- Tidak membahas integrasi data meteorologi dari sumber resmi (BMKG).
- Cakupan penelitian terbatas pada area pemasangan sensor IoT.
- Tidak memperhitungkan keterbatasan jaringan internet di daerah tertentu.

### Relevansi terhadap Judul Penelitian
Cukup relevan dalam konteks penggunaan algoritma ML untuk prediksi kualitas udara berbasis indeks. Namun, penelitian penulis menggunakan data meteorologi historis (bukan sensor IoT real-time), sehingga relevansinya lebih pada bagian metodologi ML-nya.

### Gap Resource
- Tidak menggunakan data meteorologi historis dari BMKG atau NASA POWER.
- Tidak fokus pada satu kota secara mendalam (Bandung).
- Tidak membandingkan dengan metode regresi konvensional.
- Tidak ada analisis jangka panjang berdasarkan data historis.

### Kesimpulan
Jurnal ini memberikan perspektif alternatif pengumpulan data kualitas udara melalui IoT. Penelitian penulis mengisi gap ini dengan menggunakan data meteorologi historis yang lebih komprehensif dari sumber resmi, sehingga dapat menghasilkan analisis jangka panjang yang lebih valid.

---

<a name="jurnal-5"></a>
## Jurnal 5

**Judul:** Analisis dan Prediksi Indeks Kualitas Udara Jakarta: Penerapan Algoritma XGBoost  
**Penulis:** Evandha Mustika Sari, Cahya Sabila, Rifqi Fakhrizal Adam, Robert Kurniawan  
**Sumber:** Jurnal Nasional Teknologi dan Sistem Informasi, Vol. 11 No. 02 (2025) 161-169  
**DOI:** https://doi.org/10.25077/TEKNOSI.v11i2.2025.161-169  
**Nama File:** `Analisis dan Prediksi Indeks Kualitas Udara Jakarta Penerapan Algoritma XGBoost.pdf`

### Fokus Utama
Penelitian ini menganalisis dan memprediksi Indeks Kualitas Udara (IKU) di DKI Jakarta menggunakan algoritma XGBoost (eXtreme Gradient Boosting). Data yang digunakan merupakan data kualitas udara dari stasiun pemantauan di Jakarta dengan parameter PM10, PM2.5, SO2, CO, O3, dan NO2.

### Kekuatan
- Menggunakan XGBoost yang merupakan algoritma ensemble state-of-the-art dengan performa tinggi.
- Menggunakan dataset kualitas udara DKI Jakarta yang lengkap dan terstruktur.
- Menyajikan analisis statistik deskriptif dan visualisasi data yang informatif.
- Menggunakan metrik evaluasi komprehensif (akurasi, RMSE, MAE).
- Konteks lokal Indonesia memudahkan adaptasi untuk penelitian penulis.
- Terbit di jurnal nasional terakreditasi.

### Kelemahan
- Tidak mengintegrasikan variabel meteorologi dalam model prediksi.
- Hanya mencakup DKI Jakarta, tidak ada studi perbandingan dengan kota lain.
- Tidak membahas pentingnya karakteristik meteorologi lokal (curah hujan, suhu, angin) terhadap AQI.
- Tidak ada pembahasan tentang feature importance secara mendalam.
- Tidak membandingkan XGBoost dengan algoritma lain secara eksplisit.

### Relevansi terhadap Judul Penelitian
Relevan karena menggunakan XGBoost untuk prediksi IKU di konteks Indonesia. Penelitian penulis dapat mengadopsi XGBoost sebagai salah satu algoritma yang dibandingkan, namun dengan penambahan fitur meteorologi Kota Bandung sebagai kebaruan.

### Gap Resource
- Tidak ada data meteorologi (suhu, kelembapan, kecepatan angin, curah hujan).
- Tidak ada studi untuk Kota Bandung dengan karakteristik geografis pegunungan.
- Tidak membandingkan XGBoost dengan metode regresi linier atau non-linear lainnya.
- Tidak ada analisis pengaruh variabel meteorologi terhadap konsentrasi polutan.

### Kesimpulan
Jurnal ini menjadi referensi yang baik untuk penggunaan XGBoost dalam prediksi IKU di Indonesia. Penelitian penulis dapat memperluas pendekatan ini dengan menambahkan variabel meteorologi Kota Bandung, sehingga memberikan model prediksi yang lebih komprehensif dan kontekstual.

---

<a name="jurnal-6"></a>
## Jurnal 6

**Judul:** Aplikasi Monitor dan Prediksi Tingkat Polusi Udara Berbasis Web dengan Streamlit  
**Penulis:** (Peneliti Indonesia)  
**Sumber:** Jurnal Media Informatika (JUMIN), Volume 7 No. 1 Edisi Januari-Februari 2026  
**ISSN:** 2808-005X  
**Nama File:** `Aplikasi Monitor dan Prediksi Tingkat Polusi Udara Berbasis Web dengan Streamlit.pdf`

### Fokus Utama
Penelitian ini mengembangkan aplikasi berbasis web menggunakan framework Streamlit untuk memantau dan memprediksi tingkat polusi udara secara interaktif. Penelitian mengintegrasikan model machine learning ke dalam antarmuka web yang dapat diakses oleh pengguna umum.

### Kekuatan
- Memberikan kontribusi praktis berupa implementasi sistem monitoring berbasis web yang dapat digunakan publik.
- Menggunakan Streamlit yang memungkinkan visualisasi data interaktif dan real-time.
- Pendekatan yang berorientasi pada pengguna akhir (user-friendly).
- Menunjukkan kemungkinan deployment model ML ke dalam aplikasi nyata.
- Kontribusi pada aspek accessibility informasi kualitas udara bagi masyarakat.

### Kelemahan
- Fokus lebih pada pengembangan aplikasi daripada kedalaman analisis model ML.
- Tidak membahas validasi model prediksi secara mendalam.
- Tidak menggunakan data meteorologi sebagai fitur prediktor.
- Kualitas model prediksi yang digunakan tidak dijelaskan secara detail.
- Ketergantungan pada konektivitas internet untuk operasional aplikasi.

### Relevansi terhadap Judul Penelitian
Relevansinya bersifat implementatif: penelitian penulis dapat mempertimbangkan deployment model prediksi ke dalam platform web sebagai output tambahan. Namun, jurnal ini tidak memberikan kontribusi metodologi prediksi yang kuat.

### Gap Resource
- Tidak ada integrasi data meteorologi.
- Tidak ada validasi model dengan data uji yang ketat.
- Tidak spesifik pada kota tertentu dengan karakteristik lokal.
- Tidak ada perbandingan performa antar model ML.

### Kesimpulan
Jurnal ini memberikan inspirasi untuk aspek implementasi dan visualisasi hasil prediksi kualitas udara. Penelitian penulis dapat mengembangkan antarmuka serupa untuk menyajikan hasil prediksi kualitas udara Kota Bandung secara interaktif, namun dengan kedalaman analisis yang jauh lebih kuat.

---

<a name="jurnal-7"></a>
## Jurnal 7

**Judul:** Comprehensive Evaluation of Machine Learning Models for Real-World Air Quality Prediction and Health Risk Assessment by AirQ+  
**Penulis:** (Tim Peneliti Internasional)  
**Sumber:** Earth Science Informatics (2025) 18:447, Springer  
**DOI:** https://doi.org/10.1007/s12145-025-01941-7  
**Nama File:** `Comprehensive Evaluation of Machine Learning Models for Real-World Air Quality Prediction and Health Risk Assessment by AirQ+.pdf`

### Fokus Utama
Jurnal ini melakukan evaluasi komprehensif berbagai model ML untuk prediksi kualitas udara di dunia nyata, sekaligus mengintegrasikan penilaian risiko kesehatan menggunakan software AirQ+. Penelitian mencakup evaluasi end-to-end dari akurasi prediksi hingga dampak kesehatan masyarakat.

### Kekuatan
- Pendekatan holistik yang menggabungkan prediksi kualitas udara dengan penilaian risiko kesehatan.
- Diterbitkan di jurnal internasional Springer yang bereputasi tinggi (Scopus Q1).
- Menggunakan berbagai model ML yang dievaluasi secara komprehensif.
- Integrasi dengan AirQ+ memberikan perspektif kesehatan masyarakat yang berharga.
- Metodologi evaluasi yang sangat rigorous dan terstruktur.

### Kelemahan
- Tidak spesifik pada satu kota/wilayah dengan karakteristik lokal.
- AirQ+ mungkin tidak sesuai dengan standar penilaian risiko kesehatan Indonesia.
- Tidak membahas secara khusus peran data meteorologi lokal.
- Kompleksitas metodologi mungkin sulit direplikasi dengan sumber daya terbatas.

### Relevansi terhadap Judul Penelitian
Relevan dalam konteks evaluasi model ML yang komprehensif. Penelitian penulis dapat mengadopsi kerangka evaluasi yang serupa, khususnya dalam memilih dan membandingkan beberapa model ML menggunakan data meteorologi Kota Bandung.

### Gap Resource
- Tidak ada studi pada kota-kota Indonesia dengan standar ISPU lokal.
- Tidak ada analisis data meteorologi tropis.
- Tidak membahas karakteristik musiman Indonesia (musim hujan vs kemarau).
- Tidak ada fokus pada model regresi konvensional sebagai baseline.

### Kesimpulan
Jurnal ini memperkuat justifikasi penggunaan pendekatan multi-model dalam evaluasi prediksi kualitas udara. Penelitian penulis dapat mengisi gap dengan menerapkan evaluasi serupa pada data spesifik Kota Bandung dengan penekanan pada variabel meteorologi lokal.

---

<a name="jurnal-8"></a>
## Jurnal 8

**Judul:** Enhancing Air-Quality Predictions on University Campuses: A Machine-Learning Approach to PM2.5 Forecasting at the University of Petroșani  
**Penulis:** Panaite, F.A.; Rus, C.; Leba, M.; Ionica, A.C.; Windisch, M.  
**Sumber:** Sustainability (MDPI), Vol. 16 (2024)  
**Nama File:** `Enhancing Air-Quality Predictions on University Campuses - A Machine-Learning Approach to PM2.5 Forecasting at the University of Petrosani.pdf`

### Fokus Utama
Penelitian ini berfokus pada prediksi PM2.5 di lingkungan kampus Universitas Petroșani, Romania, menggunakan pendekatan machine learning. Studi ini mengeksplorasi bagaimana karakteristik lokasi spesifik (kampus universitas) mempengaruhi kualitas udara dan model prediksinya.

### Kekuatan
- Studi kasus yang sangat spesifik pada lokasi terbatas (kampus universitas) memungkinkan analisis yang mendalam.
- Mengintegrasikan data meteorologi lokal dalam model prediksi PM2.5.
- Metodologi yang dapat diadaptasi untuk lokasi-lokasi spesifik lainnya.
- Diterbitkan di jurnal MDPI Sustainability yang terindeks internasional.
- Memberikan insight tentang pengaruh aktivitas lokal terhadap kualitas udara.

### Kelemahan
- Konteks geografis dan iklim sangat berbeda (Eropa Timur vs Indonesia).
- Tidak relevan secara langsung dengan kondisi kualitas udara perkotaan di Indonesia.
- Skala penelitian terbatas (satu kampus) sehingga kurang mewakili kota secara keseluruhan.
- Pola pencemaran udara di Eropa berbeda signifikan dengan Indonesia.

### Relevansi terhadap Judul Penelitian
Relevan secara metodologi karena menggunakan data meteorologi sebagai fitur prediksi PM2.5 dengan ML. Pendekatan ini dapat diadaptasi untuk konteks Kota Bandung, meskipun karakteristik geografis dan klimatologi berbeda jauh.

### Gap Resource
- Tidak ada penelitian serupa di Indonesia, khususnya Kota Bandung.
- Tidak mempertimbangkan karakteristik iklim tropis basah.
- Tidak membahas pengaruh musim hujan dan kemarau terhadap PM2.5.
- Tidak ada data dari sumber Indonesia (BMKG, KLHK).

### Kesimpulan
Jurnal ini memperkuat argumentasi penggunaan data meteorologi dalam prediksi PM2.5. Penelitian penulis berpeluang menjadi studi serupa namun dalam konteks Kota Bandung dengan karakteristik iklim tropis, mengisi gap penelitian di kawasan Asia Tenggara.

---

<a name="jurnal-9"></a>
## Jurnal 9

**Judul:** Forecasting Urban Air Quality: A Comparative Study of ML Models for PM2.5 and AQI in Smart Cities  
**Penulis:** Arman Khan, Karan Singh  
**Sumber:** Journal of Scientific Innovation and Advanced Research (JSIAR), Volume 1, Issue 2, May 2025  
**Nama File:** `Forecasting Urban Air Quality - A Comparative Study of ML Models for PM2.5 and AQI in Smart Cities.pdf`

### Fokus Utama
Penelitian ini melakukan studi komparatif berbagai model ML untuk peramalan kualitas udara perkotaan, dengan fokus pada PM2.5 dan AQI di konteks smart city. Penelitian mengeksplorasi performa relatif berbagai algoritma seperti Random Forest, XGBoost, SVM, dan ANN.

### Kekuatan
- Konteks smart city yang relevan dengan pengembangan kota cerdas di Indonesia.
- Perbandingan langsung beberapa algoritma ML memudahkan pemilihan metode terbaik.
- Fokus ganda pada PM2.5 dan AQI memberikan cakupan yang komprehensif.
- Relevansi tinggi dalam era digitalisasi monitoring lingkungan.

### Kelemahan
- Tidak spesifik pada kota Asia Tenggara atau Indonesia.
- Tidak mengintegrasikan data meteorologi secara eksplisit sebagai fitur utama.
- Dataset yang digunakan tidak jelas sumbernya.
- Tidak membahas aspek seasonality (musim hujan/kemarau) yang penting untuk Indonesia.

### Relevansi terhadap Judul Penelitian
Relevan sebagai referensi studi komparatif ML untuk prediksi PM2.5 dan AQI. Penelitian penulis dapat mengadopsi pendekatan komparatif ini dengan menambahkan variabel meteorologi spesifik Kota Bandung.

### Gap Resource
- Tidak ada studi pada kota Indonesia dengan karakteristik tropis.
- Tidak membahas pengaruh data meteorologi terhadap prediksi.
- Tidak ada model regresi konvensional sebagai baseline.
- Tidak mempertimbangkan pola musiman Indonesia.

### Kesimpulan
Jurnal ini menjadi referensi yang baik untuk justifikasi pendekatan komparatif ML. Penelitian penulis dapat mengisi gap dengan studi spesifik Kota Bandung menggunakan data meteorologi BMKG, yang belum ada dalam literatur yang ada.

---

<a name="jurnal-10"></a>
## Jurnal 10

**Judul:** Global Air Quality Index Prediction Using Machine Learning on Major Pollutants  
**Penulis:** (Tim Peneliti)  
**Sumber:** Journal of Applied Data Sciences, Vol. 7, No. 1, January 2026, pp. 802-814  
**ISSN:** 2723-6471  
**Nama File:** `Global Air Quality Index Prediction Using Machine Learning on Major Pollutants.pdf`

### Fokus Utama
Penelitian ini mengembangkan model prediksi AQI global menggunakan machine learning dengan fokus pada polutan-polutan utama. Pendekatan global ini bertujuan mengidentifikasi pola umum kualitas udara di berbagai wilayah dan menguji apakah model dapat digeneralisasi lintas lokasi.

### Kekuatan
- Perspektif global memberikan gambaran perbandingan kualitas udara antar kota/negara.
- Menggunakan data polutan utama (PM2.5, PM10, O3, NO2, SO2, CO) secara komprehensif.
- Terbit di jurnal internasional terbaru (2026), mencerminkan state-of-the-art.
- Memberikan benchmark global yang berguna untuk evaluasi kondisi lokal.

### Kelemahan
- Pendekatan global cenderung mengabaikan karakteristik lokal dan regional.
- Data meteorologi tidak diintegrasikan secara spesifik.
- Model global mungkin tidak optimal untuk prediksi pada kota tertentu seperti Bandung.
- Karakteristik iklim tropis Indonesia mungkin tidak tercermin dalam model global.

### Relevansi terhadap Judul Penelitian
Relevan sebagai referensi metode ML untuk prediksi AQI. Namun, penelitian penulis lebih spesifik (Kota Bandung) dan menggunakan data meteorologi, sehingga berpotensi menghasilkan model yang lebih akurat untuk konteks lokal.

### Gap Resource
- Tidak ada fokus pada kota-kota Indonesia.
- Tidak ada data meteorologi lokal sebagai prediktor.
- Tidak ada perbandingan metode regresi vs ML.
- Tidak mempertimbangkan keunikan iklim tropis dan topografi Bandung.

### Kesimpulan
Jurnal ini memberikan perspektif global yang berguna sebagai pembanding. Penelitian penulis berpotensi memberikan kontribusi lebih spesifik dengan membuktikan bahwa model berbasis data meteorologi lokal Kota Bandung dapat menghasilkan prediksi yang lebih akurat dibanding model global generik.

---

<a name="jurnal-11"></a>
## Jurnal 11

**Judul:** Klasifikasi Indeks Kualitas Udara DKI Jakarta dengan Multinomial Logistic Regression Berbasis Machine Learning  
**Penulis:** Alma, dkk.  
**Sumber:** Jurnal Teknologi Maritim, Volume 8 No 2 Tahun 2025  
**Nama File:** `Klasifikasi Indeks Kualitas Udara DKI Jakarta dengan Multinomial Logistic RegressionBerbasis Machine Learning.pdf`

### Fokus Utama
Penelitian ini mengklasifikasikan Indeks Kualitas Udara (IKU) DKI Jakarta menggunakan metode Multinomial Logistic Regression berbasis machine learning. Data PM10, PM2.5, SO2, CO, O3, dan NO2 dari stasiun pemantauan Jakarta digunakan untuk mengklasifikasikan kategori IKU (BAIK, SEDANG, TIDAK SEHAT, SANGAT TIDAK SEHAT).

### Kekuatan
- Menggunakan metode regresi logistik multinomial yang sangat relevan dengan judul penelitian penulis (regresi).
- Menggunakan data dari sumber resmi pemerintah (satudata.jakarta.go.id).
- Menerapkan teknik oversampling SMOTE untuk menangani class imbalance.
- Menyajikan metrik evaluasi lengkap: akurasi (91.4%), precision, recall, F1-score, AUC.
- Konteks lokal Indonesia memudahkan adaptasi.
- Membahas statistik deskriptif yang informatif.

### Kelemahan
- Hanya menggunakan data polutan, tidak mengintegrasikan variabel meteorologi.
- Pendekatan klasifikasi, bukan regresi prediktif nilai AQI secara kontinu.
- Terbatas pada DKI Jakarta, tidak mencakup kota lain seperti Bandung.
- Tidak membahas faktor temporal (tren kualitas udara dari waktu ke waktu).
- Tidak mempertimbangkan pengaruh musim dan cuaca.

### Relevansi terhadap Judul Penelitian
Relevansi tinggi karena menggunakan metode regresi logistik (salah satu jenis regresi) dalam konteks kualitas udara Indonesia. Penelitian penulis dapat mengembangkan pendekatan ini ke bentuk regresi prediktif nilai AQI kontinu dengan menambahkan fitur meteorologi Kota Bandung.

### Gap Resource
- Tidak ada data meteorologi sebagai fitur prediktor.
- Tidak ada studi untuk Kota Bandung.
- Tidak membandingkan regresi logistik dengan algoritma ML lainnya secara luas.
- Tidak ada analisis pengaruh musim (hujan/kemarau) terhadap IKU.

### Kesimpulan
Jurnal ini menjadi salah satu referensi paling relevan bagi penelitian penulis, terutama dalam penggunaan metode regresi untuk klasifikasi IKU. Penelitian penulis dapat memperluas pendekatan ini dengan: (1) menggunakan regresi untuk prediksi nilai AQI kontinu, (2) menambahkan variabel meteorologi, dan (3) menerapkan pada Kota Bandung.

---

<a name="jurnal-12"></a>
## Jurnal 12

**Judul:** Machine Learning Models for Advanced Air Quality Prediction  
**Penulis:** Zuhra Sadriddin  
**Sumber:** Jurnal Internasional (Universitas Alatoo, Kyrgyzstan)  
**Nama File:** `Machine Learning Models for Advanced Air Quality Prediction.pdf`

### Fokus Utama
Penelitian ini mengeksplorasi berbagai model machine learning untuk prediksi kualitas udara secara advanced, termasuk model-model deep learning dan ensemble. Penelitian berfokus pada peningkatan akurasi prediksi menggunakan teknik ML terkini.

### Kekuatan
- Memberikan gambaran komprehensif tentang model ML terkini untuk prediksi kualitas udara.
- Mencakup berbagai pendekatan dari tradisional hingga deep learning.
- Berguna sebagai referensi untuk state-of-the-art dalam bidang ini.

### Kelemahan
- Tidak ada studi kasus pada kota tertentu di Indonesia.
- Tidak membahas integrasi data meteorologi secara spesifik.
- Konteks geografis sangat berbeda (Kyrgyzstan).
- Keterbatasan pada aspek lokal dan kontekstual.

### Relevansi terhadap Judul Penelitian
Relevan sebagai referensi umum untuk model ML dalam prediksi kualitas udara. Membantu penulis dalam memilih dan memahami berbagai algoritma yang dapat diaplikasikan.

### Gap Resource
- Tidak ada studi pada Indonesia atau kota-kota dengan iklim tropis.
- Tidak membahas data meteorologi lokal.
- Tidak ada perbandingan dengan metode regresi konvensional.

### Kesimpulan
Jurnal ini berguna sebagai referensi metodologi umum. Penelitian penulis memberikan nilai tambah dengan fokus pada konteks spesifik Kota Bandung dengan data meteorologi lokal.

---

<a name="jurnal-13"></a>
## Jurnal 13

**Judul:** Machine Learning-Based Forecasting of Air Quality Index Under Long-Term Environmental Patterns: A Comparative Approach with XGBoost, LightGBM, and SVM  
**Penulis:** Tırınk S.  
**Sumber:** PLOS One, October 8, 2025  
**DOI:** https://doi.org/10.1371/journal.pone.0334252  
**Nama File:** `Machine Learning-Based Forecasting of Air Quality Index Under Long-Term Environmental Patterns - A Comparative Approach with XGBoost, LightGBM, and.pdf`

### Fokus Utama
Penelitian ini melakukan peramalan AQI menggunakan tiga algoritma ML populer (XGBoost, LightGBM, SVM) dengan data jangka panjang. Penelitian menganalisis pola lingkungan jangka panjang dan bagaimana model ML dapat menangkap pola tersebut untuk prediksi yang akurat.

### Kekuatan
- Diterbitkan di PLOS One (open access, peer-reviewed internasional).
- Membandingkan tiga algoritma populer (XGBoost, LightGBM, SVM) secara sistematis.
- Menggunakan data jangka panjang yang mencerminkan pola lingkungan yang sesungguhnya.
- LightGBM umumnya menunjukkan keunggulan dalam hal kecepatan komputasi.
- Memberikan insight tentang pola temporal jangka panjang kualitas udara.

### Kelemahan
- Tidak secara eksplisit mengintegrasikan data meteorologi sebagai fitur prediktor.
- Tidak ada konteks Indonesia atau Bandung.
- Tidak membahas pengaruh topografi (dataran tinggi Bandung) terhadap dispersi polutan.
- Tidak membandingkan dengan model regresi linear sebagai baseline.

### Relevansi terhadap Judul Penelitian
Sangat relevan karena membandingkan XGBoost, LightGBM, dan SVM — algoritma-algoritma yang dapat dipertimbangkan dalam penelitian penulis. Metodologi perbandingan yang digunakan dapat diadopsi untuk studi Kota Bandung.

### Gap Resource
- Tidak ada data meteorologi sebagai fitur dominan.
- Tidak ada studi pada kota-kota tropis Indonesia.
- Tidak ada integrasi data cuaca dari BMKG.
- Tidak ada analisis pengaruh musim hujan/kemarau.

### Kesimpulan
Jurnal ini merupakan referensi metodologi yang sangat baik untuk pendekatan komparatif ML (XGBoost, LightGBM, SVM). Penelitian penulis dapat mengadopsi desain studi ini dengan menambahkan data meteorologi Kota Bandung dan metode regresi sebagai baseline.

---

<a name="jurnal-14"></a>
## Jurnal 14

**Judul:** Next Gen AQI Forecasting with Hybrid ML Models and Cloud Synergy  
**Penulis:** (Tim Peneliti Internasional)  
**Sumber:** International Journal of Engineering Trends and Technology, Volume 73, Issue 8  
**ISSN:** 2231-5381  
**Nama File:** `Next Gen AQI Forecasting with Hybrid ML Models and Cloud Synergy.pdf`

### Fokus Utama
Penelitian ini mengeksplorasi pendekatan hybrid machine learning yang dikombinasikan dengan cloud computing untuk peramalan AQI generasi berikutnya. Penelitian berfokus pada sinergi antara model ML hybrid dan infrastruktur cloud untuk meningkatkan skalabilitas dan akurasi prediksi.

### Kekuatan
- Inovatif dalam mengintegrasikan ML hybrid dengan cloud computing untuk prediksi AQI.
- Memberikan solusi skalabel yang dapat diimplementasikan pada skala kota besar.
- Pendekatan hybrid menggabungkan keunggulan beberapa model sekaligus.
- Relevan dengan perkembangan infrastruktur digital masa depan.

### Kelemahan
- Pendekatan hybrid dan cloud complex memerlukan infrastruktur yang tidak selalu tersedia.
- Tidak spesifik pada satu wilayah atau karakteristik lokal.
- Tidak membahas integrasi data meteorologi secara mendalam.
- Biaya implementasi cloud mungkin tidak sesuai untuk penelitian skala kecil.

### Relevansi terhadap Judul Penelitian
Relevan sebagai referensi metodologi hybrid ML. Namun, penelitian penulis lebih praktis dan terfokus pada data lokal, sehingga relevansinya lebih terbatas pada konsep dasar model hybrid.

### Gap Resource
- Tidak ada studi pada kota-kota Indonesia.
- Tidak membahas penggunaan data meteorologi lokal.
- Tidak ada baseline regresi konvensional.
- Tidak mempertimbangkan keterbatasan sumber daya komputasi lokal.

### Kesimpulan
Jurnal ini memberikan gambaran tentang tren terkini dalam prediksi AQI menggunakan hybrid ML. Penelitian penulis lebih kontekstual dengan menggunakan metode yang lebih terjangkau dan data meteorologi yang dapat diakses secara lokal di Kota Bandung.

---

<a name="jurnal-15"></a>
## Jurnal 15

**Judul:** PM2.5: Air Quality Index Prediction Using Machine Learning: Evidence from Kuwait's Air Quality Monitoring Stations  
**Penulis:** (Tim Peneliti Kuwait)  
**Sumber:** Sustainability (MDPI), 2025  
**Nama File:** `PM2.5 - Air Quality Index Prediction Using Machine Learning - Evidence from Kuwait's Air Quality Monitoring Stations.pdf`

### Fokus Utama
Penelitian ini menggunakan data dari stasiun pemantauan kualitas udara Kuwait untuk memprediksi AQI berbasis PM2.5 dengan machine learning. Penelitian ini menggunakan dataset resmi dari jaringan stasiun pemantauan nasional Kuwait.

### Kekuatan
- Menggunakan data dari jaringan stasiun pemantauan resmi yang terstruktur.
- Diterbitkan di MDPI Sustainability yang diindeks internasional.
- Memberikan contoh nyata penggunaan data stasiun pemantauan untuk prediksi ML.
- Analisis komprehensif dengan berbagai model ML.
- Memberikan insight tentang karakteristik PM2.5 dalam konteks perkotaan.

### Kelemahan
- Karakteristik iklim Kuwait (gurun, kering) sangat berbeda dari Bandung (tropis, lembab, dataran tinggi).
- Sumber polutan di Kuwait (petrokimia) berbeda dari Bandung (transportasi, industri).
- Tidak mengintegrasikan variabel meteorologi secara komprehensif.
- Tidak relevan secara langsung untuk konteks Indonesia.

### Relevansi terhadap Judul Penelitian
Relevan secara metodologi dalam penggunaan data stasiun pemantauan untuk prediksi PM2.5 dengan ML. Penelitian penulis dapat mengadopsi pendekatan metodologi serupa namun dengan data dari stasiun pemantauan KLHK/BMKG di Kota Bandung.

### Gap Resource
- Tidak ada studi di wilayah iklim tropis.
- Tidak ada data meteorologi tropis.
- Tidak ada studi perbandingan dengan metode regresi.
- Tidak ada konteks Indonesia.

### Kesimpulan
Jurnal ini menunjukkan bahwa prediksi PM2.5 berbasis data stasiun pemantauan dapat dilakukan dengan baik menggunakan ML. Penelitian penulis mengisi gap dengan menerapkan pendekatan serupa di Kota Bandung dengan karakteristik iklim tropis dan penambahan variabel meteorologi.

---

<a name="jurnal-16"></a>
## Jurnal 16

**Judul:** PM2.5 Concentration Prediction Using Machine Learning Algorithms: An Approach to Virtual Monitoring Stations  
**Penulis:** Ahmad Makhdoomi, Maryam Sarkhosh & Somayyeh Ziaei  
**Sumber:** Scientific Reports (Nature), 2025  
**DOI:** 10.1038/s41598-025-92019-3  
**Nama File:** `PM2.5 Concentration Prediction Using Machine Learning Algorithms - An Approach to Virtual Monitoring Stations.pdf`

### Fokus Utama
Penelitian ini menggunakan algoritma ML (LGBM, XGBR, RF, GBR) untuk memprediksi konsentrasi PM2.5 sebagai pendekatan untuk menciptakan "virtual monitoring stations" — prediksi kualitas udara di lokasi yang tidak memiliki sensor fisik. Ini memungkinkan perluasan jangkauan monitoring kualitas udara secara cost-effective.

### Kekuatan
- Diterbitkan di Scientific Reports (Nature Publishing Group) — jurnal internasional top.
- Konsep virtual monitoring station sangat inovatif dan praktis untuk negara berkembang.
- Membandingkan empat algoritma ML berbasis gradient boosting (LGBM, XGBR, RF, GBR).
- Menggunakan data meteorologi sebagai fitur prediksi.
- Solusi cost-effective untuk memperluas jaringan monitoring.

### Kelemahan
- Konteks geografis berbeda (Timur Tengah/Iran).
- Tidak ada validasi pada kondisi iklim tropis.
- Tidak membahas adaptasi untuk standar ISPU Indonesia.
- Data meteorologi yang digunakan mungkin berbeda karakteristiknya dari Bandung.

### Relevansi terhadap Judul Penelitian
**Sangat relevan** — jurnal ini secara langsung menggunakan data meteorologi dengan algoritma ML (LGBM, XGBR, RF, GBR) untuk prediksi PM2.5, sangat sesuai dengan fokus penelitian penulis. Konsep virtual monitoring station dapat diadopsi untuk lokasi-lokasi di Kota Bandung yang tidak memiliki stasiun pemantauan.

### Gap Resource
- Tidak ada studi di Indonesia/Asia Tenggara.
- Tidak ada perbandingan dengan metode regresi konvensional.
- Tidak mempertimbangkan karakteristik iklim tropis lembab.
- Tidak ada integrasi dengan standar ISPU Indonesia.

### Kesimpulan
Ini adalah salah satu jurnal paling relevan untuk penelitian penulis. Pendekatan penggunaan data meteorologi dengan berbagai algoritma ML gradient boosting dapat langsung diadaptasi untuk Kota Bandung. Penelitian penulis berpotensi menjadi replikasi yang diperkaya dengan konteks Indonesia dan penambahan metode regresi konvensional sebagai baseline.

---

<a name="jurnal-17"></a>
## Jurnal 17

**Judul:** Pengujian Algoritma LSTM untuk Prediksi Kualitas Udara dan Suhu Kota Bandung  
**Penulis:** (Peneliti Indonesia)  
**Sumber:** Jurnal Nasional Indonesia  
**Nama File:** `Pengujian Algoritma LSTM untuk Prediksi Kualitas Udara dan Suhu kota Bandung.pdf`

### Fokus Utama
Penelitian ini menguji algoritma Long Short-Term Memory (LSTM) untuk memprediksi kualitas udara **dan suhu** di **Kota Bandung**. Ini merupakan salah satu sedikit penelitian yang secara spesifik berfokus pada Kota Bandung sebagai lokasi studi.

### Kekuatan
- **Lokasi studi Kota Bandung** — sangat relevan langsung dengan penelitian penulis.
- Menggunakan LSTM yang efektif untuk data time series.
- Mempertimbangkan suhu sebagai variabel yang berkaitan dengan kualitas udara.
- Memberikan baseline data dan pemahaman tentang kondisi kualitas udara Bandung.
- Konteks lokal Indonesia yang kuat.

### Kelemahan
- Hanya menggunakan LSTM, tidak membandingkan dengan metode regresi atau ML lainnya.
- File PDF terenkripsi sehingga terbatas dalam ekstraksi konten.
- Tidak diketahui apakah menggunakan data meteorologi komprehensif (selain suhu).
- LSTM memerlukan data historis yang panjang dan komputasi yang intensif.
- Tidak membahas variabel meteorologi lain (curah hujan, kelembapan, kecepatan angin).

### Relevansi terhadap Judul Penelitian
**Paling relevan** dari semua jurnal karena memiliki lokasi studi yang sama persis: **Kota Bandung**. Jurnal ini menjadi referensi langsung untuk kondisi kualitas udara Bandung dan pendekatan prediksi yang telah dilakukan sebelumnya.

### Gap Resource
- Hanya menggunakan LSTM, tidak ada perbandingan dengan regresi atau ML lain.
- Tidak diketahui kelengkapan data meteorologi yang digunakan.
- Tidak ada analisis feature importance variabel meteorologi.
- Tidak membahas dampak musim hujan/kemarau terhadap kualitas udara Bandung.

### Kesimpulan
Jurnal ini adalah referensi paling relevan karena berlokasi di Kota Bandung. Penelitian penulis memperluas studi ini dengan: (1) menambahkan metode regresi dan beberapa algoritma ML sebagai perbandingan, (2) menggunakan data meteorologi yang lebih komprehensif, dan (3) melakukan analisis pengaruh masing-masing variabel meteorologi terhadap kualitas udara Bandung.

---

<a name="jurnal-18"></a>
## Jurnal 18

**Judul:** Prediction of Air Quality Index Using Ensemble Models  
**Penulis:** Theresia Herlina Rochadiani  
**Sumber:** Journal of Applied Informatics and Computing (JAIC), Vol. 8, No. 2, December 2024  
**Institusi:** Pradita University  
**Nama File:** `Prediction of Air Quality Index Using Ensemble Models.pdf`

### Fokus Utama
Penelitian ini menggunakan model ensemble untuk memprediksi Air Quality Index (AQI). Pendekatan ensemble menggabungkan beberapa model dasar untuk meningkatkan akurasi dan robustness prediksi.

### Kekuatan
- Menggunakan pendekatan ensemble yang terbukti meningkatkan akurasi prediksi.
- Diterbitkan di jurnal terakreditasi nasional Indonesia (JAIC Polibatam).
- Relevan dengan konteks Indonesia.
- Metodologi ensemble dapat langsung diadopsi.
- Penulis dari institusi Indonesia memudahkan adaptasi konteks.

### Kelemahan
- Tidak spesifik pada kota tertentu di Indonesia.
- Tidak mengintegrasikan data meteorologi sebagai fitur prediktor.
- Tidak membahas karakteristik iklim lokal.
- Tidak membandingkan dengan metode regresi tunggal.

### Relevansi terhadap Judul Penelitian
Relevan dalam konteks penggunaan ensemble model untuk prediksi AQI di Indonesia. Penelitian penulis dapat mengadopsi pendekatan ensemble ini dengan menambahkan variabel meteorologi Kota Bandung.

### Gap Resource
- Tidak ada data meteorologi.
- Tidak ada studi spesifik Kota Bandung.
- Tidak ada perbandingan dengan model regresi konvensional.

### Kesimpulan
Jurnal ini mendukung penggunaan model ensemble dalam prediksi AQI. Penelitian penulis dapat menjadikan ini sebagai salah satu acuan metodologi, khususnya jika ensemble model dipertimbangkan sebagai salah satu pendekatan dalam studi Kota Bandung.

---

<a name="jurnal-19"></a>
## Jurnal 19

**Judul:** Prediksi Kualitas Udara Malang Menggunakan Metode Gradient Boosting Regression  
**Penulis:** M. Rizal Muhaimin, Daffa Mirah Karina, Andreas Bayu Krisna  
**Sumber:** Digital Transformation Technology (Digitech), Vol. 4, No. 2, September 2024  
**Institusi:** Universitas Merdeka Malang  
**DOI:** https://doi.org/10.47709/digitech.v4i2.5046  
**Nama File:** `Prediksi Kualitas Udara Malang Menggunakan Metode Gradient Boosting Regression.pdf`

### Fokus Utama
Penelitian ini menggunakan metode Gradient Boosting Regression untuk memprediksi kualitas udara di Kota Malang. Ini merupakan salah satu sedikit penelitian yang secara spesifik berfokus pada prediksi kualitas udara kota di Jawa dengan metode regresi gradient boosting.

### Kekuatan
- Menggunakan **metode regresi** (Gradient Boosting Regression) yang sangat sesuai dengan tema penelitian penulis.
- Konteks **kota di Jawa** memiliki kemiripan karakteristik dengan Bandung (perkotaan Jawa, pengaruh industri dan transportasi).
- Metodologi yang dapat langsung diadaptasi untuk Kota Bandung.
- Gradient Boosting Regression terbukti efektif untuk data kualitas udara.
- Diterbitkan di jurnal nasional Indonesia yang relevan.

### Kelemahan
- Menggunakan data Kota Malang, bukan Bandung — karakteristik topografi dan iklim berbeda.
- Tidak mengintegrasikan variabel meteorologi secara komprehensif.
- Tidak membandingkan dengan metode regresi lainnya (linear regression, SVR, dll.).
- Tidak ada analisis feature importance variabel meteorologi.
- Tidak membahas pengaruh musim terhadap kualitas udara Malang.

### Relevansi terhadap Judul Penelitian
**Sangat relevan** karena secara langsung menggunakan metode regresi untuk prediksi kualitas udara kota di Indonesia. Penelitian penulis dapat menjadi studi serupa namun untuk Kota Bandung dengan penambahan variabel meteorologi dan perbandingan lebih banyak metode.

### Gap Resource
- Tidak ada studi untuk Kota Bandung.
- Tidak ada data meteorologi komprehensif sebagai prediktor.
- Tidak membandingkan dengan beberapa metode regresi dan ML.
- Tidak membahas pengaruh musim dan iklim lokal.

### Kesimpulan
Jurnal ini merupakan referensi paling langsung untuk penelitian penulis karena menggunakan metode regresi pada konteks kota Indonesia yang serupa. Penelitian penulis dapat memperluas temuan ini dengan: (1) mengaplikasikan pada Kota Bandung, (2) menambahkan data meteorologi, dan (3) membandingkan lebih banyak metode regresi dan ML.

---

<a name="jurnal-20"></a>
## Jurnal 20

**Judul:** Systematic Review of Machine Learning and Deep Learning Techniques for Spatiotemporal Air Quality Prediction  
**Penulis:** Agbehadji, I.E.; Obagbuwa, I.C.  
**Sumber:** Atmosphere (MDPI), 2024  
**Nama File:** `Systematic Review of Machine Learning and Deep Learning Techniques for Spatiotemporal Air Quality Prediction.pdf`

### Fokus Utama
Penelitian ini merupakan systematic review komprehensif tentang teknik ML dan deep learning untuk prediksi kualitas udara spatiotemporal. Penelitian menggunakan metode systematic literature review (SLR) dengan pencarian di berbagai basis data ilmiah.

### Kekuatan
- Sebagai systematic review, memberikan gambaran menyeluruh tentang state-of-the-art dalam bidang ini.
- Mengidentifikasi tren dan pola penelitian dalam ML untuk prediksi kualitas udara.
- Mencakup aspek spatiotemporal yang penting untuk pemodelan distribusi polutan.
- Diterbitkan di MDPI Atmosphere yang terindeks internasional.
- Sangat berguna sebagai referensi tinjauan pustaka.

### Kelemahan
- Sebagai review paper, tidak menghasilkan model prediksi baru.
- Tidak fokus pada satu lokasi atau metode spesifik.
- Tidak membahas secara spesifik penggunaan data meteorologi lokal.
- Tidak memberikan panduan implementasi praktis untuk kasus tertentu.

### Relevansi terhadap Judul Penelitian
Sangat relevan untuk mendukung tinjauan pustaka dan justifikasi metodologi penelitian penulis. Memberikan gambaran komprehensif tentang metode yang telah berhasil digunakan sehingga membantu pemilihan metode yang tepat.

### Gap Resource
- Tidak ada rekomendasi spesifik untuk kota-kota di Indonesia.
- Tidak membahas penggunaan data meteorologi BMKG.
- Tidak ada panduan implementasi untuk kondisi tropis.
- Tidak ada analisis gap penelitian di Asia Tenggara.

### Kesimpulan
Jurnal ini merupakan referensi tinjauan pustaka yang sangat berharga. Penelitian penulis dapat mengutip jurnal ini untuk mendukung argumentasi bahwa ML dan deep learning efektif untuk prediksi kualitas udara, sekaligus mengidentifikasi bahwa belum ada studi yang fokus pada Kota Bandung dengan data meteorologi lokal.

---

<a name="jurnal-21"></a>
## Jurnal 21

**Judul:** Teknik Machine Learning untuk Analisa Klasifikasi Kualitas Udara: A Review  
**Penulis:** Haris Alfian, Sri Wahyuni, Aqil Revalino, M. Fitter Mirano, Elsa Rahmayana, Harun Mukhtar  
**Sumber:** Software Engineering and Information System (SEIS), Vol. 4, No. 2, Agustus 2024  
**Institusi:** Universitas Muhammadiyah Riau  
**Nama File:** `Teknik Machine Learning untuk Analisa Klasifikasi Kualitas Udara - A Review.pdf`

### Fokus Utama
Penelitian ini merupakan review tentang berbagai teknik machine learning yang digunakan untuk analisis dan klasifikasi kualitas udara. Meliputi Decision Trees, SVM, Neural Networks, dan Ensemble Learning dengan evaluasi efektivitas masing-masing dalam mengolah data sensor udara yang kompleks.

### Kekuatan
- Memberikan gambaran komprehensif berbagai teknik ML untuk kualitas udara dalam bahasa Indonesia.
- Membahas tantangan dalam pengumpulan dan preprocessing data sensor.
- Mengidentifikasi tren terbaru dan peluang penelitian masa depan.
- Relevan dengan konteks penelitian Indonesia.
- Sebagai review paper, memberikan justifikasi pemilihan metode.

### Kelemahan
- Sebagai review, tidak menghasilkan model prediksi baru.
- Tidak mengintegrasikan data meteorologi sebagai variabel prediktor.
- Tidak spesifik pada satu lokasi di Indonesia.
- Tidak membahas metode regresi konvensional secara mendalam.
- Hanya mengulas hingga tahun 2024 sehingga mungkin melewatkan perkembangan terbaru.

### Relevansi terhadap Judul Penelitian
Relevan untuk justifikasi pemilihan metode ML dalam penelitian penulis, khususnya karena ditulis dalam bahasa Indonesia dan membahas berbagai teknik yang dapat diaplikasikan. Dapat digunakan dalam tinjauan pustaka.

### Gap Resource
- Tidak ada studi spesifik Kota Bandung.
- Tidak membahas data meteorologi sebagai prediktor.
- Tidak membandingkan ML dengan regresi konvensional.
- Tidak ada rekomendasi metode terbaik untuk kondisi Indonesia.

### Kesimpulan
Jurnal ini berguna sebagai referensi review berbahasa Indonesia untuk pemilihan teknik ML. Penelitian penulis mengisi gap yang diidentifikasi dalam jurnal ini dengan mengaplikasikan secara praktis pada Kota Bandung dengan data meteorologi lokal.

---

<a name="kesimpulan-umum"></a>
## KESIMPULAN UMUM & GAP RESEARCH

### Rangkuman Gap Research dari Seluruh Jurnal

Berdasarkan review terhadap 21 jurnal di atas, terdapat beberapa **gap penelitian yang signifikan** yang menjadi justifikasi dan kontribusi penelitian penulis:

| No | Gap yang Ditemukan | Jurnal yang Mengalami Gap |
|----|--------------------|--------------------------|
| 1 | Tidak ada studi prediksi kualitas udara **spesifik Kota Bandung** menggunakan data meteorologi | Hampir semua jurnal (kecuali Jurnal 17) |
| 2 | Tidak ada integrasi **data meteorologi lokal** (suhu, kelembapan, curah hujan, kecepatan angin) sebagai fitur prediktor utama | 1, 4, 5, 6, 9, 10, 11, 12, 18, 19, 21 |
| 3 | Tidak ada **perbandingan metode regresi konvensional vs ML** secara komprehensif di Indonesia | Semua jurnal |
| 4 | Kurangnya studi pada kota dengan **karakteristik topografi dataran tinggi tropis** | Semua jurnal selain Jurnal 17 |
| 5 | Tidak ada analisis pengaruh **musim hujan dan kemarau** terhadap kualitas udara Bandung | Semua jurnal |
| 6 | Kurangnya studi prediksi kualitas udara berbasis data **BMKG** di Indonesia | Semua jurnal |
| 7 | Tidak ada **analisis feature importance** variabel meteorologi untuk kualitas udara Bandung | Hampir semua jurnal |

### Kontribusi Utama Penelitian Penulis

Berdasarkan gap yang ditemukan, penelitian **"Prediksi Kualitas Udara Menggunakan Metode Regresi dan Machine Learning Berbasis Data Meteorologi Kota Bandung"** memberikan kontribusi unik:

1. **Lokasi Spesifik:** Kota Bandung dengan karakteristik topografi dataran tinggi (±768 mdpl) yang mempengaruhi pola dispersi polutan secara unik.
2. **Data Meteorologi:** Integrasi komprehensif variabel meteorologi (suhu, kelembapan, curah hujan, kecepatan angin, radiasi matahari) dari BMKG sebagai fitur prediktor utama.
3. **Komparatif:** Membandingkan metode regresi konvensional dengan ML modern, memberikan perspektif yang belum banyak dilakukan di Indonesia.
4. **Konteks Lokal:** Menggunakan standar ISPU Indonesia dan data dari instansi resmi Indonesia.
5. **Karakteristik Musiman:** Mempertimbangkan pengaruh musim hujan dan kemarau terhadap kualitas udara Bandung.

### Metode yang Direkomendasikan Berdasarkan Review

Berdasarkan sintesis dari 21 jurnal yang diulas:

| Kategori Metode | Algoritma | Referensi Utama |
|----------------|-----------|-----------------|
| **Regresi Konvensional** | Multiple Linear Regression, Polynomial Regression | Jurnal 11 |
| **Tree-based ML** | Random Forest, XGBoost, LightGBM | Jurnal 5, 13, 16 |
| **Ensemble** | Gradient Boosting Regression, Stacking | Jurnal 2, 18, 19 |
| **Deep Learning (opsional)** | LSTM | Jurnal 1, 17 |

### Rekomendasi untuk Penelitian Penulis

1. **Data Primer:** Gunakan data meteorologi BMKG Stasiun Bandung (suhu, kelembapan, tekanan udara, kecepatan angin, curah hujan) dan data ISPU dari KLHK/BMKG.
2. **Baseline Model:** Terapkan Multiple Linear Regression sebagai baseline untuk perbandingan.
3. **Model Utama:** XGBoost, Random Forest, dan Gradient Boosting Regression sebagai model ML yang dibandingkan.
4. **Evaluasi:** Gunakan RMSE, MAE, MAPE, dan R² untuk evaluasi komprehensif.
5. **Analisis Tambahan:** Lakukan analisis feature importance untuk mengidentifikasi variabel meteorologi paling berpengaruh terhadap kualitas udara Bandung.
6. **Periode Data:** Gunakan data minimal 3-5 tahun untuk menangkap pola musiman.

---

*Review ini disusun berdasarkan analisis mendalam terhadap 21 jurnal ilmiah yang berkaitan dengan prediksi kualitas udara menggunakan machine learning dan metode regresi.*

*Disusun oleh: Vany Salsabila Putri | NIM: 123450022 | 22 Juni 2026*
