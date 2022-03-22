# Lab2Web

## NAMA     : Muhammad Bisma Putra H
## Kelas    : TI.20.A.1
## NIM      : 312010443

#
# 1. MEMBUAT DOKUMEN HTML
<img width="959" alt="pertama" src="https://user-images.githubusercontent.com/101621391/159464314-b755d0e4-3b00-47cb-b698-25d3497ee017.png">

## Contoh coding
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSS Dasar</title>
</head>
<body>
<header>
<h1>CSS Internal dan <i>Inline CSS</i></h1>
</header>
<nav>
<a href="lab2_css_dasar.html">CSS Dasar</a>
<a href="lab2_css_eksternal.html">CSS Eksternal</a>
<a href="lab1_tag_dasar.html">HTML Dasar</a>
</nav>
<!-- CSS ID Selector -->
<div id="intro">
<h1>Hello World</h1>
<p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman
Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML
dan CSS.</p>
<!-- CSS Class Selector -->
<a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
</div>
</body>
</html>
```
#
# 2. Mendeklarasikan CSS Internal
<img width="951" alt="2" src="https://user-images.githubusercontent.com/72791776/159485467-113377d4-f48b-40c5-96e6-9ca3b79f69a4.png">
Ini adalah hasil Mendeklarasikan CSS Internal

## Contoh coding
```
<head>
    <!-- menyisipkan css eksternal -->
<link rel="stylesheet" href="style_eksternal.css" type="text/css">
    <title>CSS Dasar</title>
    <style>
    body {
    font-family:'Open Sans', sans-serif;
    }
    header {
    min-height: 80px;
    border-bottom:1px solid #000000;
    }
    h1 {
    font-size: 24px;
    color: #000000;
    text-align: center;
    padding: 20px 10px;
    }
    h1 i {
    color:#6d6a6b;
    }
    </style>
</head>
```
#
# 3. Menambahkan Inline CSS
<img width="950" alt="3" src="https://user-images.githubusercontent.com/72791776/159485573-b07f7b03-c8ac-4ee7-b4a3-66de2a5979f6.png">
Ini adalah hasi dari Menambahkan Inline CSS

## Contoh coding
```
<p> style="text-align: center; color: #ccd8e4;"> </p>
```
#
# 4. Membuat CSS Eksternal
<img width="131" alt="buat file" src="https://user-images.githubusercontent.com/101621391/159469421-583c6562-458d-4f41-a01d-087b565665d7.png">

Selanjutnya buatlah file baru dengan nama style_eksternal.css 
Caranya masukan Contoh codingan berikut :

## Contoh coding
```
nav {
    background: #555555;
    color:#fff;
    padding: 10px;
    }
nav a {
    color: #fff;
    text-decoration: none;
    padding:10px 20px;
    }
nav .active,
nav a:hover {
    background: #414141;
    }
```
Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian <head>.

Caranya yaitu, masukan contoh codingan berikut :

<link rel="stylesheet" href="style_eksternal.css" type="text/css">

Setelah memasukan contoh codingannya, simpan dan pergi lagi ke browser kemudian refresh kembali browser tersebut dan lihatlah perubahannya.


<img width="956" alt="4" src="https://user-images.githubusercontent.com/72791776/159485689-04af4f33-ab5d-4c10-bb6d-9e16931c8608.png">
Inilah contoh perubahannya

#
# 5. Menambahkan CSS Selector
Cara menambahkan CSS Selector adalah.

Gunakan ID dan Class Selector. Pada file
style_eksternal.css.

Cara menambahkannya ialah masukan kode berikut di file style_eksternal.css.
```
/* ID Selector */
#intro {
    background: #444444;
    border: 1px solid #000000;
    min-height: 100px;
    padding: 10px;
    }
    #intro h1 {
    text-align: left;
    border: 0;
    color: #fff;
    }
    /* Class Selector */
    .button {
    padding: 15px 20px;
    background: #bebcbd;
    color: #fff;
    display: inline-block;
    margin: 10px;
    text-decoration: none;
    }
    .btn-primary {
    background: #286936;
    }

```
Setelah menambahkan kodenya simpan (Ctrl s) filenya, dan pergi lagi ke broeser kemudian refresh, lihatlah perubahannya.
<img width="958" alt="5" src="https://user-images.githubusercontent.com/72791776/159485764-bef4b36a-2228-4230-be5e-85721a064682.png">
Inilah contoh perubahannya