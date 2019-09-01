# crud-laravel
Membuat CRUD menggunakan Larave 6.0 studi kasus tabel Buku pada Perpustakaan

clone repository dengan perintah<br>
<code>$ git-clone https://github.com/muhidin/crud-laravel.git</code>

pilih folder project<br>
<code>$ cd crud-laravel</code>

buat database melalui perintah mysql<br>
<code>$ mysql -uroot -p</code>

pada prompt mysql berikan perintah membuat database dengan nama crud-laravel<br>
<code>mysql> create database crud-laravel;</code>

selesai, kembali ke prompt dengan ctrl + D alias exit<br>
<code>mysql> exit;</code>

Update composer dengan perintah
<br><code>$ composer update</code>

jalankan migrate agar tabel terbentuk
<br><code>$ php artisan migrate</code>

jalankan serve laravel atau langsung buka browser
<br><code>$ php artisan serve</code>

Demikian semoga bermanfaat dan sama seru ngoprek.
