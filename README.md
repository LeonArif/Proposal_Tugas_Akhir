# Tugas_Akhir

Template Laporan Tugas Akhir STI STEI, Institut Teknologi Bandung.

Dokumen utama:
1. ProposalTA.tex (file utama)
2. daftar-pustaka.bib (file daftar pustaka)
3. ta-sti.cls (class file)

Ketiga file ini harus berada di folder yang sama.

## Petunjuk penggunaan

1. Sunting `ProposalTA.tex` sesuai dengan kebutuhan Anda.
2. Sunting atau generate isi `daftar-pustaka.bib` dengan referensi yang Anda gunakan, sesuai dengan format BibLaTeX.
3. Kompilasi file `ProposalTA.tex` menggunakan XeLaTeX dan Biber (lihat urutan cara kompilasi di bawah).
4. Hasil kompilasi adalah file `ProposalTA.pdf` yang siap untuk dicetak.

Eksekusi perintah-perintah berikut untuk melakukan kompilasi melalui command line (cmd atau terminal):

```
xelatex ProposalTA.tex
biber ProposalTA
xelatex ProposalTA.tex
xelatex ProposalTA.tex
```

Jika menggunakan Visual Studio Code sebagai editor dengan ekstensi LaTeX Workshop, konfigurasi build recipe ada di `.vscode/settings.json`.

### Catatan

- Pastikan paket-paket LaTeX yang diperlukan sudah terinstal, termasuk `biblatex-chicago` dan `fontspec`.
- Gunakan editor LaTeX yang mendukung XeLaTeX, seperti VS Code (LaTeX Workshop), TeXstudio, Overleaf, atau TexShop (Mac OS).
