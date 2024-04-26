
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

![alt text](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/html1.png?raw=true)

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

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/html2.png)

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

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/html3.png)
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

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/html4.png)

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

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/html5.png)


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

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/html6.png)


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

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/html7.png)

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

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/html8.png)

#
# CSS

Dalam perogaman web, CSS digunakan untuk mendekorasi atau memperindah sebuah website. Dengan penggunaan CSS yang baik dan benar,
para user pasti akan merasa nyaman menggunkan website yang mereka kunjungi


#
## style dan selector
"style" merupakan sebuah tag utama yang selalu digunakan oleh web developer untuk memperindah website mereka,
tag "style" memiliki banyak fungsi seperti:
- mengubah warna suatu teks
- mengubah background
- mengubah style dan ukuran font
- dan masih banyak lagi
selector merupakan perantara antara tag "style" dan tag lain untuk mendapatkan sebuah dekorasi

```html
<!DOCTYPE html>
<html>
<head>
<style>
h1, h2, p {
  text-align: center;
  color: red;
}
.nale{
  text-align: center;
  color: greenyellow;
}
#nale1{
  text-align: center;
  color: blue;
}
p.nale{
  text-align: center;
  color: pinkw;
</style>
</head>
<body>

<h1>Hello World!</h1>
<h2>Smaller heading!</h2>
<p>This is a paragraph.</p>

</body>
</html>
```

## hasil:
![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/CSS1.png)

- (h1,h2.p) = element
- (.nale) = "class= nale"
- (#nale1)= "id= nale1"
- (p.nale)= "p class= nale"


#
## Cara penggunaan
cara penggunaan sebuah CSS dapat dilakukan dengan cara berikut
- inline (berada di baris yang sama dengan perintah)
- internal (berada di head html)
- external (berada di luar file)

```html
  <!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="mystyle.css">
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
} 

</style>
</head>
<body>

<h1>This is a heading</h1>
<h2 style="color:blue;text-align:center;">ini heading 2</h2>
<p class="open">This is a paragraph.</p>

</body>
</html>

```
## hasil:

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/CSS2.png)

untuk contoh gambar yang lebih lengkap silahkan kunjungi files CSS

#
## Comment, Colors, and backgorund
- comment untuk memberi komentar tanpa merusak coding
- colors untuk mengganti warna tulisan, background dll
- background untuk mengganti gambar background

```html
  <!DOCTYPE html>
<html>
    <head>
        <style>
            h3{
                background-color:magenta;   
            }
            body{
                background-image:url(/html/kucing1.jpeg); /* halooo guys ini commentttt*/
            }
        </style>
    </head>
<body>
<h3>Halo wak</h3>
<h1 style="background-color:Tomato;">Tomato</h1>
<h1 style="background-color:Orange;">Orange</h1>
<h1 style="background-color:DodgerBlue;">DodgerBlue</h1>
<h1 style="background-color:MediumSeaGreen;">MediumSeaGreen</h1>  
<h1 style="background-color:Gray;">Gray</h1>
<h1 style="background-color:SlateBlue;">SlateBlue</h1>
<h1 style="background-color:Violet;">Violet</h1>
<h1 style="background-color:LightGray;">LightGray</h1>

<h1 style="background-color:DodgerBlue;">Hello World</h1>

<p style="background-color:Tomato;">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
</p>

<h3 style="color:Tomato;">Hello World</h3>

<p style="color:DodgerBlue;">Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>

<p style="color:MediumSeaGreen;">Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.</p>

<h1 style="border: 2px solid Tomato;">Hello World</h1>

<h1 style="border: 2px solid DodgerBlue;">Hello World</h1>

<h1 style="border: 2px solid Violet;">Hello World</h1>

<p>Same as color name "Tomato":</p>

<h1 style="background-color:rgb(255, 99, 71);">rgb(255, 99, 71)</h1>
<h1 style="background-color:#ff6347;">#ff6347</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">hsl(9, 100%, 64%)</h1>

<p>Same as color name "Tomato", but 50% transparent:</p>
<h1 style="background-color:rgba(255, 99, 71, 0.5);">rgba(255, 99, 71, 0.5)</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">hsla(9, 100%, 64%, 0.5)</h1>

<p>In addition to the predefined color names, colors can be specified using RGB, HEX, HSL, or even transparent colors using RGBA or HSLA color values.</p>
</body>
</html>
```
### Hasil:

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/CSS3.png)

