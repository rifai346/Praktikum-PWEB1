# Praktikum Pemrograman WEB1
Dalam praktikum pemrograman web kali ini, para mahasiswa mempelajari dasar-dasar pemrograman web seperti HTML (HyperText Markup Language), CSS (Cascading Style Sheets), dan JavaScript. 

## Yang digunakan
- HTML (HyperText Markup Langguange)
- CSS  (Cascading Style Sheets)
- JS (Javascript)

## HTML
HTML (HyperText Markup Language) adalah bahasa markup yang digunakan untuk membuat struktur dasar dari halaman web.
- HTML basic
  
Semua dokumen HTML harus dimulai dengan deklarasi tipe dokumen: `<!DOCTYPE html>`.
Dokumen HTML itu sendiri dimulai dengan `<html>`dan diakhiri dengan `</html>`.
Bagian yang terlihat dari dokumen HTML adalah antara `<body>` dan `</body>`.
``` sh
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

</body>
</html>
```
- ELEMENT HTML

Elemen HTML dapat disarangkan (artinya elemen dapat berisi elemen lain).
Semua dokumen HTML terdiri dari elemen HTML bersarang.
Contoh berikut berisi empat elemen HTML `( <html>, <body>, <h1> dan <p>):`

```SH
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
- ATRIBUTE HTML

Semua elemen HTML dapat memiliki atribut,
Atribut memberikan informasi tambahan tentang elemen,
Atribut selalu ditentukan di tag awal,
Atribut biasanya datang dalam pasangan nama/nilai seperti: name="value".
``` sh
<!DOCTYPE html>
<html lang="en">
<body>
    <a href="https://www.w3schools.com">Visit W3Schools</a>
    <img src="img_girl.jpg">
    <img src="img_girl.jpg" width="500" height="600">
    <p style="color:red;">This is a red paragraph.</p>
</body>
</html>
```
- HEADINGS HTML

Judul HTML ditentukan dengan tag `<h1>` to `<h6>`.
`<h1>` mendefinisikan judul yang paling penting. `<h6>` mendefinisikan judul yang paling tidak penting.

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/1aee05fd-b0a8-4561-b1bb-0d7d0654fb13)

- PARAGRAPHT HTML

Elemen HTML `<p>` mendefinisikan paragraf.
Sebuah paragraf selalu dimulai pada baris baru, dan browser secara otomatis menambahkan spasi (margin) sebelum dan sesudah paragraf.

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/87473d40-82aa-441a-8b2d-94e05a489e17)

- STYLE HTML

Atribut HTML styledigunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya.

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/9c22e654-8537-4859-ae8e-8b0673cc4921)

- FORMATTING HTML

Elemen pemformatan dirancang untuk menampilkan jenis teks khusus:

`<b>` Teks tebal,
`<strong>` Teks penting,
`<i>` Teks miring,
`<em>` Teks yang ditekankan,
`<mark>` Teks yang ditandai,
`<small>` Teks lebih kecil,
`<del>` Teks yang dihapus,
`<ins>` Teks yang disisipkan,
`<sub>` Teks subskrip,
`<sup>` Teks superskrip.

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/e7fb3201-9b04-43a4-b119-355a156de91c)

- QUOTATIONS HTML

  Dalam bab ini akan membahas elemen `<blockquote>`, `<q>`, `<abbr>`, `<address>`, `<cite>`, dan `<bdo>` HTML.

  ![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/476b63b4-0202-4590-9d9b-ea3e9bd844c8)

- COMMENT HTML

Komentar HTML tidak ditampilkan di browser, namun dapat membantu mendokumentasikan kode sumber HTML.
```SH
<p>This is a paragraph.</p>
<!--
<p>Look at this cool image:</p>
<img border="0" src="pic_trulli.jpg" alt="Trulli">
-->
<p>This is a paragraph too.</p>
```
- COLOR HTML

Warna HTML ditentukan dengan nama warna yang telah ditentukan sebelumnya, atau dengan nilai RGB, HEX, HSL, RGBA, atau HSLA.
![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/b26180fe-48ce-4f38-a418-436b4f2c3244)

- LINK HTML

Tautan HTML adalah hyperlink.
Anda dapat mengeklik tautan dan melompat ke dokumen lain.
Saat Anda menggerakkan mouse ke atas link, panah mouse akan berubah menjadi tangan kecil.

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/49cbcaf2-4ab1-4cff-af93-cd9cd0133148)
- IMAGE HTML
Tag HTML `<img>` digunakan untuk menyematkan gambar di halaman web.
Gambar secara teknis tidak dimasukkan ke dalam halaman web; gambar ditautkan ke halaman web. Tag `<img>` menciptakan ruang penahan untuk gambar yang direferensikan.
Tag `<img>` kosong, hanya berisi atribut, dan tidak memiliki tag penutup.

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/3a6ef518-5563-4523-9b34-5a7f1274cbe6)
- FAVICON HTML
Favicon adalah gambar kecil yang ditampilkan di sebelah judul halaman di tab browser.

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/0c105e6f-20b4-4bba-85c9-6e6d7f8ef069)
- TABLE HTML

Tabel HTML memungkinkan pengembang web untuk mengatur data ke dalam baris dan kolom. Setiap sel tabel ditentukan oleh a `<td>`dan `</td>`tag.
td singkatan dari data tabel.
Segala sesuatu di antara `<td>` dan `</td>`merupakan konten sel tabel. Setiap baris tabel dimulai dengan a `<tr>` dan diakhiri dengan `</tr>` tag. Terkadang Anda ingin sel Anda menjadi sel header tabel. Dalam kasus tersebut, gunakan `<th>` tag alih-alih `<td>` tag:

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/45ae5360-c8ce-429e-8f4f-c90f75d8a8d9)
- LIST HTML

Daftar HTML memungkinkan pengembang web mengelompokkan sekumpulan item terkait dalam daftar.
![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/b464e964-021f-4271-9711-f4bcbbc3ac4e)

- DIV HTML

Elemen ini <div>secara default adalah elemen blok, artinya elemen ini mengambil semua lebar yang tersedia, dan dilengkapi dengan jeda baris sebelum dan sesudahnya.

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/39861e49-282b-4faa-b8ac-772f3632bf4f)

- ATRIBUTE HTML

Atribut HTML classdigunakan untuk menentukan kelas elemen HTML.
Beberapa elemen HTML dapat berbagi kelas yang sama.
Menggunakan Atribut kelas
Atribut ini classsering digunakan untuk menunjuk ke nama kelas dalam style sheet. Itu juga dapat digunakan oleh JavaScript untuk mengakses dan memanipulasi elemen dengan nama kelas tertentu.
Pada contoh berikut kita memiliki tiga <div>elemen dengan classatribut dengan nilai "kota". Ketiga <div> elemen tersebut akan diberi gaya yang sama sesuai dengan .city definisi gaya di bagian kepala:

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/e3a32e2f-0502-46f7-a44d-43618b21404e)

- IFRAME HTML

Iframe HTML digunakan untuk menampilkan halaman web di dalam halaman web.

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/871c015f-3ce4-475f-9c56-b6c543025af4)

- RESPONSIVE HTML

Desain Web Responsif adalah tentang penggunaan HTML dan CSS untuk secara otomatis mengubah ukuran, menyembunyikan, mengecilkan, atau memperbesar situs web, agar terlihat bagus di semua perangkat (desktop, tablet, dan ponsel):

![image](https://github.com/rifai346/Praktikum-PWEB1/assets/151704215/6eaa6834-8432-4b75-9d23-ed70fadce378)

## CSS

CSS adalah bahasa yang DIgunakan untuk menata gaya dokumen HTML.
CSS menjelaskan bagaimana elemen HTML harus ditampilkan.

- CSS SYNTAX

Pemilih menunjuk ke elemen HTML yang ingin Anda gaya.
Blok deklarasi berisi satu atau lebih deklarasi yang dipisahkan oleh titik koma.
Setiap deklarasi menyertakan nama properti CSS dan nilainya, dipisahkan oleh titik dua.
Beberapa deklarasi CSS dipisahkan dengan titik koma, dan blok deklarasi diapit oleh kurung kurawal.

```sh
p {
  color: red;
  text-align: center;
} 
```
- CSS SELECTOR

Pemilih CSS digunakan untuk "menemukan" (atau memilih) elemen HTML yang ingin Anda gaya.

Kita dapat membagi pemilih CSS menjadi lima kategori:

Selector sederhana (pilih elemen berdasarkan nama, id, kelas),
Penyeleksi kombinator (memilih elemen berdasarkan hubungan tertentu di antara elemen tersebut),
Selector kelas semu (memilih elemen berdasarkan keadaan tertentu),
Pemilih elemen semu (memilih dan memberi gaya pada bagian elemen),
Pemilih atribut (memilih elemen berdasarkan atribut atau nilai atribut).

```sh
<!DOCTYPE html>
<html>
<head>
<style>
p {
  text-align: center;
  color: red;
} 
#para1 {
  text-align: center;
  color: red;
}
.center {
  text-align: center;
  color: red;
}
</style>
</head>
<body>

