# Template LaTeX untuk Kajian Pustaka Sistem Pendukung Keputusan

Template LaTeX untuk membuat kajian pustaka (literature review) tentang sistem pendukung keputusan untuk bantuan pendidikan. Template ini dirancang khusus untuk menganalisis dua paper penelitian dengan metode yang berbeda: Simple Additive Weighting (SAW) dan Neural Network.

## 📋 Deskripsi

Template ini menyediakan struktur lengkap untuk kajian pustaka akademik dengan format yang sesuai untuk penggunaan di Overleaf. Template dirancang untuk memenuhi standar penulisan akademik dengan font Times New Roman 10pt dan layout satu kolom.

## 📁 Struktur File

```
├── main.tex                    # File utama LaTeX dengan struktur lengkap
├── references.bib              # File bibliografi untuk daftar pustaka
├── template/                   # Template kosong untuk mahasiswa
│   ├── main.tex               # Template kosong yang siap diisi
│   └── references.bib         # Template bibliografi kosong
├── example/                   # Contoh template yang sudah diisi
│   ├── main.tex              # Contoh kajian pustaka lengkap
│   └── references.bib        # Contoh bibliografi lengkap
└── README.md                  # Panduan penggunaan ini
```

## 🎯 Paper yang Direview

Template ini dirancang untuk menganalisis dua paper berikut:
1. **"APLIKASI UNTUK MENCARI KELAYAKAN SISWA PENERIMA BANTUAN PENDIDIKAN DENGAN METODE SIMPLE ADDITIVE WEIGHTING"**
2. **"PERANCANGAN SISTEM PENDUKUNG KEPUTUSAN UNTUK PREDIKSI PENERIMA BEASISWA MENGGUNAKAN METODE NEURAL NETWORK"**

## 📐 Spesifikasi Format

- **Font**: Times New Roman
- **Ukuran Font**: 10pt
- **Layout**: Single column (1 kolom)
- **Spacing**: 1.5x line spacing
- **Margin**: 3cm (semua sisi)
- **Paper Size**: A4
- **Bahasa**: Bahasa Indonesia dengan dukungan untuk istilah teknis dalam bahasa Inggris

## 📖 Struktur Kajian Pustaka

### Untuk Setiap Paper:
1. **Metode yang digunakan** - Penjelasan detail algoritma/metode
2. **Dataset yang digunakan** - Deskripsi data dan preprocessing
3. **Hasil eksperimen dan analisis** - Ringkasan hasil dan evaluasi
4. **Kelebihan dan kekurangan** - Analisis kritis penelitian
5. **Referensi yang digunakan** - Evaluasi kualitas referensi

### Struktur Dokumen Lengkap:
- Title page dengan informasi mahasiswa
- Table of contents
- Pendahuluan kajian pustaka
- Section terpisah untuk Paper 1 (SAW)
- Section terpisah untuk Paper 2 (Neural Network)
- Analisis komparatif kedua metode
- Kesimpulan dan rekomendasi
- Bibliography/daftar pustaka

## 🚀 Cara Penggunaan

### Opsi 1: Menggunakan Template Kosong (Untuk Mahasiswa)

1. **Download template kosong:**
   ```
   template/main.tex
   template/references.bib
   ```

2. **Upload ke Overleaf:**
   - Buat project baru di Overleaf
   - Upload kedua file template
   - Set main document sebagai `main.tex`

3. **Kustomisasi informasi pribadi:**
   - Edit bagian author dengan nama, NIM, program studi, dll.
   - Update title jika diperlukan

4. **Isi konten:**
   - Ganti semua bagian `% TODO:` dengan konten Anda
   - Lengkapi analisis untuk setiap paper
   - Update file `references.bib` dengan referensi aktual

### Opsi 2: Menggunakan Contoh Lengkap (Untuk Referensi)

1. **Download contoh lengkap:**
   ```
   example/main.tex
   example/references.bib
   ```

2. **Gunakan sebagai referensi** untuk memahami struktur dan format yang diharapkan

3. **Adaptasi konten** sesuai dengan paper yang Anda analisis

### Opsi 3: Menggunakan Template Utama

1. **Download file utama:**
   ```
   main.tex
   references.bib
   ```

2. **File ini berisi struktur lengkap** dengan placeholder content yang dapat Anda modifikasi