#
## Box model, outline, dan text format
- box model (merupakan sebuah kotak yang dapat diberi sebuah tulisan macam macam)
- outline merupakan sebuah garis yang berada di bagian luar suatu objek
- text format merupakan bagaimana cara penulisan sebuah teks

## hasil:

```html
<!DOCTYPE html>
<html>
<head>
<style>
div {
  background-color: lightgrey;
  width: 300px;
  padding: 50px;
  margin: 20px;
  outline-style:dashed;
  outline-color: blue;
  letter-spacing: 5px;
}
</style>
</head>
<body>

<h2>Demonstrating the Box Model</h2>

<p>The CSS box model is essentially a box that wraps around every HTML element. It consists of: borders, padding, margins, and the actual content.</p>

<div>This text is the content of the box. We have added a 50px padding, 20px margin and a 15px green border. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div>

</body>
</html>
```

## hasil:

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/CSS4.png)
#
## Border, table, etc
- border untuk member pembatas pada tulisan
- table untuk menghias tabel dari html
- padding untuk memberi batas teks dalam tabel
- margins untuku membatasi tabel dengan pojokan
- hover digunakan untuk mengaktifkan sesuatu jika cursor melawati suatu variabel
- nth-child digunakan untuk menentutkan sesuatu dengan ganjil dan genap

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Challenge 1 - CSS</title>

</head>
  <style>
    body{
      font-family: arial;
    }
    .judul{
      text-align:center;
    }
    table, td, th {
      border: 1px solid;
      border-color:red;
    }
    table {
      width: 1000px;
      height: 20px;
      border-collapse: collapse;
      margin-right: auto;
      margin-left: auto;
    }
    th{
        color: white;
        background-color: rgb(87,87,218);
    }
    tr:nth-child(even) {
        background-color: #59ddd5;
    }
    tr:hover{
        background-color: greenyellow;
        font-size:120%;
        font-weight:bold;
    }
  
    
 
  </style>
<body>
  <h2 class="judul" style="color: blue "> Daftar Mahasiswa</h2>
  <table>
      <tr>
          <th>Nama</th>
          <th>Program Studi</th>
          <th>Kelas</th>
      </tr>
      <tr>
          <td>John Dee</td>
          <td>Teknik Informatika</td>
          <td>A-01</td>
      </tr>
      <tr>
          <td>Jane Smith</td>
          <td>Sistem Informasi</td>
          <td>B-02</td>
      </tr>
      <tr>
          <td>Alice Johnson</td>
          <td>Teknik Komputer</td>
          <td>A-03</td>
      </tr>
      <tr>
          <td>Bob Brown</td>
          <td>Teknik Elektro</td>
          <td>C-01</td>
      </tr>
      <tr>
          <td>Emily Davis</td>
          <td>Manajemen Informatika</td>
          <td>D-02</td>
      </tr>
  </table>
   <li><b>Keterangan : </b></li>
      <ol type="1">
        <li> Warna Heading dan Table Header adalah <b>rgb(87,87,218)</b></li>
        <li>Warna baris genap adalah <b>#59ddd5</b></li>
        <li>Warna saat hover adalah <b>greenyellow</b></li>
          <li>Warna saat hover adalah <b>greenyellow</b></li>
        <li>Pada saat hover, ukuran font <b>lebih besar</b>dan berubah menjadi<b>BOLD
        </b></li>
  </body>
</body>
</html>
```

## hasil:

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/CSS5.png)


# Java Script
Seperti sama halnya dengan rumah dimana yang mmenjadi pondasi itu html, yang menghiasi ruangan CSS dan yang menjalankan sistem nya adalah javascript.
Java script merupakan bahasa pemrogaman yang paling sering digunakan oleh web development dikarenakan ke mampuannya untuk mengolah data


## GetElementadeById
Merupakan sebuah command untuk memanggil suatu variabel

```html
<!DOCTYPE html>
<html>
  <body>
    <h2>What Can JavaScript Do?</h2>

    <p>JavaScript can show hidden HTML elements.</p>

    <p id="demo" style="display: none">Hello JavaScript!</p>

    <button
      type="button"
      onclick="document.getElementById('demo').style.display='block'"
    >
      Click Me!
    </button>
  </body>
