# Coffee Harvest AI

Sistem hybrid YOLOv11 dan XGBoost untuk mendeteksi kematangan buah kopi Arabika dari foto dan memperkirakan waktu panen. Bagian dari tesis magister.

## Kegunaan

- Mendeteksi tingkat kematangan buah kopi dari citra kamera ponsel.
- Memodelkan distribusi kematangan pada satu pohon.
- Memperkirakan waktu panen optimal.

## Tech stack

| Lapis | Teknologi |
|---|---|
| Deteksi | YOLOv11n |
| Prediksi | XGBoost |
| Backend | FastAPI |
| Pelatihan | Python, Jupyter, Google Colab |
| Infrastruktur | Docker Compose, Nginx |

## Alur singkat

1. Foto buah kopi diambil dari ponsel.
2. Model deteksi menandai buah dan kelas kematangannya.
3. Distribusi kematangan dihitung per pohon.
4. Model regresi memperkirakan waktu panen optimal.

## Ringkasan

| | |
|---|---|
| Konteks | Tesis Magister Teknik Informatika, 2026 |
| Status | Penelitian selesai, prototipe jalan |

> Kode sumber tidak dipublikasikan. Repo ini hanya menjelaskan kegunaan, stack, dan alur kerja. Tidak ada data pengguna, data pasien, atau kredensial di sini.
