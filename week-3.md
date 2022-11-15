# Writing Week 3

## JavaScript

### Array
* Array adalah tipe data list order yang dapat menyimpan tipe data apapun di dalamnya.
* Array dapat menyimpan tipe data String, Number, Boolean, dan lainnya.

### Cara mengakses array
Array pada JavaScript dimulai dari Index ke - 0. Jadi data pertama memiliki index-0
```Javascript
let kota = ["Jakarta", "Surabaya", "Malang"];
console.log(buku);
```

### Cara mengupdate array
```Javascript
let kota = ["Jakarta", "Surabaya", "Malang"];
kota[1] = "Blitar";
console.log(buku);

Output = ["Jakarta", "Blitar", "Malang"];
```

### Cons pada array
Jika menggunakan let, kita dapat mengubah array dengan array baru dan konten nilai yang ada di dalam array dengan nilai lain. tetapi const tidak bisa melakukan update data. Namun pada Array kita dapat melakukan update konten nilai di dalam array.
```Javascript
cons kota = ["Jakarta", "Surabaya", "Malang"];
kota[1] = [Blitar];
console.log(buku);

Output = Error
```

### Array propeties
Properties adalah fitur yang sudah disediakan oleh Javascript untuk memudahkan developer. Salahsatunya yaitu length. length akan mengembalikan nilai dari jumlah panjang data suatu array.
contoh :
```JavaScript 
cons kota = ["Jakarta", "Surabaya", "Malang"];
console.log(kota.length)

Output : 3
```

### Array Method
Array memiliki method atau biasa disebut built-in methods. Artinya Javascript sudah memudahkan kita dengan menyediakan function/method umum yang bisa kita gunakan. Kita tidak perlu membuat function lagi jika method yang kita butuhkan sudah tersedia.
Contoh Array Built-in Methods :
* push : Method untuk menambahkan item array pada urutan yang paling akhir.
* pop : Method yang menghapus item array index terakhir.
* shift : Method untuk menghapus item Array pada index pertama
* unshift : Method untuk menambahkan item Array pada index pertama
* sort : Method untuk mengurutkan secara Ascending atau Descending Alphanumeric

### Array looping
Array memiliki built in methods untuk melakukan looping yaitu .map() dan .forEach()

### Array multidimensi
Multidimensional Array bisa dianalogikan dengan array of array. Ada array didalam array.

### Javascript Object
object adalah sebuah tipe data pada variabel yang menyimpan properti dan fungsi (method). 
Properti adalah data lengkap dari sebuah object. 
Method adalah action dari sebuah object. Apa saja yang dapat dilakukan dari suatu object.

### Membuat sebuah object
Sama seperti tipe data sebelumnya. Object dapat diassign kedalam sebuah variabel.
```Javascript
let siswa = {
 nama : 'Muklas',
 umur : 21,
 asal : 'Malang',
 }
```

### Mengakses Object dan Property Object
Cara akses object Dalam mengakses object terdapat 2 cara yaitu menggunakan dot notation dan bracket.
* dot notation, misalnya console.log(siswa.nama);
* bracket, misalnya console.log(siswa['nama']);

### Method
Method adalah ketika ingin menambahkan sebuah function. Ada 2 method dalam object, yaitu :
* const greeting
* nested object

### Array of object
array yang menyimpan banyak object sebagai nilainya.

### Recursive dan Modules
* Rekursif function atau algoritma yang memanggil dirinya sendiri sampai kondisi tertentu. Rekrusif ini mirip seperti looping. Misalnya pada gambar ada gambar di dalam gambar. Terdapat 2 kunci pada rekrusif,yaitu base case atau titik berhenti dan recrusion case atau titik memanggil function.
* Modules cara untuk memisahkan kode ke file yang berbeda. Keuntungan dari modules yaitu mudah untuk mengelola kode serta kode tidak menumpuk di dalam satu file. Terdapat 2 kata kunci pada modules yaitu export dan import.

### Asyncronus
Merupakan sebuah proses yang dilakukan secara tidak berurutan. Jika proses terlalu panjang, akan diselat oleh proses yang lebih singkat. Secara umum, bahasa pemrograman berjalan secara synchronous. JS memiliki kelebihan dapat menjalankan sebuah proses tanpa harus berurutan.

