![image.png](https://imgur.com/IdJZ8HQ )



### Cara Membuat Order List
Ordered list dibuat dengan tag <ol>. Lalu di dalamnya diisi dengan item-item yang akan dimasukkan ke dalam list. Item dibuat dengan tag <li> (list item).
Digunakan untuk membuat daftar dimana tiap bagiannya ditandai
dengan sebuah simbol.

Tag: <ul> ... </ul>

Contoh:
##<ol>
##<li>Jaringan Komputer</li>
##<li>Sistem Multimedia</li>
##<li>Basis Data</li>
##<li>Sistem Operasi</li>
##</ol>


### Membuat Unorder List
Unordered list adalah list yang tak terurut yang menggunakan simbol-simbol pada item-nya. Unordered list dibuat dengan tag <ul> dan untuk item-nya dibuat juga dengan tag <li>.


##<ul>
##<li>Jaringan Komputer</li>
##<li>Sistem Multimedia</li>
##<li>Basis Data</li>
##<li>Sistem Operasi</li>
##</ul>



### Membuat Web Description List
Description List adalah list yang berisi deksripsi atau penjelasan dari sesuatu.

Ada tiga tag yang digunakan untuk membuat description list:

    <dl> (description list) tag untuk memulai description list;
    <dt> (description term) tag untuk membuat kata yang akan dideskripsikan;
    <dd> (description description) tag untuk membuat penjelasan dari kata.

Format penulisannya seperti ini:

###<section id="unorder-list">
        ###<h2>Description List</h2>
        ###<dl>
        ##<dt>Fakultas Teknik</dt>
        ##<dd>Teknik Industri</dd>
        ##<dd>Teknik Informatika</dd>
        ##<dd>Teknik Lingkungan</dd>
        ##<dt>Fakultas Ekonomi dan Bisnis</dt>
        ##<dd>Akuntansi</dd>
        ##<dd>Manajemen</dd>
        ##<dd>Bisnis Digital</dd>
        ##</dl>
        ##</section>



### Cara Membuat Tag tabel html
##Salah satu cara atau format menampilkan informasi dalam web adalah dengan tabel.

Tabel terdiri dari 4 unsur utama:

    Baris
    Kolom
    Sel
    Garis

   ## Ada beberapa tag yang harus diingat untuk membuat tabel di HTML:

    Tag <table> untuk membungkus tabelnya
    Tag <thead> untuk membungkus bagian kepala tabel
    Tag <tbody> untuk membungkus bagian body dari tabel
    Tag <tr> (tabel row) untuk membuat baris
    Tag <td> (table data) untuk membuat sel
    Tag <th> (table head) untuk membuat judul pada header

    Nilai "1" pada atribut border adalah ukuran garisnya. Semakin besar ukurannya, maka akan semakin besar pula ukuran garisnya.

    Nilai "1" adalah ukuran garis yang palng kecil.

    Atribut cellpadding adalah atribut untuk mengatur jarak teks dengan garis di dalam sel.

    Atribut ini dapat kita berikan kepada tag <table>


###Tag yang paling penting untuk diingat adalah tag <table>, <tr>, dan <td>. Sementara tag yang lain adalah tambahan (opsional), boleh digunakan boleh tidak


### <table border="1" cellpadding="4" cellspacing="0">
    <thead>
    <tr>
    <th>No.</th>
    <th>Fakultas</th>
    <th>Program Studi</th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td>1.</td>
    <td>Teknik</td>
    <td>Teknik Informatika</td>
    </tr>
    <tr>
    <td>2.</td>
    <td>Teknik</td>
    <td>Teknik Industri</td>
    </tr>
    <tr>
    <td>3.</td>
    <td>Teknik</td>
    <td>Teknik Lingkungan</td>
    </tr>
    </tbody>
    </table>


### table border="1" cellpadding="6" cellspacing="0">
    <thead>
    <tr>
    <th>No.</th>
    <th>Fakultas</th>
    <th>Program Studi</th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td>1.</td>
    <td rowspan="3">Teknik</td>
    <td>Teknik Informatika</td>
    </tr>
    <tr>
    <td>2.</td>
    <td>Teknik Industri</td>
    </tr>
    <tr>
    <td>3.</td>
    <td>Teknik Lingkungan</td>
    </tr>
    </tbody>
    </table>


### Cara Membuat Form tabel Html
Form di HTML dapat kita buat dengan tag <form>.

Tag ini memiliki beberapa atribut yang harus diberikan, seperti:

action untuk menentukan aksi yang akan dilakukan saat data dikirim
method metode pengiriman data.
Untuk atribut action, kita dapat mengisinya dengan alaman URL dari endpoint yang akan memproses form.

Secara sederhana,—pada contoh di atas— kita akan menyuruh file prosess.php untuk memproses data form
Field adalah ruas yang dapat diisi dengan data.

### Contoh field:<input type="text" name="info" />

### Pada kode di atas, kita membuat empat buah filed:

    input username dengan tipe text;
    input password dengan tipe password;
    input remember dengan tipe checkbox;
    input submit dengan tipe submit;

Lalu ketiga filed ini dibungkus ke dalam tag <fieldset>.

Nanti tag <fieldset> ini akan membuat sebuah garis.

Di dalam tag <fieldset>, kita membuat tag <legend> untuk memberikan teks pada fieldset.

Lalu, perhatikan juga atirbut yang digunakan pada setiap field.

    Atribut placeholder untuk menampilkan teks sementara (placeholder);
    Atribut value untuk membreikan nilai default pada field.

Setiap field kita bungkus dalam tag <p> agar terlihat rapi dan juga kita berikan sebuah label dengan tag <label>



























# LAB3_WEBB
