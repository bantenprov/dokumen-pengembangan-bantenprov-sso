---
date: 2018-05-10
title: Manajemen Role
description: Manajemen Role Perangkat Daerah dalam SSO
categories:
  - sso
type: Document
---

## Menu dan Cara Penggunaan Manajemen Role

### Tampilan Halaman List Role

[![Halaman Menu Role](/images/sso/manajemen-role/sso_halaman-list-role.png)](/images/sso/manajemen-role/sso_halaman-list-role.png)

Halaman ini berfungsi untuk menampilkan list role yang tersedia di aplikasi SSO. Setiap role memiliki hak akses yang berbeda-beda tergantung kewenangannya. Role tertinggi dimiliki oleh Superadmin yang mana memiliki hak akses ke semua menu dan user yang terdapat di dalam aplikasi. Setiap role memiliki kode dan identifier (UUID) yang berbeda dan juga di dalam menu role terdapat member yang terdiri dari user. User yang terdapat dalam suatu role hanya memiliki hak akses sesuai dengan role tersebut. Sebelum menambahkan user pada suatu role, sebelumnya harus terdapat user yang ingin ditambahkan. List user yang ingin di tambahkan bisa dilihat di menu User

Untuk menambahkan role maka admin harus membuka menu role pada sebelah kiri halaman seperti gambar di bawah ini:

[![Tombol Menu Role](/images/sso/manajemen-role/sso_tombol-menu-role.png)](/images/sso/manajemen-role/sso_tombol-menu-role.png)

Didalam menu ini terdapat 2 sub menu yaitu :

 1. List Role: Sub menu ini berfungsi untuk melihat list role yang telah dibuat.
 2. New Role: Sub menu ini berfungsi untuk membuat role baru sesuai yang dibutuhkan.

Setelah membuka menu role, maka admin menekan tombol **New Role** seperti gambar di bawah ini:

[![Tombol New Role](/images/sso/manajemen-role/sso_tombol-menu-new-role.png)](/images/sso/manajemen-role/sso_tombol-menu-new-role.png)

## Membuat Role Baru

Maka akan terbuka halaman create new role. Pada halaman ini terdapat form untuk mengisi data dari role tersebut seperti: Nama Role, Nama Yang Ditampilkan, Identifier (UUID), dan juga permission yang diberikan.

[![Halaman Create Role](/images/sso/manajemen-role/sso_halaman-create-new-role.png)](/images/sso/manajemen-role/sso_halaman-create-new-role.png)

Untuk pengisian form ini kita hanya mengisi 3 field saja yaitu:

 1. Name
 2. Display Name
 3. Identifier

Berikut contoh form yang harus diisi:

[![Contoh Form Kosong](/images/sso/manajemen-role/sso_form-kosong.png)](/images/sso/manajemen-role/sso_form-kosong.png)

Jika sudah terisi akan seperti ini:

[![Contoh Form Terisi](/images/sso/manajemen-role/sso_form-terisi.png)](/images/sso/manajemen-role/sso_form-terisi.png)

Jika form sudah terisi seperti gambar di atas maka langkah selanjutnya yaitu menekan tombol save yang terdapat di bawah form seperti gambar di bawah ini:

[![Tombol Save](/images/sso/manajemen-role/sso_tombol-save.png)](/images/sso/manajemen-role/sso_tombol-save.png)

Setelah menekan tombol save maka role yang telah dibuat akan muncul di halaman list role, pada contoh ini role yang ditambahkan yaitu role **Gubernur**. Berikut merupakan tampilan role yang baru di ditambahkan:


[![Role Baru ditambah](/images/sso/manajemen-role/sso_role-baru-ditambahkan.png)](/images/sso/manajemen-role/sso_role-baru-ditambahkan.png)

Jika langkah menambahkan role telah berhasil, maka selanjutnya kita menambahkan role baru sesuai dengan yang di butuhkan. Untuk manambahkan role baru langkah yang ditempuh sama seperti sebelumnya, berikut ini merupakan beberapa role yang sudah di tambahkan:

[![Role Yang sudah di tambahkan](/images/sso/manajemen-role/sso_role-sudah-ditambahkan.png)](/images/sso/manajemen-role/sso_role-sudah-ditambahkan.png)

## Menambahkan User Pada Role

Jika role yang ingin ditambahkan dirasa sudah cukup, maka langkah selanjutnya kita menambahkan user pada role yang telah kita buat. Setiap user memiliki hak akses yang berbeda tergantung di role mana user tersebut di tambahkan, untuk menambahkan user pada suatu role berikut langkah-langkahnya:

[![List Role](/images/sso/manajemen-role/sso_role-list-ditambahkan.png)](/images/sso/manajemen-role/sso_role-list-ditambahkan.png)

1. Buka menu list role, lalu kita pilih role mana yang ingin ditambahkan user. Pada contoh ini kita akan menambahkan user pada role **Gubernur**, maka kita harus mengklik role **Gubernur** yang terdapat di list seperti gambar di bawah ini:

 [![Role Gubernur Diklik](/images/sso/manajemen-role/sso_role-gubernur.png)](/images/sso/manajemen-role/sso_role-gubernur.png)

2. Akan muncul halaman edit role seperti gambar di bawah ini:

 [![Halaman Edit Role](/images/sso/manajemen-role/sso_halaman-edit-role.png)](/images/sso/manajemen-role/sso_halaman-edit-role.png)

3. Lalu pilih menu members seperti gambar di bawah ini:

 [![Menu Members](/images/sso/manajemen-role/sso_menu-members.png)](/images/sso/manajemen-role/sso_menu-members.png)

4. Akan muncul form members, lalu langkah selanjutnya klik icon setting dan pilih **Add member** seperti gambar dibawah ini:

 [![Add member](/images/sso/manajemen-role/sso_form-members.png)](/images/sso/manajemen-role/sso_form-members.png)

5. Lalu akan muncul list user yang bisa di tambahkan seperti gambar di bawah ini:

 [![List User Yang Akan Dipilih](/images/sso/manajemen-role/sso_list-user-yang-akan-dipilih.png)](/images/sso/manajemen-role/sso_list-user-yang-akan-dipilih.png)

6. Untuk menambahkan user yang ada di dalam list cukup memberi ceklis pada kolom nama user lalu menekan tombol add, pada contoh ini kita akan menambahkan user dengan nama **Adi** dan **Bai**.

 [![List User Yang TelahDipilih](/images/sso/manajemen-role/sso_list-user-yang-telah-dipilih.png)](/images/sso/manajemen-role/sso_list-user-yang-telah-dipilih.png)

7. Berikut ini adalah tampilan user yang telah di tambahkan:

 [![Tampilan List Members](/images/sso/manajemen-role/sso_halaman-edit-role-user.png)](/images/sso/manajemen-role/sso_halaman-edit-role-user.png)

8. Langkah selanjutnya yaitu cara menghapus user dari suatu role yaitu cukup memberi ceklis pada nama user yang terdapat di list Members lalu klik icon settings pada sebelah kanan layar lalu pilih remove member, pada contoh ini kita akan menghapus user role tadi telah kita tambahkan. 

 [![List User Yang Akan Dihapus](/images/sso/manajemen-role/sso_halaman-edit-hapus-user.png)](/images/sso/manajemen-role/sso_halaman-edit-hapus-user.png)

9. Jika sudah selesai maka user akan hilang dari form Members seperti gambar di bawah ini:

 [![Form Member Kosong](/images/sso/manajemen-role/sso_halaman-edit-user-kosong.png)](/images/sso/manajemen-role/sso_halaman-edit-user-kosong.png)
