# Program Rekap dan Analisis Nilai Matematika Kelas

Proyek akhir mata kuliah Algoritma dan Pemrograman, S1 Pendidikan Matematika FKIP Universitas Sultan Ageng Tirtayasa, 2026/2027 Ganjil.

Status: **tahap perancangan (Pertemuan 14)**. Kode program diimplementasikan pada Pertemuan 15.

## Deskripsi

Program console berbasis Python untuk guru matematika: membaca data nilai dari file teks, memvalidasi isinya, menghitung statistik kelas, menentukan status ketuntasan berdasarkan KKM, dan menyimpan laporan. Rincian masalah, kebutuhan, IPO, dan algoritma ada di [proposal.md](proposal.md).

## Fitur Wajib (rencana)

- Membaca file nilai berformat `nama,nilai`.
- Memvalidasi nilai 0-100.
- Menghitung rata-rata, minimum, maksimum.
- Menentukan status Tuntas/Belum Tuntas berdasarkan KKM.
- Menyimpan laporan ke file teks.

## Persyaratan

- Python 3.x

## Cara Menjalankan

Belum tersedia; program dibuat pada Pertemuan 15.

## Struktur Folder (rencana)

```
proyek-akhir-rekap-nilai/
|-- README.md
|-- proposal.md
|-- .gitignore
|-- data/nilai_contoh.txt
|-- src/            (main.py, data_io.py, analisis.py, utilitas.py)
|-- tests/test_case.md
`-- output/
```

## Test Case

14 test case sudah dirancang di [tests/test_case.md](tests/test_case.md). Status eksekusi: belum dijalankan.

## Anggota dan Kontribusi

| Nama | NIM | Kontribusi |
|------|-----|-----------|
| Rasyad Fazri Mulyono | 2225250023 | Seluruh peran (koordinator, programmer, tester, dokumentasi) |

## Referensi/Bantuan

- Bahan Ajar Algoritma dan Pemrograman Pertemuan 14 (Dr. Aan Hendrayana, S.Si., M.Pd.).
- Bantuan AI (Claude, Anthropic): menyusun kerangka proposal dan test case; isi telah ditinjau oleh penyusun.
