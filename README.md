Tentu! Berikut adalah versi yang telah diparafrase:

# Tugas-CF-Fuzzy_Logic

## Certainty Factor (CF)

Certainty Factor adalah metode yang digunakan dalam sistem pakar untuk menangani **ketidakpastian**. Konsep ini mengukur tingkat keyakinan terhadap suatu kesimpulan berdasarkan gejala yang diamati.

Nilai CF berada dalam kisaran -1 hingga +1:
- `+1` : sangat yakin bahwa pernyataan **benar**  
- `0` : **netral** atau belum memiliki kepastian  
- `-1` : sangat yakin bahwa pernyataan **salah**

🔍 Dalam studi kasus ini, sistem pakar digunakan untuk **mendiagnosis suatu penyakit** berdasarkan gejala yang dimasukkan oleh pengguna. Sistem kemudian memberikan hasil diagnosis **beserta tingkat kepercayaannya**.

---

## Fuzzy Logic

Fuzzy Logic adalah pendekatan logika yang dirancang untuk menangani **ambiguitas dan ketidakpastian**, terutama ketika data tidak dapat dikategorikan secara mutlak sebagai benar (1) atau salah (0). Dalam fuzzy logic, **derajat keanggotaan** digunakan untuk menyatakan tingkat kebenaran suatu kondisi, dengan rentang nilai antara 0 dan 1.

### Komponen utama dalam Fuzzy Logic:
- **Fuzzy Set**: Kumpulan nilai yang tidak pasti (contoh: *suhu tinggi*, *kelembaban sedang*)
- **Membership Function**: Menentukan seberapa jauh suatu nilai masuk ke dalam kategori tertentu  
- **Fuzzification**: Mengubah data numerik menjadi bentuk fuzzy  
- **Inference (Aturan IF-THEN)**: Menyusun aksi berdasarkan kombinasi kondisi fuzzy  
- **Defuzzification**: Mengubah hasil fuzzy menjadi nilai numerik yang pasti  

📌 Dalam studi kasus ini, sistem fuzzy digunakan untuk **mengontrol kecepatan kipas** berdasarkan suhu 🌡️ dan tingkat kelembaban 💧. Aturan fuzzy yang telah dirancang memungkinkan sistem bekerja secara **dinamis dan adaptif terhadap perubahan lingkungan**.

Semoga ini membantu! Jika ada bagian yang ingin disesuaikan lagi, beri tahu saya. 😊
