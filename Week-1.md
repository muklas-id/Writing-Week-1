# Writing-Week-1

## Unix Command Line
* ### Shell
Program yang menerima perintah, kemudian meneruskan perintah tersebut ke system untuk dieksekusi.
* ### Command Line Interface
Shell yang berbasis teks.
* ### Cara mengakses CLI
Cara mengakses CLI adalah memlalui terminal yaitu tempat/aplikasi dimana user dapat mengetikan atau memberikan suatu perintah.
&nbsp;
Untuk windows kita dapat mengaksesnya menggunakan command prompt
* ### File System Structure
Sebuah filesystem mengatur bagaimana data disimpan di dalam sebuah system
&nbsp;
Sistem operasi Windows & Unix-like menyusun file dan direktori menggunakan struktur yang bentuknya mirip tree
* ### Command
  - pwd (print working directory), untuk melihat current working directory
  - dir (directory), untuk melihat isi sebuah directory
  - cd (change directory), untuk pindah directory
  - ls (list), untuk melihat isi file di dalam directory
  - touch, untuk membuat file directory
  - cp (copy), untuk menyalin file directory
  - mv (move), untuk memindahkan file directory
  - rm (remove), untuk menghapus file directory

## Git & GitHub Dasar
* ### Git
Merupakan aplikasi yang dapat melacaks suatu perubahan yang terjadi di suatu folder ataupun file, yang biasanya digunakan oleh programmer sebagai tempat untuk menyimpan file programan mereka karena lebih efektif.
* ### GitHub
Merupakan vendor penyedia layanan git yang dimiliki oleh microsoft atau secara definisi merupakan layanan hosting berbasis web sebagai repositori git.
* ### kenapa Git dan Github tools yang wajib digunakan
epandai apapun programmer, tidak akan mampu untuk mengerjakan semuanya sendiri selamanya. Maka dari itu dengan menggunakan Git & Github akan memudahkan programmer untuk bisa bekerja sama dalam sebuah tim. Tujuan besarnya adalah programmer bisa berkolaborasi dengan programmer lainnya.
* ### Command di dalam Git & Github
  - git init <nama_proyek>, untuk membuat repositori baru
  - git commit, untuk melakukan commit atau menyimpan perubahan pada version control pada git. Dan kita bisa menambahkan pesan untuk membeikan checkout pada setiap perbuahan. contohnya "git commit -m "pesan checkout"
  - git push origin, untuk mempublish file atau aplikasi ke github
  - git clone, untuk melakukan cloning dari github ke komputer atau local

## HTML
* ### peran HTML pada web development
Secara umum, fungsi HTML adalah untuk mengelola serangkaian data dan informasi sehingga suatu dokumen dapat diakses dan ditampilkan di Internet melalui layanan web.
### tools pendukung dalam menggunakan HTML
banyak tools pendukung dalam menggunakan HTML, saya menggunakan Visual Studio Code
* ### tag HTML yang populer
Image
```html
<img src="image.jpg" alt="image">
```
Video
```html
<video controls>
  <source src="video.mp4" type="video/mp4">
</video>
```
Tabel
* ### semantic HTML
Semantic HTML yaitu menggunakan elemen HTML sesuai dengan kebutuhan konten. Contoh yaitu header, footer, nav, section, aside, dll.
* ### deployment
Deploy adalah sebuah proses untuk menyebarkan aplikasi yang sudah kita kerjakan supaya bisa digunakan oleh orang-orang. Jika aplikasi kita HTML atau Web App kita perlu mendeploy ke server. Untuk melakukan hal tersebut kita bisa menggunakan layanan yang bernama Netlify.

## CSS
* ### Apa itu CSS
CSS adalah sebuah bahasa yang digunakan untuk mendesain halaman website. Dengan CSS kita dapat kita bisa mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dan lainnya.
* ### Mengguanakan CSS
Ada 3 cara bagaimana kita dapat menggunakan CSS tersebut yang pertama yaitu Inline Styles, Internal, dan Eksternal.
* ### CSS Syntax
CSS Syntax adalah syntax yang digunakan untuk menunjuk atau memilih HTML element mana yang ingin diberi style (dihias). CSS syntax terdiri dari selector, property, dan value.

