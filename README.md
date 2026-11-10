# Dataset Narkotika dan Psikotropika PN Bogor

Repositori untuk Tugas 2 mata kuliah Temu Kembali Informasi. Dataset ini disiapkan untuk latihan pengumpulan dokumen putusan dan penyusunan ringkasan terstruktur.

**Penyusun** Muhammad Hilman Al Hazmi · NIM berakhiran **229**  
**Cakupan** Lima putusan tingkat pertama dari Pengadilan Negeri Bogor, tahun putus 2024–2025.

## Sumber dan cara pengumpulan

PDF diunduh secara manual dari klasifikasi **Pidana Khusus → Narkotika dan Psikotropika**. Bagian **Mengadili** menjadi dasar ringkasan barang bukti dan amar. [Direktori Putusan Mahkamah Agung RI untuk PN Bogor](https://putusan3.mahkamahagung.go.id/direktori/index/pengadilan/pn-bogor/kategori/narkotika-dan-psikotropika-1.html)

## Daftar dokumen

| No | Nomor putusan | Tanggal putus | Halaman amar di PDF | Nama berkas di dalam ZIP |
| ---: | --- | --- | --- | --- |
| 1 | [222/Pid.Sus/2024/PN Bgr](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0b31f2546edaa822a313732343339.html) | 13 Agustus 2024 | 27–28 | `222_Pid.Sus_2024_PN_Bgr.pdf` |
| 2 | [238/Pid.Sus/2024/PN Bgr](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0b31f0370fe28b7d3313732333433.html) | 19 Agustus 2024 | 32–33 | `238_Pid.Sus_2024_PN_Bgr.pdf` |
| 3 | [281/Pid.Sus/2025/PN Bgr](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0b48c4cc96a2e8b3d313235383332.html) | 28 Oktober 2025 | 17–18 | `281_Pid.Sus_2025_PN_Bgr.pdf` |
| 4 | [294/Pid.Sus/2025/PN Bgr](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0b48c5308373abca0313235383432.html) | 28 Oktober 2025 | 50–51 | `294_Pid.Sus_2025_PN_Bgr.pdf` |
| 5 | [295/Pid.Sus/2025/PN Bgr](https://putusan3.mahkamahagung.go.id/direktori/putusan/zaf0b48c517af0eca632313235383430.html) | 28 Oktober 2025 | 37–38 | `295_Pid.Sus_2025_PN_Bgr.pdf` |

## Struktur berkas

```text
Dataset-Narkotika_229/
├── Dataset/
│   └── Narkotika.zip
├── Overview/
│   └── Overview.xlsx
└── README.md
```

| Berkas | Isi |
| --- | --- |
| `Dataset/Narkotika.zip` | Lima PDF dari Direktori Putusan. Nama berkas diseragamkan. Isi setiap PDF identik dengan hasil unduhan. |
| `Overview/Overview.xlsx` | Ringkasan untuk lima putusan, satu baris per PDF. |
| `README.md` | Kriteria, cara pengumpulan, struktur, dan cara membaca dataset. |

## Kolom pada `Overview.xlsx`

| Kolom | Isi |
| --- | --- |
| `No` | Urutan baris dari 1 sampai 5. |
| `No Putusan` | Nomor putusan seperti tertulis dalam PDF. |
| `Lembaga Peradilan` | Pengadilan Negeri Bogor. |
| `Barang Bukti` | Jenis, jumlah, berat atau ukuran jika tercantum, dan penetapan terhadap barang bukti. |
| `Amar Putusan` | Pokok bagian *Mengadili*, termasuk pidana, denda, penetapan, dan biaya perkara jika tercantum. |

## Cara memakai dataset

Ekstrak [Narkotika.zip](Dataset/Narkotika.zip), lalu buka [Overview.xlsx](Overview/Overview.xlsx). Gunakan `No Putusan` untuk mencocokkan baris dengan dokumen asli. Rujuk halaman amar pada tabel untuk memeriksa redaksi lengkap.
