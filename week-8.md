# Writing Week 8

## React Context

- Context menyediakan cara untuk oper data melalui diagram komponen tanpa harus oper props secara manual di setiap tingkat.
- Dalam aplikasi React yang khusus, data dioper dari atas ke bawah (parent ke child) melalui props, tetapi ini bisa menjadi rumit untuk tipe props tertentu (mis. preferensi locale, tema UI) yang dibutuhkan oleh banyak komponen di dalam sebuah aplikasi. Context menyediakan cara untuk berbagi nilai seperti ini di antara komponen tanpa harus oper prop secara explisit melalui setiap tingkatan diagram.
- Sebelum Menggunakan Context
  - Context terutama digunakan ketika beberapa data harus dapat diakses oleh banyak komponen pada tingkat bersarang yang berbeda. Gunakan dengan hemat karena membuat penggunaan kembali komponen menjadi lebih sulit.
  - Jika Anda hanya ingin menghindari mengoper beberapa props melalui banyak tingkatan, komposisi komponen seringkali menjadi solusi yang lebih sederhana daripada context.
- Kapan Menggunakan Context
  - Context dirancang untuk berbagi data yang dapat dianggap “global” untuk diagram komponen React, seperti pengguna terotentikasi saat ini, tema, atau bahasa yang disukai.

## React Testing

- Testing pada react untuk memeriksa bahwa code sudah sesuai harapan

- Testing membantu memastikan dan mengetahui celah yang belum teratasi tetapi tidak menyelesaikan bug

- Selain itu, manfaat testing adalah
  - Meningkatkan stabilitas program jika testing terstruktur dengan baik
  - Software engineer dapat menyadari jika terjadi penuruan performa
  - Digunakan sebagai desain (TDD)
- Testing terbagi menjadi dua jenis, yaitu:
  - Manual testing (dilakukan manual dengan analisis manusia)
  - Automated testing (dilakukan dengan code) -> dibagi menjadi 3 :
    - unit tes = membuat komponen dari yang paling kecil seperti functionya bakal di test apakah sesuai ekspetasi kita atau tidak. Setiap buat code lakukan unit test
    - integration = Integration test: satu aplikasi terhubung ke system lain, contoh database
    - end to end = test yang dilihat dari sisi user (workflow dari awal sampai akhir)
