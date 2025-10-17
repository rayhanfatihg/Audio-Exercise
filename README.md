# Audio-Exercise

Tugas Pemrosesan Audio untuk mata kuliah Pemrosesan Informasi Multimedia (IF-4021)

## Lingkungan Pengembangan
- Python 3.x
- Visual Studio Code dengan ekstensi Jupyter Notebook
- Windows (direkomendasikan, karena dikembangkan di Windows)

## Library yang Dibutuhkan
Berikut adalah library Python yang diperlukan untuk menjalankan project ini:
- numpy: Untuk operasi matematika dan array
- librosa: Untuk pemrosesan dan analisis audio
- matplotlib: Untuk visualisasi data
- soundfile: Untuk membaca dan menulis file audio
- pyloudnorm: Untuk normalisasi loudness
- scipy: Untuk pemrosesan sinyal

Anda dapat menginstal semua library yang diperlukan dengan menjalankan:
```bash
pip install numpy librosa matplotlib soundfile pyloudnorm scipy
```

## Struktur Project
```
Audio-Exercise/
│
├── main.ipynb           # File notebook utama berisi semua kode dan analisis
├── README.md           # Dokumentasi project
│
└── WAV/               # Folder berisi file audio
    ├── Berita.wav     # File rekaman untuk soal 1
    ├── noise.wav      # File rekaman untuk soal 2
    ├── SadSong.wav    # File musik untuk soal 5
    └── FunSong.wav    # File musik untuk soal 5
```

## Cara Menjalankan Project
1. Pastikan semua library yang diperlukan sudah terinstal
2. Buka Visual Studio Code
3. Install ekstensi Jupyter Notebook jika belum ada
4. Buka file `main.ipynb`
5. Pastikan semua file audio (.wav) sudah ada di folder WAV
6. Jalankan setiap sel kode secara berurutan dari atas ke bawah
   - Gunakan tombol "Run Cell" (▶️) untuk menjalankan setiap sel
   - Atau gunakan shortcut Shift+Enter

## Catatan Penting
- Pastikan struktur folder dan nama file sesuai dengan yang disebutkan di atas
- Jika menggunakan sistem operasi selain Windows, mungkin perlu menyesuaikan path separator dalam kode
- Rekaman audio harus dalam format WAV
- Pastikan Python dan pip sudah terinstal di sistem Anda

## Deskripsi Soal
Project ini terdiri dari 5 soal utama:
1. Rekaman dan analisis suara multi-level
2. Noise reduction dengan filtering
3. Pitch shifting dan audio manipulation
4. Audio processing chain
5. Music analysis dan remix

Setiap soal memiliki instruksi dan requirement spesifik yang dijelaskan dalam notebook.

