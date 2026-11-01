# Rancangan Test Case (Pertemuan 14)

Test case ini dirancang sebelum implementasi, sebagai definisi "berhasil" dan "gagal" untuk proyek Rekap dan Analisis Nilai. Eksekusi, kolom Actual, dan status dicatat pada Pertemuan 15 (folder `pertemuan-15-implementasi-proyek`).

Kategori: normal, batas, invalid, kosong, file, integrasi, dan campuran. Total 14 test case (syarat minimal: 5).

| ID | Kategori | Input/Kondisi | Expected Result | Status |
|----|----------|---------------|-----------------|--------|
| TC01 | Normal | Nilai 80, 70, 90 | Rata-rata 80.0 | Belum dijalankan |
| TC02 | Batas | Nilai 0 | Diterima sebagai nilai valid | Belum dijalankan |
| TC03 | Batas | Nilai 100 | Diterima sebagai nilai valid | Belum dijalankan |
| TC04 | Invalid | Nilai 105 | Ditolak dengan pesan validasi | Belum dijalankan |
| TC05 | Invalid | File tidak ada | Pesan jelas, program tidak crash | Belum dijalankan |
| TC06 | Normal | Semua nilai >= KKM | Jumlah tuntas = jumlah data | Belum dijalankan |
| TC07 | Batas | Nilai 75 dan 74 (KKM 75) | 75 Tuntas, 74 Belum Tuntas | Belum dijalankan |
| TC08 | Invalid | Nilai teks `abc` | Ditolak, program tidak error | Belum dijalankan |
| TC09 | Kosong | File tanpa data | Pesan jelas, tanpa ZeroDivisionError | Belum dijalankan |
| TC10 | File | Data valid | Laporan tersimpan di file | Belum dijalankan |
| TC11 | Kosong | List kosong ke `hitung_statistik` | Rata-rata 0, min/max None | Belum dijalankan |
| TC12 | Integrasi | Data contoh proyek | Seluruh alur berjalan | Belum dijalankan |
| TC13 | Campuran | Baris valid, teks, kosong, 105 | Hanya baris valid dihitung, kesalahan tercatat | Belum dijalankan |
| TC14 | Invalid | Baris tanpa koma | Ditolak dengan nomor baris | Belum dijalankan |

Definition of Done: semua fitur wajib berjalan, semua test case wajib lulus, error yang sudah diprediksi tidak menghentikan program, output mudah dibaca, README menjelaskan cara menjalankan, commit menunjukkan proses kerja.