## Algoritma dan Struktur Data
* ### Algoritma
Algortima Adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah. Untuk menyelesaikan suatu masalah, tentunya kita harus mempunyai data struktur, nah data inilah yang akan kita gunakan untuk menyelesaikan suatu masalah dengan menggunakan algoritma.
* ### Mengapa kita memerlukan algoritma?
Manfaat algoritma antara lain:
  - Membantu menyederhanakan suatu program yang rumit dan juga besar.
  - Mempermudah pembuatan program yang dapat menyelesaikan masalah tertentu.
  - Membantu menyelesaikan suatu masalah dengan logika dan juga sistematis.
* ### Kualitas Algortima
Kualitas wajib dari algoritma
  - Input dan output harus didefinisikan terlebih dahulu dengan tepat
  - Setiap step harus benar-benar clear dan tidak ambigu
  - Algoritma seharusnya tidak mengandung suatu code pada bahasa pemograman tertentu.
  - Algoritma harus dibuat agar dapat digunakan dalam bahasa pemograman apapun.
* ### Penggunaan Algoritma
* ### Pseudocode
Pseudocode adalah menuliskan algoritma sebelum kita implementasikan ke bahasa pemograman tertentu.
* ### Bagaimana menulis pseudocode
  - Menggunakan HURUF BESAR pada kata kunci (key commands).
CONTOH: IF number is > 10 THEN …
  - 1 statement = 1 baris
  - Gunakan indentasi
  - Simpel

## Introduction to JavaScript
* ### Apa Itu JavaScript
Bahasa Pemrograman yang digunakan untuk logic pada sebuah website. Dengan menggunakan JavaScript, dapat membuat website menjadi interaktif dan dinamis.

* ### Menjalankan JavaScript
Dapat dilakukan melalui browser (Chrome, Mozila Firefox, Microsoft Edge, Opera, dll)

* ### Tipe Data dalam JavaScript
Merupakan pengelompokan yang diberikan untuk berbagai macam data dalam yang digunakan dalam programming. Terdapat 6 Tipe data dasar dalam JavaScript, yaitu :
  - Number -> tipe data yang memuat angka termasuk angka desimal
  - String -> grup karakter yang ada pada keyboard laptop/PC kita yaitu letters (huruf), number (angka), spaces (spasi), symbol, dan lainnya. Harus diawali dan diakhiri dengan single quotes ‘ … ‘ ataupun double quotes “ … “.
  - Boolean -> hanya mempunyai 2 nilai (true/false)
  - Null -> mengartikan bahwa sebuah variable/data tidak memiliki nilai
  - Undefined -> mengartikan variable/data tidak memiliki nilai
  - Object -> tipe data object adalah koleksi data yang saling berhubungan (related). Tipe data pbject dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya). Tipe data object mempunyai key dan value.

* ### Operator pada Java Script
* Arithmetic Operator
Arithmetic operator adalah operator yang melibatkan operasi matematika.
  - Tambah (+)
  - Kuramg (-)
  - Perkalian (*)
  - Pembagian (/)
  - Modulus (%)
* Comparison Operator
Comparison operator adalah operator yang membandingkan satu nilai dengan nilai lainnya.
  - Lebih kecil dari (<)
  - Lebih besar dari (>)
  - Lebih kecil atau sama dengan (<=)
  - Lebih besar atau sama dengan (>=)
  - Sama dengan (===)
  - Tidak sama dengan (!==)
* Logical Operator
Logical operator biasa digunakan untuk sebuah CONDITIONAL pada pemograman.
  - AND operator (&&)
  - OR operator (||)
  - NOT operator (!)

* ### Control Flow
* Conditional
  - if else
  - switch case
* Looping
  - for
  - while
  - do while
