> **FARHAN DWI PRAMANA**
>
> 3C / 04
>
> 2141720125

# SETUP DATABASE dan FECTHING DATA di NEXTJS

### Praktikum 1: Setup Database

#### Soal 1 : Jelaskan apa yang telah Anda pelajari?

![alt text](docs/prak1-soal1.png)

Memanfaatkan vercel untuk mendeploy sebuah proyek yang ada pada repository yang hanya dipilih saja untuk dilakukan deploy.

#### Soal 2 : Jelaskan apa yang telah Anda pelajari?

![alt text](docs/prak1-soal2.png)

Fitur lain dari vercel yaitu berupa pembuatan database, di praktikum ini contoh pembuatan database menggunakan Postgre dari vercel. Untuk mengakses database postgre dari vercel ini diperlukan atau harus membuat file .env yang isinya berupa kode-kode rahasia yang berupa API dan harus dibuat di file .gitignore agar kode rahasia tersebut tidak ikut terpush ke github

#### Soal 3 : Jelaskan apa yang telah Anda pelajari?

![alt text](docs/prak1-soal3.png)

Mencoba menginputkan sebuah data dan tabel ke dalam database yang telah dibuat melalui file seed.js, selain itu mencoba untuk menentukan dat aapa saja yan akan diinputkan ditiap tabel yang akan dibuat di file data.js

#### Soal 4 : Jelaskan apa yang telah Anda pelajari ? Cobalah eksekusi query SQL yang lain sesuai kreasi Anda, capture hasilnya dan jelaskan!

![alt text](docs/prak1-soal4.png)

Query SQL tersebut mengambil nilai amount dan name dari tabel invoices dan customers secara bersamaan berdasarkan kondisi invoices.amount = 666. Ini dilakukan dengan menggabungkan data dari kedua tabel menggunakan kolom customer_id dan id yang sesuai.

![alt text](docs/prak1-soal4.png)

Sama seperti query sebelumnya hanya saja kondisinya berbeda yaitu dimana data ditampilkan yang hanya memiliki amount diatas 10000

### Praktikum 2: Fetching Data (API)

#### Soal 5 :

![alt text](docs/prak2-soal5.png)

[link](http://localhost:3000/)

Pertama, mendefinisikan struktur data melalui model untuk setiap tabel. Kemudian, menggunakan model query untuk mengakses data dari database dan memprosesnya sebelum ditampilkan di laman. Selanjutnya, membuat komponen dan laman yang diperlukan, tetapi tunda tampilan data sampai laman dapat dijalankan untuk mencegah error. Setelah komponen selesai, perbarui halaman utama (page.tsx) agar dapat menampilkan komponen yang telah dibuat saat server dijalankan.
