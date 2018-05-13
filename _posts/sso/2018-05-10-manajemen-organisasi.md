---
date: 2018-05-10
title: Manajemen organisasi
description: Manajemen Organisasi Perangkat Daerah dalam SSO
categories:
  - sso
type: Document
---


## Halaman Organization Structure

 [![Halaman Organization Structure](/images/sso/manajemen-organisasi/sso_halaman-struktur-organisasi.png)](/images/sso/manajemen-organisasi/sso_halaman-struktur-organisasi.png)

Halaman ini berfungsi untuk menampilkan struktur organisasi pemerintahan yang ada di Provinsi Banten. Pada halaman ini administrator dapat menambahkan, melihat, merubah, dan menghapus data struktur organisasi yang terdapat di Pemerintahan. 

 [![Struktur Hirarki](/images/sso/manajemen-organisasi/sso_struktur-hirarki-organisasi.png)](/images/sso/manajemen-organisasi/sso_struktur-hirarki-organisasi.png)

Gambar di atas merupakan struktur hirarki organisasi pemerintahan yang ada di Provinsi Banten sesuai dengan level-nya. Setiap unit kerja memiliki level yang berbeda sesuai kewenangannya, dan juga setiap unit kerja membawahi unit kerja yang levelnya berada di bawahnya. Setiap unit kerja memiliki kode dan identifier (UUID) yang berbeda-beda.

 [![Data Struktur Hirarki](/images/sso/manajemen-organisasi/sso_data-struktur-hirarki-organisasi.png)](/images/sso/manajemen-organisasi/sso_data-struktur-hirarki-organisasi.png)

Gambar di atas merupakan tampilan dari data struktur hirarki, di menu ini terdapat data dari hirarki yang dipilih baik itu nama unit kerja, identifier, identitas kepala unit kerja dan juga bawahannya. Untuk melihat data struktur hirarki kita harus mengklik folder hirarki dari unit kerja yang ingin dilihat. Berikut ini merupakan gambar detail unit kerja yang dipilih:

 [![Data Struktur Hirarki](/images/sso/manajemen-organisasi/sso_struktur-hirarki-organisasi-full.png)](/images/sso/manajemen-organisasi/sso_struktur-hirarki-organisasi-full.png)

## Menambah Unit Kerja baru

