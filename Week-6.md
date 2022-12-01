# Writing Week 6

## React JS
- React JS adalah pustaka atau library Javascript yang dimanfaatkan untuk membuat desain interface website. Bisa dibilang, React JS seperti perpustakaan yang menyimpan kode-kode Javascript.

## Kenapa harus menggunakan React JS
- Membuat aplikasi front end menjadi lebih cepat walaupun harus menghandle berbagai data.
- React js membagi 1 tampilan pada web menjadi komponen2 kecil
- Dapat digunakan pada aplikasi berskala kecil hingga besar dan kompleks
- Komunitas react sangat luas

## Cara menginstall React JS
- Install Node JS
  - download pada laman nodejs.org
  - install lts version
  - lalu instal seperti biasa
  - Jika sudah terinstal, kita bisa cek melalui git bash
- Install React JS (Use library create-react-app)
  - npx (npx create-react-app my-app)
  - npm (npm init react-app my-app)
  - yarn (yarn create react-app my-app)

## Component
- React Component
React Component adalah sebuah fungsi atau kelas yang mengembalikan kode JSX. React Component memungkinkan kita untuk memisahkan kode JSX menjadi beberapa bagian yang lebih kecil. React Component memungkinkan kita untuk membuat komponen-komponen yang dapat digunakan kembali.
- State & Props
State & Props adalah hal yang berhubungan dengan Stateless & Stateful Component. Stateless hanya memiliki props, stateful memiliki state. Jadi state adalah data local. Props digunakan agar component memiliki data yang dinamis dari component lain.
- Lifecycle
Lifecycle method pada React.js adalah method yang akan dijalankan pada saat tertentu. Life cycle method pada React.js adalah method yang akan dijalankan pada saat mounting, unmounting dan updating. Lifecycle method pada React.js adalah method yang akan dijalankan pada saat mounting yaitu constructor, getDerivedStateFromProps, render, componentDidMount, dan getSnapshotBeforeUpdate. Lifecycle method pada React.js adalah method yang akan dijalankan pada saat unmounting yaitu componentWillUnmount. Lifecycle method pada React.js adalah method yang akan dijalankan pada saat updating yaitu getDerivedStateFromProps, shouldComponentUpdate, render, getSnapshotBeforeUpdate, dan componentDidUpdate.
- Hooks
Berfungsi untuk memudahkan penggunaan functional components agar bisa menggunakan state dan lifecycle lainnya Dengan pengguanan hooks, state (setState) dan lifecycle (componentDidMount, componentDidUpdate) dapat digunakan pada functional component Functional component akan melakukan hooks terhadap hal hal yang hanya ada di class agar dapat digunakan oleh functional component dengan mudah.