## 🔧 Konfigurasi di Overleaf

### Langkah-langkah Setup:

1. **Buat Project Baru**
   - Login ke Overleaf
   - Klik "New Project" → "Blank Project"

2. **Upload Files**
   - Upload `main.tex` dan `references.bib`
   - Pastikan `main.tex` diset sebagai main document

3. **Compile Settings**
   - Compiler: pdfLaTeX
   - TeX Live version: 2023 atau terbaru
   - Main document: main.tex

4. **Packages yang Diperlukan**
   Semua packages sudah termasuk dalam template:
   - `mathptmx` (Times New Roman font)
   - `babel` (Indonesian language support)
   - `geometry` (page layout)
   - `hyperref` (links and bookmarks)
   - `cite` (citation management)

## 📚 Panduan Penulisan

### Tips Menulis Kajian Pustaka:

1. **Analisis Mendalam**
   - Jangan hanya merangkum, berikan analisis kritis
   - Bandingkan kedua metode secara objektif
   - Identifikasi gap dan peluang penelitian

2. **Sitasi yang Tepat**
   - Gunakan format `\cite{key}` untuk sitasi
   - Pastikan semua referensi ada di file `.bib`
   - Gunakan sitasi untuk mendukung argumen

3. **Struktur yang Jelas**
   - Gunakan heading dan subheading dengan konsisten
   - Buat transisi yang smooth antar section
   - Gunakan bullet points untuk daftar

4. **Bahasa Akademik**
   - Gunakan bahasa formal dan objektif
   - Hindari bahasa yang terlalu casual
   - Perhatikan grammar dan spelling

### Format Tambahan:

```latex
% Untuk menambahkan gambar
\begin{figure}[h]
\centering
\includegraphics[width=0.8\textwidth]{nama_file.png}
\caption{Caption gambar}
\label{fig:label}
\end{figure}

% Untuk menambahkan tabel
\begin{table}[h]
\centering
\caption{Caption tabel}
\label{tab:label}
\begin{tabular}{|c|c|c|}
\hline
Kolom 1 & Kolom 2 & Kolom 3 \\
\hline
Data 1 & Data 2 & Data 3 \\
\hline
\end{tabular}
\end{table}

% Untuk persamaan matematika
\begin{equation}
E = mc^2
\label{eq:einstein}
\end{equation}
```

## 📋 Checklist Sebelum Submit

- [ ] Informasi mahasiswa sudah diupdate
- [ ] Semua section TODO sudah diisi
- [ ] Referensi di file .bib sudah lengkap dan akurat
- [ ] Dokumen bisa dikompilasi tanpa error
- [ ] Format sesuai dengan requirement (Times New Roman 10pt)
- [ ] Minimal 1 halaman per paper (tidak termasuk referensi)
- [ ] Analisis komparatif sudah lengkap
- [ ] Bibliography ter-generate dengan benar

## 🔍 Troubleshooting

### Error Kompilasi Umum:

1. **Package not found**
   - Pastikan menggunakan TeX Live 2023 atau terbaru
   - Coba compile ulang beberapa kali

2. **Bibliography tidak muncul**
   - Pastikan ada sitasi `\cite{}` dalam dokumen
   - Compile: LaTeX → BibTeX → LaTeX → LaTeX

3. **Font tidak sesuai**
   - Pastikan package `mathptmx` dimuat dengan benar
   - Cek console output untuk error font

4. **Layout bermasalah**
   - Periksa package `geometry` sudah dimuat
   - Pastikan tidak ada conflict dengan package lain

## 📞 Support

Jika mengalami masalah atau memiliki pertanyaan:

1. **Check Overleaf Documentation** untuk issue teknis LaTeX
2. **Review template example** untuk referensi format
3. **Konsultasi dengan dosen pembimbing** untuk konten akademik

## 📄 Lisensi

Template ini dapat digunakan secara bebas untuk keperluan akademik. Mohon cantumkan credit jika menggunakan template ini sebagai basis untuk template lain.

---

**Selamat menulis kajian pustaka! 📖✨**

> Template ini dirancang untuk membantu mahasiswa membuat kajian pustaka yang berkualitas dengan format profesional. Gunakan sebagai panduan dan sesuaikan dengan kebutuhan spesifik tugas Anda.