Kunci Utama dalam Asynchronus
* CallBack merupakan sebuah function yang dijadikan argumen. Ketika sesuatu memerlukan waktu yang lama, maka dia akan masuk kedalam callback queue lalu menjalankan proses yang berada di belakangnya. Jika proses yg belakang sudah selesai, maka engine akan memeriksa yang ada didalam callback queue untuk dijalankan. Console.log(“A”) setTimeout( () => { Console.log(“B”) }, 1000) Console.log(“C”) //Output : //A //C //B
* Promises Kejadian yang telah selesai atau gagal dalam operasi asynchronous yang menghasilkan nilai. Saat on progress progress dalam fase pending. Jika gagal maka status asynchronous menjadi rejected. Jika kejadian dari event asynchronous telah berhasil, maka status fulfilled.

### Web Storage
Ada beberapa cara untuk menyimpan data pengguna seperti pencarian, artikel berita, dan lain-lain ke lokal (browser) menggunakan web storage seperti cookies, local storage, dan session storage. Data ini dimanfaatkan oleh situs web tersebut untuk merekam kebiasaan pengguna agar dapat memberikan rekomendasi sesuai preferensi si pengguna tersebut.

### Cookies
Cookies adalah data kecil yang dikirim dari situs web dan disimpan di komputer kita oleh web browser saat kita menjelajah. Disebut data kecil karena maksimum data yang dapat disimpan dalam cookies adalah 4096 bytes (4 KB). Biasanya data yang disimpan di cookies adalah access token pengguna saat login atau data pencarian saat melakukan pencarian pada situs web tertentu. Hal ini yang biasanya dilakukan oleh situs pencarian untuk melacak pencarian kita dan menampilkan iklan yang berhubungan dengan pencarian kita sebelumnnya.
Namun ada beberapa kekurangan yang perlu kita perhatikan mengenai cookies di antaranya:

* Setiap kita mengakses situs web, cookies juga kembali dikirim sehingga memperlambat aplikasi web kamu dengan mengirimkan data yang sama.
* Cookies disertakan pada setiap HTTP request, sehingga mengirimkan data yang tidak dienkripsi melalui internet, maka saat kita ingin menyimpan data dalam cookies kita harus mengenkripsinya terlebih dahulu.
* Cookies hanya dapat menyimpan data sebanyak 4KB.
* Lalu cookies juga memiliki tanggal kadaluarsa. Tanggal ini telah ditentukan sehingga web browser bisa menghapus cookies jika tanggal sudah kadaluarsa atau tidak dibutuhkan. Kita dapat memanfaatkan jenis web storage yang lain untuk mengatasi kekurangan yang dimiliki cookies.

### Local Storage
Berbeda dengan local storage, walaupun masuk ke dalam web storage, data yang tersimpan pada session storage akan hilang ketika session dari sebuah laman berakhir.
Karakteristik Local Storage:

* Menyimpan data tanpa tanggal kadaluarsa.
* Data tidak akan dihapus ketika web browser ditutup dan akan tersedia seterusnya selama kita tidak menghapus data local storage pada web browser.
* Dapat menyimpan data hingga 5MB.
* Hanya dapat menyimpan data string.

### Mengakses Local Storage & Session Storage
- Local Storage
* Menyimpan Data Untuk menyimpan data pada local storage, kita menggunakan method setItem() yang membutuhkan 2 parameter. Parameter pertama adalah key yang ingin kita simpan dan parameter kedua adalah data (value) dari key yang akan disimpan.
* Mengambil Data Untuk mengambil data yang telah tersimpan pada local storage, kita dapat menggunakan method getItem() yang membutuhkan 1 parameter. Parameter tersebut adalah key dari data yang kita inginkan.
* Menghapus Data Untuk menghapus data yang telah tersimpan pada local storage, kita dapat menggunakan method removeItem() yang membutuhkan 1 parameter. Parameter tersebut adalah key dari data yang ingin kita hapus.

- Session Storage
* Menyimpan Data Sama dengan local storage
* Mengambil Data Sama seperti local storage, cara mendapatkan data dari session storage juga menggunakan getItem(),
* Menghapus Data Syntax untuk menghapus data dari session storage ada 2, yaitu: sessionStorage.removeItem('key'); dan sessionStorage.clear();


