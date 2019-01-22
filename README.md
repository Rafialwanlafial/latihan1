# Tutorial Cara Penggunaan Git
Pertama-tama kita download dan instal terlebih dahulu Aplikasi Git sesuai PC masing-masing (https://git-scm*com/) * ganti .

Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email akun "Github"

Config :

   $ git config --global user.name "Nama User Github kalian"
   $ git config --global user.email "Contoh@gmail.co.id"
Kemudian buat forlder baru "labs_pemrograman1"

Kemudian klik kanan pada folder tersebut dan pilih "Git Bash Here"

Maka akan muncul jendela git bash

kita buat projek pertama dengan nama latihan01

Config :

  $ mkdir latihan01

  $ cd latihan01

  sehingga terbentuk satu direktori baru dibawahnya "d/labs_pemrograman1/latihan01"
Selanjutnya, membuat reposiory local

jalankan perintah "git init" (tanpa tanda " ) , untuk membuat repository local. Maka akan terbentuknya satu direktori hidden dengan nama .git

kemudian menambahkan file baru pada repository. *disini kita akan menamakan file README.md

   Config : $ echo "#latihan01" >> README.md
selanjutnya, menambahkan file baru pada repository

   Config : $ git add README.md
menyimpan perubahan ke database

   Config : $ git commit -m "File pertama Saya"
............

...............

..................

GITHUB.COM

Selanjunya kita beralih github.com *pastikan kalian punya akun di Github.com <<

Pada laman github, klik tombol start a project, atau dari menu (icon +) kilk New Repository

Isi nama repository kalian, lalu kilk tombol Create Repository

Menambahkan Remote Repository

  Config $ git remote add origin http://github.com/.........git
Push (Mengirim perubahan ke Server)

  Config $ git push -u origin master
Buka laman Github.com , arahkan pada repositoriny, makan perubahan pada laman terbut
