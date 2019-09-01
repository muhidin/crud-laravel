# crud-laravel
Membuat CRUD menggunakan Larave 6.0 studi kasus tabel Buku pada Perpustakaan

clone repository dengan perintah
$ git-clone https://github.com/muhidin/crud-laravel.git

pilih folder project
$ cd crud-laravel

buat database melalui perintah mysql
$ mysql -uroot -p

pada prompt mysql berikan perintah membuat database dengan nama crud-laravel
mysql> create database crud-laravel;

selesai, kembali ke prompt dengan ctrl + D alias exit
mysql> exit;

jalankan migrate agar tabel terbentuk
$ php artisan migrate

jalankan serve laravel atau langsung buka browser
$ php artisan serve
