# evlfctry.pro

a simple URL shortener that doesn't try to do too much. also, serverless

## Motivasi

Sebelumnya kita menggunakan [gow](https://evlfctry.pro/gow) untuk membuat URL
shortener yang mana dibuat menggunakan Go & Reason serta SQLite sebagai basis data.

Karena terjadi musibah terkait Docker, semua data yang ada di Docker Volume hilang
ditelan Inode. Dibuatnya project ini adalah agar:

- Menghindari musibah tersebut terjadi lagi
- Membuat proses pembuatan "short url" menjadi relatif lebih mudah & transparan
- Dah

Project ini digunakan oleh internal evilfactorylabs untuk membuat "short url" agar
mempermudah audiens evilfactorylabs mengakses tautan yang anggota evilfactorylabs
buat (dan juga cocok untuk mengarahkan ke tautan affiliate :p)

## Prasyarat

- Bash ~> 3.2
- Node.js ~> 14.16
- NPM ~> 6.14
- OpenSSL ~> 1.1 (Opsional)

## Cara menggunakan

- Clone repository ini
- Jalankan `./generate` untuk menampilkan cara penggunaan

## Dokumentasi

Seharusnya sudah cukup jelas :)

## Menjalankan test

Tidak ada. YOLO.

## Menjalankan di production

Cukup push repository ini di GitHub, sesuaikan konten yang ada di direktori `links`,
sesuaikan konten yang ada di `.github/workflows/eleventy.yml` khususnya dibagian `cname`, profit.

## Cara berkontribusi

Berkontribusilah ke project lain yang lebih bermanfaat!

## Terima kasih

Project ini dibuat menggunakan [Eleventy](https://www.11ty.dev) dan ditenagai oleh
[GitHub Actions](https://github.com/features/actions).

## Pemelihara

- [fariz, evilfactorylabs](https://github.com/faultable)

## Lisensi

Project ini dirilis menggunakan [lisensi MIT](./LICENSE).
