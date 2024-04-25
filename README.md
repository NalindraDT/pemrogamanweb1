
# Project ini merupakan sebuah pembelajaran yang meliputi

 - HTML
 - CSS
 - JS
 
 ### Tujuan
 - Mengetahui perintah perintah dasar dari bahasa pemgroman web
 - Mengetahui dasar dasar yang diperlukan untuk menjadi seorang web developer
 - Menguak proses yang terjadi di balik layar sebuah website


 ## HTML

 
## Pengenalan
Berikut merupakan sebuah codingan sederhana yang berisi berbagai macam tag dasar seperti:
- "head" yang merupakan menentukan meta name
- "body" yang merupakan bagian utama sebuah document html
- "h" yang berarti header
- "u" yang berarti underline
- "br" yang berfungsi mengubah baris
- "p" sebagai pembuat paragraf
- "a" dan "href" sebagai sumber link
- "img src" sebagai input gambar

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coba Heading</title>
</head>
<body>

<h1><u> Headings</h1><br></u>
    <h1> Ini adalah heading modif 1</h1>
    <h2> Ini adalah heading modif 2</h2>
    <h3> Ini adalah heading modif 3</h3>
    <h4> Ini adalah heading modif 4</h4>
    <h5> Ini adalah heading modif 5</h5>
    <h6> Ini adalah heading modif 6</h6><br>

<h1><U>Paragraphs</U></h1>
    <p>Ini adalah paragraf yang di modif</p>
    <p>ini adalah paragraf lain yang di modif</p><br>


<h1><u>Links</u></h1>
    <a href="https://www.youtube.com/watch?v=AhvkKR0ero8">Ini adalah link video kali uchis</a><br>
    <br>

    <h1><u> Images</u></h1>
<img src="https://static.independent.co.uk/s3fs-public/thumbnails/image/2020/07/23/17/jesse-lingard.jpg" width="300" height="300">
</body>
</html>
```

### Hasil:

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

(sebuah header memilki ketebalan dan ukuran font yang berbeda sesuia tipe mereka)
##
## Comment
Sebuah comment memiliki fungsi untuk memberikan comment atau sebuah penjelasan tertulis tanpa mengganggu coding

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2>Comment</h2>
    <p>Ini adalah paragraf</p>
    <!-- Halo guys ini adalah comment jika ada sebuah perintah atau kalimat yang memasuki jangkauan comment
         maka perintah atau kalimat tersebut tidak berlaku -->
    <p>hai ini paragarf</p>
</body>
</html>
```

Hasil:

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

#
## Link
Untuk melampirkan sebuah link anda dapat menggunakan tag "a" dan "h ref" lalu anda dapat memasukan value sesuai kemauan anda
sebuah link dapat berbentuk seperti gambar juga, untuk selengkapnya berada di file html.

```html
<!DOCTYPE html>
<html>
<body>

<h1>HTML Links</h1>

<p><a href="https://github.com/NalindraDT" title="pergi ke github nale">Visit my github</a></p>

</body>
</html>

```

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)
#
## Image

Sebuah gambar dapat dilampirkan jika anda menggunkan "img src", dengan menggunakan tag ini anda dapat melampirkan gambar dalam folder yang sama,
dalam folder yang berbeda, dan link image dari web lain

```html
<!DOCTYPE html>
<html>
<body>

<h2>Animated Images</h2>

<p>HTML allows moving images:</p>

<img src="kucinggaruk.gif" alt="Kuncing Gatel" style="width:148px;height:148px;">

</body>
</html>

```
## Hasil:

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

dalam gambar diatas merupakan salah satu contoh dari banyak nya contoh cara untuk melampirkan gambar

#
## List
dengan menggunanakan tag "li" anda bisa membuat list dengan cara yang berbeda beda seperti
- tag "ul" untuk list yang tidak berurutan ( titik tengah, strip, symbol lain)
- tag "ol" untuk list yang berurutan (angka, huruf, romawi)


### ol (ordered list)
```html
<!DOCTYPE html>
<html>
<body>

<h2>An ordered HTML list</h2>

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>  

</body>
</html>
```

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


### ul (unordered list)
```html
<!DOCTYPE html>
<html>
<body>

<h2>An unordered HTML list</h2>

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>  

</body>
</html>
```

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


#
## table
anda dapat membuat sebuah table sederhana menggunakan tag "table", sebuah table memilik tag lain seperti
- th (table header)
- td (table cell)
- tr (table row)

```html
<!DOCTYPE html>
<html>
<style>
table, th, td {
  border:1px solid black;
}
</style>
<body>

<h2>A basic HTML table</h2>

<table style="width:100%">
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>

<p>To understand the example better, we have added borders to the table.</p>

</body>
</html>

```

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

#
## Contoh pelaksanaanya

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <h2>Praktikum Pemrograman Web 1</h2>
    <ul type="square">
    <li style="color: green;">Senin</li>
    <ol type="a">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ol>
    <li style="color: blue;">Selasa</li>
    <ol type="I">
          <li>Boostrap</li>
          <li>Introduction</li>
          <li>Layout</li>

    </ol>
    <ol>
      <li>PHP</li>
      <li>MySQL</li>
    </ol>
    </ul>

    </pre>
  </body>
</html>
```
Contoh pembuatan list bersarang





