# Kumaha_Atuh_Ieu

# 1. Ketentuan Umum

Berikut adalah ketentuan umum dalam mengerjakan Mini Project:

1. Proyek harus dikerjakan dengan penggunaan AI Level-2, yaitu Anda berhak menggunakan AI untuk berdiskusi dalam merencanakan pengerjaan proyek:
   - Anda TIDAK diperkenankan untuk mengikutsertakan artefak apa pun, termasuk kode program, yang dihasilkan AI.
   - Anda WAJIB dapat menjelaskan segala analisis dan desain yang Anda hasilkan, baik dalam bentuk artefak maupun kode program.
   - Anda WAJIB dapat menjelaskan segala kode program yang Anda hasilkan.

2. Anda TIDAK diperkenankan menggunakan library atau framework apa pun pada server-side, kecuali yang secara langsung tersedia pada Node.js. Pengecualian berlaku jika library atau framework hanya digunakan dalam pengaksesan basis data.

3. Anda TIDAK diperkenankan menggunakan library atau framework apa pun dalam membangun frontend dari aplikasi Anda.

4. Anda diperkenankan menggunakan basis data apa pun, misalnya SQLite3 atau PostgreSQL.

5. Tampilan dari aplikasi tidak dinilai. Hal yang menjadi penilaian hanyalah fungsionalitas aplikasi.

6. Aplikasi WAJIB menggunakan HTTPS untuk mengakses reverse proxy dengan certificate yang valid dan memiliki certificate authority yang dipercaya oleh web browser yang digunakan. Komunikasi dari reverse proxy ke server yang berisikan konten harus menggunakan HTTP.

7. Aspek efisiensi (misalnya kompresi) dan keamanan (misalnya cookies) juga akan menjadi poin penilaian.

# 2. Topik 1

Berikut adalah rincian untuk Topik 1:

1. Anda diminta untuk membuat sebuah aplikasi yang memiliki minimal 3 halaman.

2. Aplikasi harus terdiri dari dua buah server, yang masing-masing server berisi konten yang sama tetapi menggunakan bahasa yang berbeda. Masing-masing server memiliki 3 halaman berisi konten yang sama dengan bahasa yang berbeda.

3. Pengguna wajib diminta untuk memilih bahasa oleh sebuah reverse proxy, dan pilihan pengguna akan disimpan di dalam cookies. Selanjutnya, reverse proxy harus memastikan bahwa pengguna terhubung dan berkomunikasi dengan server yang tepat, sesuai dengan pilihan bahasa yang dipilih pengguna.

4. Semua komunikasi pengguna dengan server yang berisikan konten WAJIB melalui reverse proxy.

5. Setiap server konten wajib memiliki fitur yang memungkinkan pengguna untuk mengubah preferensi bahasa. Namun, jika pengguna belum memiliki preferensi bahasa, pemilihan preferensi ini harus dilakukan pada reverse proxy.

6. Anda diperkenankan menggunakan AI atau aplikasi translator untuk mengubah konten dari suatu bahasa ke bahasa asing.

7. Setiap halaman wajib memiliki minimal satu gambar.
