Jawaban Soal Pertama :
Server-side scripting adalah proses menjalankan skrip di sisi server untuk menghasilkan halaman web dinamis atau menjalankan logika aplikasi web. Skrip ini biasanya digunakan untuk menangani permintaan pengguna, memproses data, dan mengelola interaksi dengan database atau sumber daya lainnya sebelum mengirimkan hasil ke browser pengguna.

Cara Kerja Server-side Scripting
1. Permintaan Klien (HTTP Request): Proses dimulai ketika browser pengguna (klien) mengirimkan permintaan HTTP ke server. Contoh permintaan ini dapat berupa permintaan untuk halaman web tertentu atau pengiriman data formulir.
   
2. Pemrosesan di Server: Server web menerima permintaan dan meneruskannya ke mesin skrip (misalnya, PHP, Python, Node.js). Mesin skrip menjalankan logika bisnis yang telah ditentukan dalam file skrip. Proses ini bisa melibatkan:
   - Validasi data pengguna.
   - Eksekusi algoritma atau fungsi tertentu.
   - Pengambilan data dari database.
   - Pengolahan informasi dinamis.
     
3. Interaksi dengan Database (Opsional):Jika data diperlukan dari database, skrip akan mengirim kueri ke database.Server database memproses kueri dan mengembalikan hasilnya ke skrip.
   
4. Pembuatan Respon (Dynamic Content): Skrip menghasilkan halaman web atau data dinamis berdasarkan hasil pemrosesan. Halaman ini biasanya berupa file HTML yang telah disisipkan data dinamis (contoh: daftar produk, nama pengguna, atau laporan statistik).
   
5. Pengiriman Respon (HTTP Response): Hasil dari server-side scripting dikirim kembali ke browser klien dalam bentuk halaman HTML, JSON, XML, atau format lain yang sesuai.
   
6. Rendering di Browser: Browser pengguna menerima hasil dan menampilkannya kepada pengguna.

Jawaban Soal Kedua :
<?php

$Nim = "312310328";
$nama = "Navrida Rully Anastasya";
$Kelas = "TI.23.CA.1";

?>

<h1>
Saya Adalah 
<?php echo $nama?>
</h1>
<p>
 <strong>Kelas</strong>=<?php echo $Kelas?>
</p>
<p>
 <strong>Nim</strong>=<?php echo $Nim?>
</p>


