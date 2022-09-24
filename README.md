# Jarkom-Modul-1-E03-2022

## Kelompok E03
- Pedro T. Korwa              05111940007003
- Made Rianja Richo Dainino   5025201236
- Syaiful Bahri Dirgantara    5025201203

### 1. Sebutkan web server yang digunakan pada "monta.if.its.ac.id"! 
Jawaban : NGINX
- Memfilter pencarian “monta.if.its.ac.id”
![Gambar 1.a](img/1a.jpg)
- Klik kanan pada salah satu paket kemudian, klik follow TCP stream, maka akan muncul seperti gambar di bawah yang menginformasikan bahwa web servernya merupakan NGINX
![Gambar 1.b](img/1b.jpg)

### 2. Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq ?
Jawaban : Evaluasi unjuk kerja User Space Filesystem (FUSE)
- Filter http request yang berisi “detail”
![Gambar 2.a](img/2a.jpg)
- Terlihat selanjutnya setelah detail topik adalah lanjut ke halaman 194 (juga dari response in frame menuju paket 599), dimana ketika dilihat paket 599 berisi halaman 194 juga, dan ketika di export object halaman 194 berisi file txt/html, kemudian simpan file tersebut
![Gambar 2.b](img/2b.jpg)
- Kemudian buka file tersebut melalui browser maka akan terbuka halaman yang dibuka Ishaq yaitu berisi topik tugas akhir yang berjudul “Evaluasi unjuk kerja User Space Filesystem (FUSE)”
![Gambar 2.c](img/2c.jpg)