<p class="center">Every paragraph will be affected by the style.</p>
<p id="para1">Me too!</p>
<p>And me!</p>

</body>
</html>
```

- CSS COMENT

Komentar digunakan untuk menjelaskan kode, dan mungkin membantu ketika Anda mengedit kode sumber di kemudian hari.
Komentar diabaikan oleh browser.
Komentar CSS ditempatkan di dalam `<style>` elemen, dimulai `/*` dan diakhiri dengan `*/`.

``` sh
/* This is a single-line comment */
```

- CSS COLORS

Warna ditentukan menggunakan nama warna yang telah ditentukan sebelumnya, atau nilai RGB, HEX, HSL, RGBA, HSLA.


- CSS BACKGROUND

Properti latar belakang CSS digunakan untuk menambahkan efek latar belakang pada elemen.


- CSS BORDERS

Properti Border CSS memungkinkan Anda menentukan gaya, lebar, dan warna batas elemen.


- CSS MARGINS

Margin digunakan untuk menciptakan ruang di sekitar elemen, di luar batas yang ditentukan.


- CSS PADDING

Padding digunakan untuk menciptakan ruang di sekitar konten elemen, di dalam batas yang ditentukan.


- CSS HEIGHT DAN WIDTH

CSS `height` dan `width` properti digunakan untuk mengatur tinggi dan lebar suatu elemen.
Properti CSS `max-width` digunakan untuk mengatur lebar maksimum suatu elemen.


- CSS BOX MODEL

Dalam CSS, istilah "box model" digunakan ketika berbicara tentang desain dan tata letak.

box model CSS pada dasarnya adalah sebuah kotak yang membungkus setiap elemen HTML. Terdiri dari: konten, padding, batas dan margin.


- CSS OUTLINE

outline adalah garis yang digambar di luar batas elemen.


- CSS TEXT

CSS memiliki banyak properti untuk memformat teks.


- CSS FONT

Memilih font yang tepat memiliki dampak besar pada pengalaman pembaca terhadap situs web.
Font yang tepat dapat menciptakan identitas yang kuat untuk brand Anda.
Menggunakan font yang mudah dibaca itu penting. Font menambah nilai pada teks Anda. Penting juga untuk memilih warna dan ukuran teks yang tepat untuk font.


- 



















[def]: image.png