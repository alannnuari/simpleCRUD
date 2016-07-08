# simpleCRUD
SimpleCRUD adalah aplikasi Create, Read, Update dan Delete data sederhana yang dibangun dengan bahasa PHP.

Fitur :
+CRUD (Create, Read, Update dan Delete data)
+notifikasi, pesan ketika sukses tambah data, sukses update data, maupun hapus data.

Cara setting 
+buat folder baru di htdocs misal simpleCRUD
+extract file dalam master kedalam folder yang telah dibuat
+buka phpmyadmin dan buat database baru dengan nama 'db_simplecrud'
+buka file koneksi dengan notepad dan edit seperti berikut :
  $host = 'localhost';
  $user = 'root'; //username database di phpmyadmin
  $pass = ''; //password database di phpmyadmin defaultnya kosong => ''
  $db = 'db_simplecrud'; //nama database di phpmyadmin
