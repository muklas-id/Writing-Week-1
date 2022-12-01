# Writing Week 7

## PropTypes
PropTypes merupakan library untuk menvalidasi props. Ini sangat membantu dalam meminimalkan bugs saat mengembangkan App besar. Jika props tidak benar type nya maka akan muncul warning.

## React Router
React Router adalah sistem perpustakaan standar yang dibangun di atas React dan digunakan untuk membuat perutean di aplikasi React menggunakan Paket React Router. Ini menyediakan URL sinkron di browser dengan data yang akan ditampilkan di halaman web. Ini memelihara struktur standar dan perilaku aplikasi dan terutama digunakan untuk mengembangkan aplikasi web satu halaman.

## React Redux
- Redux merupakan salah satu state manajement yang sangat populer digunakan di reactjs. Namun redux sebenarnya berdiri sendiri atau tidak tergantung pada react itu sendiri.

- Cara kerja Redux :
  - Action : Adalah sebuah function yang mereturn sebuah objek.
  - Reducer : sebuah fungsi yang tugasnya untuk mengolah state yang ada di store.
  - Store : tempat untuk menampung state

## Async Actions with Middleware and Thunk
- Redux Thunk adalah middleware yang memungkinkan memanggil pembuat aksi yang mengembalikan fungsi sebagai ganti objek aksi. Fungsi itu menerima metode pengiriman penyimpanan, yang kemudian digunakan untuk mengirim aksi sinkron di dalam isi fungsi setelah operasi asinkron selesai.
- Cara Penggunaan :
  - Instal (npm install redux-thunk)
  - Update Redux store agar dapat menggunakan middleware (import thunk from 'redux-thunk')
  - import applyMiddleware (import { createStore, applyMiddleware } from 'redux';)
