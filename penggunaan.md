Di halaman ini akan menjelaskan penggunaan format-tesis

Daftar isi:
- [_Table of Content_ (TOC)](#_table-of-content_-toc)
- [_Caption_](#_caption_)

-----

## _Table of Content_ (TOC)

Langkah untuk membangkitkan TOC: 
- Buka `References > Table of Contents > Custom Table of Contents...` melalui menu _Ribbon_.
- Buka pilihan `Options...`
- Pastikan mengikuti konfigurasi TOC Levels.

### Konfigurasi TOC Levels

**Daftar isi**

Styles | TOC level
:-- | :-:
`.toc-Judul` | 1
`.toc-Judul.1.5` | 1
`.toc-Judul.hidden` | 1
`.toc-Judul.italic` | 1
`Heading 1` | 1
`Heading 2` | 2
`Heading 3` | 3

**Daftar Lampiran**

Styles | TOC level
:-- | :-:
`.toc-lampiran` | 8
`.toc-lampiran-sub` | 9

**Daftar Gambar**

Styles | TOC level
:-- | :-:
`.gambar-judul` | 8
`.gambar-judul.panjang` | 8

**Daftar Tabel**

Styles | TOC level
:-- | :-:
`.tabel-judul` | 8
`.tabel-judul.panjang` | 8

-----

## _Caption_

Sebelum memasukkan _caption_, harus ditambah label yang dibutuhkan (label persamaan, tabel, gambar):
- `References` > `Insert Caption`
- Buat tiga label baru yaitu **Gambar**, **Tabel**, **Persamaan** melalui pilihan `New Label...`
- Pada pengaturan `Numbering...` ubah Format menjadi `I, II, III, ...` dan centang pilihan `Include chapter number`.
- Untuk label Persamaan, pastikan memilih `Exclude label from caption`.

Untuk menambah label pada dokumen:
- `References` > `Insert Caption`
- Pilih label yang ingin ditambahkan lalu klik `OK`.
- Beri ruang antara label dan judul label dengan `TAB`. Contoh: "Gambar IV-1`TAB`Judul gambar ini adalah sekian"
- Ubah _styles_ sesuai labelnya

Label | Styles | Deskripsi
:-: | :- | :-
Gambar | `.gambar-judul` | Untuk judul satu baris
. | `.gambar-judul.panjang` | Untuk judul lebih dari satu baris
Tabel | `.tabel-judul` | Untuk judul satu baris
. | `.tabel-judul.panjang` | Untuk judul lebih dari satu baris
Persamaan | `.eq-nomor` | -