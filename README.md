# PDF Watermark Tool

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-stable-success.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20MacOS-lightgrey.svg)

Alat sederhana untuk menambahkan **watermark teks** atau **watermark gambar** ke dalam file PDF.  
Mendukung **Bahasa Indonesia** dan **Bahasa Inggris**.

---

## ✨ Fitur
- Pilihan watermark **teks** (posisi, ukuran font, rotasi, transparansi bisa diatur).
- Pilihan watermark **gambar** (posisi, ukuran bisa diatur).
- Menu interaktif di terminal.
- Multi-bahasa (English & Bahasa Indonesia).
- Output disimpan sebagai file PDF baru.

---

## 📦 Instalasi

1. Clone atau unduh repository ini:
   ```bash
   git clone https://github.com/username/pdf-watermark-tool.git
   cd pdf-watermark-tool

2. Install dependencies:

pip install -r requirements.txt




---

🚀 Cara Menjalankan

1. Pastikan file watermark2.py ada di folder kerja.


2. Simpan file PDF dan gambar watermark (PNG transparan disarankan) di folder yang sama.


3. Jalankan program:

python watermark2.py


4. Pilih bahasa (English / Bahasa Indonesia).


5. Ikuti menu utama:

1. Text Watermark → Tambahkan teks watermark.

2. Image Watermark → Tambahkan gambar watermark.

3. Exit → Keluar.





---

🖥️ Screenshot Terminal (Simulasi)

========================================
           CHOOSE A LANGUAGE
========================================
1. English
2. Bahasa Indonesia
========================================
Choose a language (1/2): 1

PDF Watermark Tool
========================================
             MAIN MENU
========================================
1. Text Watermark
2. Image Watermark
3. Exit
========================================
Choose an option (1/2/3):

Contoh Input Text Watermark

Enter the input PDF file name: dokumen.pdf
Enter watermark text: CONFIDENTIAL
Font size (default: 60): 80
X position (points, default: 200): 250
Y position (points, default: 400): 500
Rotation (degrees, default: 45): 30
Transparency (0.0-1.0, default: 0.2): 0.3
Enter the output file name (e.g., result.pdf): hasil.pdf
Processing...
Success! The watermarked file is saved at 'hasil.pdf'

Contoh Input Image Watermark

Enter the input PDF file name: dokumen.pdf
Enter the image file name: logo.png
Image width (points, default: 200): 150
Image height (points, default: 200): 150
X position (points, default: 200): 100
Y position (points, default: 400): 100
Enter the output file name (e.g., result.pdf): hasil_logo.pdf
Processing...
Success! The watermarked file is saved at 'hasil_logo.pdf'


---

📂 Struktur Folder

.
├── watermark2.py
├── requirements.txt
└── README.md


---

⚠️ Catatan

Gunakan PNG dengan latar transparan untuk hasil watermark gambar terbaik.

File hasil akan tersimpan di folder yang sama.



---

📜 Lisensi

Proyek ini menggunakan lisensi MIT.

---


