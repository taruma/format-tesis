Dalam tulisan ini akan menjelaskan daftar _styles_ yang telah diubah/dimodifikasi. 

**Catatan:**
- Penamaan styles yang telah dimodifikasi memiliki _prefix_ tanda titik diikuti nama _styles_. Contoh: `.NAMA-STYLES`.
- Penggunaan garis bawah setelah tanda titik menandakan bahwa _styles_ tidak disarankan digunakan, dan hanya digunakan sebagai pengisi baris kosong atau penyesuaian tampilan. Contoh: `._blank-1`.
- Pengembangan/modifikasi dilakukan pada Microsoft Word dengan Office 365 Personal.

## Core Styles

_Core Styles_ merupakan _styles_ paling penting dikarenakan _styles_ ini digunakan sebagai acuan untuk pengembangan _styles_ lainnya. _Core styles_ terdiri dari `._standard` dan `Normal`. `._standard` merupakan _custom styles_ yang dibuat, sedangkan `Normal` merupakan _built-in styles_. Kedua _styles_ ini memiliki atribut/paragraf:
- Font: Times New Roman
- Font size: 12pt
- Line spacing: Single
- Align: Left

Untuk pengembangan _styles_ lainnya, akan mengacu pada `._standard`.

Catatan:
- Hindari penggunaan `._standard` pada umumnya. `._standard` dibuat hanya sebagai alternatif dari _built-in styles_ `Normal`. Selalu gunakan _styles_ yang sesuai dengan teks/bagian.

## Preparation Styles

_Preparation Styles_ merupakan kumpulan _styles_ yang **hanya digunakan** pada bagian persiapan dokumen (cover, pengesahan, abstrak, dll). Penulisan nama _styles_ ini selalu diawali dengan `.prep-NAMASTYLES`. 

Berikut daftar _styles_ yang termasuk dalam kategori ini:

Styles | Deskripsi
:- | :-
`.prep-abstrak` | Bagian Abstrak
`.prep-abstrak.italic` | Abstrak dengan huruf miring
`.prep-Judul` | Bagian Judul
`.prep-Judul.italic` | Judul dengan huruf miring
`.prep-normal` | paragraf berdasarkan `._standard`
`.prep-normal.bold` | paragraf dengan huruf tebal
`.prep-normal.bold.italic` | paragraf dengan huruf tebal dan miring

Catatan:
- _styles_ `.prep-Judul` tidak akan diikut sertakan dalam pembuatan daftar isi / _Table of Content_
- _styles_ berdasarkan format `._standard`

## Content Styles

_Content Styles_ merupakan kumpulan _styles_ yang digunakan di dalam tubuh utama dokumen, hal ini memisahkan dari _Preparation Styles_.

Penggunaan pada | Styles | Deskripsi
:- | :- | :-
Paragraf | `.paragraf` | Paragraf
Paragraf | `.paragraf.hanging` | Paragraf dengan _hanging_ dan 1 spasi
Paragraf | `.paragraf.italic` | Paragraf dengan huruf miring
Paragraf | `.paragraf-list` | Paragraf untuk daftar/_list_
BAB | `Heading 1` | Judul BAB
sub-BAB | `Heading 2` | Judul anak BAB
sub-sub-BAB | `Heading 3` | Judul anak sub-BAB
sub-4-BAB | `Heading 4` | Judul anak sub-sub-BAB
Gambar | `.img` | Membuat gambar jadi _centered_
Gambar | `.gambar-judul` | Baris judul gambar
Gambar | `.gambar-judul.panjang` | Baris judul gambar yang panjang
Persamaan | `.eq-isi` | Baris persamaan
Persamaan | `.eq-nomor` | Penomoran persamaan
Tabel | `.tabel-isi` | Isian tabel
Tabel | `.tabel-judul` | Baris judul tabel
Tabel | `.tabel-judul.panjang` | Baris judul tabel yang panjang

Catatan:
- Penggunaan _built-in styles_ untuk bab/sub-bab seperti `Heading 1` agar memudahkan dalam menambahkan keterangan/_caption_ untuk gambar, persamaan, dan tabel.
- Untuk `.paragraf-hanging` menggunakan hanging 1.25 cm. Pada panduan, ditulis 7 ketuk yang sulit saya interpretasikan. Pada contoh dokumen, besarnya _hanging_ sebesar 1.27 cm (atau 0.5 inci).

## TOC Styles

_Table of Content/TOC Styles_ merupakan kumpulan _styles_ yang digunakan untuk menyertakan _styles_ tersebut dalam daftar isi. Penggunaan _styles_ ini biasanya hanya digunakan pada bagian persiapan dan bagian akhir dikarenakan untuk tubuh utama dokumen menggunakan `Heading`.

Styles | Deskripsi
:- | :-
`.toc-Judul` | Judul dengan 1 spasi
`.toc-Judul.1.5` | Judul dengan 1.5 spasi
`.toc-Judul.italic` | Judul dengan huruf miring
`.toc-lampiran` | BAB lampiran
`.toc-lampiran-sub` | Sub-bab lampiran
