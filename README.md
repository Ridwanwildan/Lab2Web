# Latihan menggunakan CSS pada website 

* Nama          : Hizbullah Ridwan
* NIM           : 312110055
* Kelas         : TI.21.B.1
* Mata Kuliah   : Pemrograman Web

Dalam latihan menggunakan CSS ini, saya menggunakan [Google Chrome](https://www.google.com/intl/id_id/chrome/) sebagai web browser dan [visual studio code](https://code.visualstudio.com/) sebagai teks editornya.       

## Membuat Dokumen HTML

Hal pertama yang harus disiapkan adalah membuat file HTML dasar. Pada file HTML ini juga         
sudah disiapkan beberapa elemen seperti header, paragraf, dan juga hyperlink.            

```bash
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
            <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman Web</b> di 
            <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat adalah membuat 
            tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.</p>
            <!-- CSS Class Selector -->
            <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
        </div>
    </body>
</html>
```         

Setelah selesai dibuat dan disimpan, jalankan file HTML pada web browser dan lihat hasilnya.            

![Gambar 1](Screenshoots/Capture1.PNG)      