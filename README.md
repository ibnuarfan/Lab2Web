# Lab2Web
Praktikum 2
Pertanyaan :
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )


Jawab :
1.Menambahkan border-style groeve pada intro dan border-style- outset di intro h1
2.Elemen h1 mencakup intro h1,elemen h1 meliputi juga button navigasi dan #intro h1 yang bertuliskan hello wordl
3.Yang lebih cepat responnya adalah css eksternal karena bisa membuat ukuran file html menjadi lebih kecil.
 Contoh css internal : 
<!DOCTYPE html>
<html>
<head>
<style>
body {
    background-color: blue;
}
h1 {
    color: red;
    padding: 60px;
} 
</style>
</head>
<body>
 
<h1>Hostinger Tutorials</h1>
<p>This is our paragraph.</p>
 
</body>
</html>

 Contoh css inline   : 

<!DOCTYPE html>
<html>
<body style="background-color:black;">
 
<h1 style="color:white;padding:30px;">Hostinger Tutorials</h1>
<p style="color:white;">Something usefull here.</p>
 
</body>
</html>

Contoh css eksternal :
<head>
  <link rel="stylesheet" type="text/css" href="style.css" />
</head>

4.Yang akan ditampilkan sebagai file css adalah elemen "class" karena elemen "class" mendeklarasikan class css yang digunaknan .Sedangan id menentukan id unik yang terdapat pada elemen
contoh :   <a class="button btn-primary "href="intro"> Informasi selengkapnya</a>
