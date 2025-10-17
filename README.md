# Audio-Exercise IF-4021 Multimedia Information Processing
Rayhan Fatih Gunawan
NIM.122140134



## Lingkungan Pengembangan
- Python 3.11.X
- Visual Studio Code dengan ekstensi Jupyter Notebook
- Windows (direkomendasikan, karena dikembangkan di Windows)

## Library yang Dibutuhkan
Berikut adalah library Python yang diperlukan untuk menjalankan project ini:
- numpy: Untuk operasi matematika 
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
- Sound yang berada di repository hanya merupakan bahan dasar untuk menjalankan semua code cell, dari menjalankan code cell dihasilkan audio hasil pemrosesannya. 
- Mungkin jika dijalankan dua kali ada beberapa duplikasi

## Deskripsi Soal
Project ini terdiri dari 5 soal utama:
1. Rekaman dan analisis suara multi-level
2. Noise reduction dengan filtering
3. Pitch shifting dan audio manipulation
4. Audio processing chain
5. Music analysis dan remix



