# Writing Week 4

## Asynchronous - Async Await

- Async await
Merupakan cara lain untuk menangkap objek promise. Fitur ini mempermudah kita dalam menangani proses asynchronous.Async/Await merupakan sebuah syntax khusus yang digunakan untuk menangani Promise agar penulisan code lebih efisien dan rapih.
- Fetch
Fetch gunakan untuk mengambil data dan menampilkan data ke browser. Berfungsi untuk web dinamis yang datanya selalu berubah. Berikut merupakan ilustrasi mengenai fetch data API

## Git & Github Lanjutan

- Inviting collaborators to a personal repository
1. Menuju halaman navigasikan ke halaman utama repositori.
2. Click Setting
3. Kemudian pilih Access collaborators
4. Click Invite a collaborator.
5. Setelah itu ketik nama orang yang ingin Anda undang, lalu klik nama di daftar kecocokan.
6. Click Add NAME to REPOSITORY.
7. Pengguna akan menerima email yang mengundang mereka ke repositori. Setelah mereka menerima undangan Anda, mereka akan memiliki akses kolaborator ke repositori Anda.
- Maintaining ownership continuity of your personal account's repositories
1. Klik foto profil Anda dan pilih Settings,
2. Setelah itu click Account,
3. Pilih "Successor settings", untuk mengundang username, nama lengkap, atau alamat email, lalu klik namanya saat muncul,
4. Setelah muncul kemudian Click Add successor.
5. Jika diminta konfirmasikan akses ke akun Anda di GitHub. Untuk informasi lebih lanjut anda bisa mengisinya sendiri,
6. Pengguna yang Anda undang akan terdaftar sebagai "Pending" sampai mereka setuju untuk menjadi successor Anda.

## Responsive Web Design

- Responsive web design atau desain web responsif adalah sebuah teknik atau metode bagi web designer untuk membuat suatu layout website yang dapat menyesuaikan diri sesuai dengan ukuran layar pengguna. Baik dari ukuran huruf, user interface, gambar dan tata letak akan menyesuaikan dengan lebar layar dan resolusi device yang digunakan. 
1.  Menggunakan viewport
    Viewport : area website yang dapat diakses oleh user <br>
    Setting viewport : Otomatis keluar saat menggunakan html dengan cara ketikan ! kemudian enter. Atau <br>
    `<meta name="viewport">`
2. Menggunakan Max-Width element
   misalnya menjadikan gambar lebih responsif
   ```HTML
   <img scr=" " alt style="max-width:100%" />
   ```
3. Menggunakan CSS relative unit
   relative length : em, rem, vw, vh, % (yg sering dipakai)
   - em : mengikuti ukuran huruf dari element dia berada. Nyari font size dengan parent element terdekat. Contoh : container dengan em nya
   - rem : mengikuti ukuran huruf dari root element (ukuran huruf html). Biasanya ukuran default html adalah 16px. Jadi 2rem = 2 x 16px = 32px
   - % : bergantung pada parent element
   - Vw : relatife 1% dengan lebar viewport.. 50vw = 50% dari lebar viewport
   - Vh : relatife 1% dengan tinggi viewport. 50vh = 50% dari tinggi viewport
4. Membuat beberapa style bergantung pada jenis device
   Kata kunci : @media. Contoh :
   ``` CSS
       @media (max-width: 500px) {
       }
   ```
   Jika ukuran layar dibawah 500px maka style settingan didalam @media yang berlaku
5. Menggunakan Flexbox dan Grid
   Flexbox, Satu arah entah samping(kanan-kiri) atau atas bawah
   Grid, Bisa kearah samping dan atas bawah
   
## Boostrap

- Bootstrap adalah framework HTML, CSS, dan JavaScript yang berfungsi untuk mendesain website responsive dengan cepat dan mudah.

1. Breakpoint : sebagai acuan untuk menyesuaikan tampilan dalam berbagai ukuran viewport. Beberapa breakpoint pada bootstrap 5 sm, md, lg, xl, xxl
2. Containers : layout basicnya bootstrap
   - Default Container
     Class container memiliki sifat yang responsive dan fixed-width, yang berarti lebarnya akan berubah pada setiap breakpoint
     ```HTML
        <div class="container">
        <!-- Content here -->
        </div>
     ```
   - Fluid Container
     Class container-fluid memiliki lebar yang sama dengan viewport
     ```HTML
        <div class="container-fluid">
        <!-- Content here -->
        </div>
     ```
   - Responsive Container
     ```HTML
        <div class="container-sm">100% wide until small breakpoint</div>
        <div class="container-md">100% wide until medium breakpoint</div>
        <div class="container-lg">100% wide until large breakpoint</div>
        <div class="container-xl">100% wide until extra large breakpoint</div>
        <div class="container-xxl">100% wide until extra extra large breakpoint</div>
     ```
3. Grid
   Grid system membagi lebar halaman menjadi 12 bagian. Sehingga apabila menggunakan class col-8, maka lebarnya akan menjadi 8/12 atau 2/3 dari lebar halaman.
4. Column 
   mengatur urutan posisi dan align Component pada bootstrap : 
   - Alerts
   - Breadcrumb
   - Buttons
   - Card
   - Modal
   - Navbar
   - Navs & tabs
   - Pagination <br>
   Content pada bootstrap
   - Reboot
   - Typography
   - Images
   - Tables
   - Figures