Untuk menambahkan unit kerja baru pada struktur hirarki maka kita harus memilih terlebih dahulu struktur hirarki yang ingin ditambahkan unit kerjanya, data unit kerja bisa dilihat di halaman [ini](https://opd-01.dev.bantenprov.go.id/laravel-opd). Misalnya kita ingin menambah unit kerja baru yang memiliki level 1 yaitu **Sekretariat DPRD**, maka kita harus mengklik folder **Pemprov Banten** pada struktur hirarki karena unit kerja level 1 harus berada di dalam folder **Pemrov Banten**, lalu kita klik icon setting di menu data hirarki seperti pada gambar dan pilih **Add org. unit** . 

 [![Tambah Unit Kerja ](/images/sso/manajemen-organisasi/sso_tambah-data-unit-kerja.png)](/images/sso/manajemen-organisasi/sso_tambah-data-unit-kerja.png)
 
Maka akan muncul halaman untuk menambah unit kerja baru seperti gambar di bawah ini:

 [![Tambah Unit Kerja Baru ](/images/sso/manajemen-organisasi/sso_tambah-unit-kerja-baru.png)](/images/sso/manajemen-organisasi/sso_tambah-unit-kerja-baru.png)
 
Pada halaman ini kita hanya akan mengisi 4 field saja yaitu: 
 1. Name: Field ini diisi dengan nama unit kerja dan semuanya huruf kecil, misalkan **sekretariatdprd**.
 2. Display Name: Field ini diisi dengan nama resmi dari unit kerja yang ingin di tambahkan, misalkan **Sekretariat DPRD**.
 3. Identifier: Field ini diisi dengan UUID dari unit kerja yang ingin di tambahkan, misalkan **7CCC311C-514E-4D45-AB09-BE48D7AF9F7C**.
 4. Cost Center: Field ini diisi dengan kode dari unit kerja yang ingin di tambahkan, misalkan **000200000000000**.

Berikut ini merupakan gambar form yang sudah terisi:

 [![Form Terisi ](/images/sso/manajemen-organisasi/sso_form-tambah-unit-kerja-terisi.png)](/images/sso/manajemen-organisasi/sso_form-tambah-unit-kerja-terisi.png)

Jika Sudah tersisi maka langkah selanjutnya menekan tombol save yang terdapat di bagian bawah halaman seperti gambar di bawah ini:

[![Tombol Save ](/images/sso/manajemen-organisasi/sso_tombol-save.png)](/images/sso/manajemen-organisasi/sso_tombol-save.png)

Setelah menekan tombol save maka unit kerja baru akan muncul di struktur hirarki, pada contoh ini yaitu unit kerja **Sekretariat DPRD**. Jika dilihat pada folder hirarki, unit kerja **Sekretariat DPRD** terletak di bawah unit kerja **Pemrov Banten** yang mana menunjukan bahwa unit kerja level 1 berhasil di tambahkan. 

[![Folder Unit Kerja Baru](/images/sso/manajemen-organisasi/sso_unit-kerja-baru.png)](/images/sso/manajemen-organisasi/sso_unit-kerja-baru.png)

Jika kita klik folder **Sekretariat DPRD** maka akan muncul tampilan data dari unit kerja **Sekretariat DPRD** di sebelah kanan, seperti unit kerja yang dibawahinya dan juga orang yang bertanggung jawab terhadap unit kerja tersebut. Saat ini di dalam data tersebut masih kosong dan kita akan menambahkan unit kerja yang ada di bawah **Sekretariat DPRD** yaitu yang memiliki level 2 sampai level 5.

## Menambah Unit Kerja baru Level 2

[![Folder Unit Kerja Baru 2](/images/sso/manajemen-organisasi/sso_unit-kerja-baru2.png)](/images/sso/manajemen-organisasi/sso_unit-kerja-baru2.png)

Selanjutnya kita akan menambahkan unit kerja baru yang memiliki level 2 pada unit kerja **Sekertariat DPRD** yaitu unit kerja **Bagian Hukum dan Persidangan**. Unit kerja ini (**Bagian Hukum dan Persidangan**) akan di tambahkan pada folder **Sekertariat DPRD** karena memiliki level 2 dan terletak di bawah **Sekertariat DPRD** jika dilihat pada halaman  [ini](https://opd-01.dev.bantenprov.go.id/laravel-opd). 

[![Halaman OPD](/images/sso/manajemen-organisasi/sso_halaman-opd.png)](/images/sso/manajemen-organisasi/sso_halaman-opd.png)

Peratama klik folder **Sekertariat DPRD**, lalu tambah unit kerja baru (**tutorial menambah unit kerja baru ada di atas**) seperti pada gambar di bawah ini:

[![Tambah Unit Kerja 2](/images/sso/manajemen-organisasi/sso_tambah-unit-kerja2.png)](/images/sso/manajemen-organisasi/sso_tambah-unit-kerja2.png)

Maka akan muncul halaman untuk menambah unit kerja baru seperti gambar di bawah ini:

 [![Tambah Unit Kerja Baru 2](/images/sso/manajemen-organisasi/sso_tambah-unit-kerja-baru2.png)](/images/sso/manajemen-organisasi/sso_tambah-unit-kerja-baru2.png)
 
Pada halaman ini kita hanya akan mengisi 4 field seperti sebelumnya yaitu: 
 1. Name: Field ini diisi dengan nama unit kerja dan semuanya huruf kecil, misalkan **bagian_hukum_dan_persidangan**.
 2. Display Name: Field ini diisi dengan nama resmi dari unit kerja yang ingin di tambahkan, misalkan **Bagian Hukum dan Persidangan**.
 3. Identifier: Field ini diisi dengan UUID dari unit kerja yang ingin di tambahkan, misalkan **E8FE7614-5DF3-4424-8BFD-04D56D4AA202**.
 4. Cost Center: Field ini diisi dengan kode dari unit kerja yang ingin di tambahkan, misalkan **000201000000000**.
 
Jika sudah terisi maka tekan tombol save pada halaman bagian bawah, berikut merupakan contoh field yang sudah terisi:
 
## Menambah Unit Kerja baru level 3

[![Form Terisi 2](/images/sso/manajemen-organisasi/sso_form-tambah-unit-kerja-terisi2.png)](/images/sso/manajemen-organisasi/sso_form-tambah-unit-kerja-terisi2.png)

Jika sudah menekan tombol save maka unit kerja baru akan muncul pada struktur hirarki, pada contoh ini unit kerja baru tersebut adalah **Bagian Hukum dan Persidangan** dan akan terletak di bawah folder **Sekertariat DPRD** seperti gambar di bawah ini:

[![Folder Unit Kerja Baru 3](/images/sso/manajemen-organisasi/sso_unit-kerja-baru3.png)](/images/sso/manajemen-organisasi/sso_unit-kerja-baru3.png)

Selanjutnya kita akan menambahkan unit kerja baru yaitu **Sub Bagian Alat Kelengkapan DPRD**. Jika di lihat di halaman  [ini](https://opd-01.dev.bantenprov.go.id/laravel-opd), unit kerja **Sub Bagian Alat Kelengkapan DPRD** terletak di bawah unit kerja **Bagian Hukum dan Persidangan** dan memiliki level 3. 

[![Halaman OPD 2](/images/sso/manajemen-organisasi/sso_halaman-opd2.png)](/images/sso/manajemen-organisasi/sso_halaman-opd2.png)

Berarti kita akan membuat unit kerja ini di dalam folder **Bagian Hukum dan Persidangan** karena unit kerja ini memiliki level 2. Langkah untuk menambah unit kerja sama seperti contoh yang ada di atas, pertama klik folder **Bagian Hukum dan Persidangan** lalu tambah unit kerja baru maka akan muncul gambar seperti di bawah ini:

 [![Tambah Unit Kerja Baru 3](/images/sso/manajemen-organisasi/sso_tambah-unit-kerja-baru3.png)](/images/sso/manajemen-organisasi/sso_tambah-unit-kerja-baru3.png)

Jika kita lihat pada bagian sebelah kanan halaman maka kita bisa melihat Organization yang tertulis, pada contoh ini yaitu **Bagian Hukum dan Persidangan** yang berarti kita akan menambahkan unit kerja baru di folder **Bagian Hukum dan Persidangan**.

Untuk mengisi form sama seperti contoh pengisian yang sebelumnya, berikut merupakan gambar form yang sudah terisi:

[![Form Terisi 3](/images/sso/manajemen-organisasi/sso_form-tambah-unit-kerja-terisi3.png)](/images/sso/manajemen-organisasi/sso_form-tambah-unit-kerja-terisi3.png)

Jika sudah menekan tombol save, maka akan muncul unit kerja baru pada struktur hirarki yaitu folder **Sub Bagian Alat Kelengkapan DPRD** seperti pada gambar di bawah ini:

[![Folder Unit Kerja Baru 4](/images/sso/manajemen-organisasi/sso_unit-kerja-baru4.png)](/images/sso/manajemen-organisasi/sso_unit-kerja-baru4.png)

Untuk pengisian unit kerja selanjutnya langkah yang di tempuh sama seperti di atas, yang perlu di perhatikan adalah penempatan unit kerjanya harus sesuai dengan level yang tertera pada unit kerja tersebut. Berikut merupakan gambar tabel unit kerja yang terdapat di halaman [opd](https://opd-01.dev.bantenprov.go.id/laravel-opd):

[![Halaman OPD 3](/images/sso/manajemen-organisasi/sso_halaman-opd3.png)](/images/sso/manajemen-organisasi/sso_halaman-opd3.png)

Pada gambar di atas maka kita akan melihat tabel unit kerja besera levelnya. Untuk membuat unit kerja baru jika mengacu pada tabel di atas maka langkah-langkahnya adalah sebagai berikut:

 1. Buat unit kerja baru di dalam folder **Pemprov Banten**, unit kerja yang di buat adalah **Sekretariat Daerah** karena unit kerja ini memiliki level 1 (**untuk unit kerja level 1 harus di buat di dalam folder Pemprov Banten**).

2. Buat unit kerja **Asisten Pemerintahan dan Kesejahteraan Rakyat**, unit ini di buat didalam folder **Sekretariat Daerah** karena unit ini memiliki level 2 dan jika dilihat pada gambar berada di bawah unit kerja **Sekretariat Daerah**.

3. Buat unit kerja **Biro Pemerintahan**, unit ini di buat didalam folder **Asisten Pemerintahan dan Kesejahteraan Rakyat** karena unit ini memiliki level 3 dan terletak di bawah unit kerja **Asisten Pemerintahan dan Kesejahteraan Rakyat**.

4. Buat unit kerja **Bagian Kerjasama**, unit ini dibuat didalam folder **Biro Pemerintahan** karena unit ini memiliki level 4 dan terletak di bawah unit kerja **Biro Pemerintahan**.

5. Buat unit kerja **Sub Bagian Kerjasama Daerah**, **Sub Bagian Kerjasama Luar Negeri**, dan **Sub Bagian Tata Usaha**. Semua unit ini di buat di dalam folder **Bagian kerjasama** karena semua unit ini memiliki level 5 dan terletak di bawah unit kerja **Bagian Kerjasama**.

6. Buat unit kerja **Bagian Administrasi Kewilayahan**, unit ini di buat di dalam folder **Biro Pemerintahan** karena unit ini memiliki level 4 dan terletak di bawah unit kerja **Biro Pemerintahan**. Untuk mengisi unit kerja selanjutnya tinggal ikuti langkah yang telah ada.

## Struktur Hirarki Unit Kerja

Berikut ini adalah contoh struktur hirarki unit kerja yang dibuat jika mengacu pada halaman [opd](https://opd-01.dev.bantenprov.go.id/laravel-opd).

```
root/
   |---Pemprov Banten                 
       |---Sekertariat Daerah                                             Level 1
       |   |---Asisten Pemerintahan dan Kesejahteraan Rakyat              Level 2
       |       |---Biro Pemerintahan                                      Level 3
       |           |---Bagian Kerjasama                                   Level 4
       |           |   |---Sub Bagian Kerjasama Daerah                    Level 5
       |           |   |---Sub Bagian Kerjasama Luar Negeri               Level 5
       |           |   |---Sub Bagian Tata Usaha                          Level 5
       |           |---Bagian Administrasi Kewilayahan                    Level 4
       |               |---Sub Bagian Administrasi Bina Kecamatan         Level 5
       |               |---Sub Bagian Batas Daerah                        Level 5    
       |               |---Sub Bagian Administrasi Rupabumi               Level 5
       |---Sekertariat DPRD                                               Level 1
           |---Bagian Hukum dan Persidangan                               Level 2
           |   |---Sub Bagian Alat Kelengkapan DPRD                       Level 3
           |   |---Sub Bagian Produk Hukum dan Tenaga Ahli DPRD           Level 3
           |   |---Sub Bagian Persidangan, Rapat, dan Risalah             Level 3
           |---Bagian Keuangan                                            Level 2
           |   |---Sub Bagian Perencanaan                                 Level 3
           |   |---Sub Bagian Verifikasi dan Pembukuan                    Level 3
           |   |---Sub Bagian Perbendaharaan                              Level 3
           |---Bagian Umum dan Kepegawaian                                Level 2
               |---Sub Bagian Tata Usaha dan Kepegawaian                  Level 3
               |---Sub Bagian Perlengkapan                                Level 3
               |---Sub Bagian Rumah Tangga                                Level 3
```  