</html>
```
![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/SSJS1.png)

#
## Let, Var, Const
Let, Var, Const intinya memiliki fungsi yang sama yaitu mendeklarasi sebuah variabel.
hanya saja let dan const lebih unggul daripada var

```html
<!DOCTYPE html>
<html>
  <body>
    <h2>JavaScript Arithmetic</h2>
    <p>
      A typical arithmetic operation takes two numbers (or variables) and
      produces a new number.
    </p>

    <p id="nale1"></p>
    <p id="nale2"></p>
    <p id="nale3"></p>

    <script>



      var c = 100;
      var d = 40;
      var e = c + d;

      let a = 100;
      let b = 50;
      let x = a + b;

      const f = 100;
      const g = 50;
      const h = g + f;
 
     
      document.getElementById("nale1").innerHTML = x;
      document.getElementById("nale2").innerHTML = e;
      document.getElementById("nale3").innerHTML = h;
    </script>
    
  </body>
</html>
```
## Hasil:


![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/SSJS2.png)

#
## Array
memiliki fungsi untuk menyimpan data secara bersamaan

```html

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript const</h2>

<p>Declaring a constant array does NOT make the elements unchangeable:</p>

<p id="demo"></p>

<script>
// Create an Array:
const cars = ["Saab", "Volvo", "BMW"];

// Change an element:
cars[0] = "Toyota";

// Add an element:
cars.push("Audi");

// Display the Array:
document.getElementById("demo").innerHTML = cars; 
</script>

</body>
</html>

```
## Hasil:

 ![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/SSJS3.png)

 #
 ## Function 
 - function memiliki arti sebagai fungsi, jadi tugas function yaitu menyeleasikan pekerjaan



```html

   <!DOCTYPE html>
<html>
  <body>
    <h1>JavaScript Functions</h1>

    <p>Call a function which performs a calculation and returns the result:</p>

    <p id="demo"></p>

    <script>
      function myFunction(p1, p2) {
        return p1 * p2;
      }

      let result = myFunction(4, 3);
      document.getElementById("demo").innerHTML = result;
    </script>
  </body>
</html>

```
## Hasil:

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/SSJS4.png)

#
## Contoh Pelaksanaan
Berikut merupakan contoh pelaksanaanya

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Challenge Live Code - JS</title>
</head>
<style>
    h1{
        text-align: center;
    }
  .content {
    font-family: Arial, Helvetica, sans-serif;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  table, tr, th, td {
      border: solid 1px grey;
      border-collapse: collapse;
  } 

  th, td { 
      padding: 10px;
  }


  tr first-child, tr:nth-child(even) {
    background-color: lightgray;
  }

  tr:hover {
    background-color: gray;
  }
  img {
      width: 200px;
      height: 150px;
    border-collapse: collapse;
  }

  button {
    margin-top: 10px;
  }
</style>
  

<body>
  <h1 font-family:Arial >JavaScript Arithmatic</h1>
  <div class="content">
    <table border="1">
      <tr>
        <th>Variabel</th>
        <th>Nilai</th>
        <th rowspan="4"><img id="gambar" src="https://www.techfor.id/wp-content/uploads/2019/12/html.png"</th>
      </tr>
      <tr>
        <td>a</td>
        <td id="nilai_a">5</td>
      </tr>
      <tr>
        <td>b</td>
        <td id="nilai_b">2</td>
      </tr>
      <tr>
        <td>c</td>
        <td id="nilai_c">1</td>
      </tr>
      <tr>
        <td>Hasil</td>
        <td id="hasil" onmouseover="tampil()" onmouseleave="hilang()"></td>
      </tr>
    </table>
    <button onclick="ubahnilai()">Ubah Nilai</button> 
  </div>

  <script>
    function hitung(a, b, c) {
      return a + b - c;
    }

    function tampil() {
      a = parseInt(document.getElementById("nilai_a").innerHTML);
      b = parseInt(document.getElementById("nilai_b").innerHTML);
      c = parseInt(document.getElementById("nilai_c").innerHTML);
      hasil = hitung(a, b, c)
      document.getElementById("hasil").innerHTML = hasil;
    }
    function hilang() {
      document.getElementById("hasil").innerHTML = "";
    }
    function ubahnilai(){
       ubah1 = prompt("masukan nilai 'A'");
      document.getElementById("nilai_a").innerHTML = ubah1
       ubah2 = prompt("masukan nilai 'B'");
      document.getElementById("nilai_b").innerHTML = ubah2
       ubah3 = prompt("masukan nilai 'C'");
      document.getElementById("nilai_c").innerHTML = ubah3
    
    document.getElementById("gambar")
    .src = "https://cdn.pixabay.com/photo/2015/04/23/17/41/javascript-736400_1280.png";
    }
  </script>
</body>

</html>
```
## Hasil:

![App Screenshot](https://github.com/NalindraDT/pemrogamanweb1/blob/main/jpg/SSJS5.png)








  



