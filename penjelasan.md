# Penjelasan Kode HTML dan CSS

## HTML Tanpa CSS
Tanpa CSS, struktur HTML ini akan menampilkan elemen-elemen HTML secara berurutan secara vertikal, tanpa gaya atau tata letak khusus:

- **`<header>`**: Menampilkan judul "HTML5 Semantic" di bagian atas halaman.
- **`<nav>`**: Menyediakan menu navigasi dengan tiga tautan, yaitu "Home", "Pengertian", dan "Kesimpulan".
- **`<section>`**: Mengandung teks "Konten", yang berfungsi sebagai bagian utama isi halaman.
- **`<footer>`**: Menampilkan teks "Copyright" di bagian bawah halaman.

Semua elemen ini hanya akan berurutan dari atas ke bawah, tanpa adanya tata letak grid atau warna latar belakang.

---

## HTML Setelah Menggunakan CSS
Setelah menambahkan kode CSS, tampilan HTML akan lebih terstruktur dan estetik berkat penggunaan grid layout dan warna latar belakang yang ditentukan. Berikut adalah detail efeknya:

### 1. Grid Layout pada Body
   - **`grid-template-areas`** membuat tiga baris (header, bagian utama, dan footer) dengan tata letak yang diatur dalam tiga kolom.
   - **`grid-template-rows`** dan **`grid-template-columns`** mengatur ukuran masing-masing baris dan kolom sehingga memiliki proporsi yang berbeda.
   - **`grid-gap`** menambahkan jarak 5px di antara elemen grid.

### 2. Elemen Header
   - **Warna Latar Belakang**: Header memiliki warna abu-abu gelap (`#707070`).
   - **Penyelarasan Teks**: Judul diselaraskan ke tengah dengan `text-align: center`.

### 3. Elemen Navigasi
   - **Warna Latar Belakang**: Bagian navigasi diberi warna abu-abu muda (`#c9bfbf`).
   - **Penempatan di Grid**: Ditampilkan di kolom kiri grid.

### 4. Elemen Section
   - **Warna Latar Belakang**: Diberi warna abu-abu terang (`#ababab`).
   - **Penempatan di Grid**: Bagian konten berada di area tengah grid.

### 5. Elemen Footer
   - **Warna Latar Belakang**: Sama seperti header (`#707070`).
   - **Ukuran Font**: Ukuran font lebih kecil (`small`).
   - **Penyelarasan Teks**: Teks diselaraskan ke tengah.

Setelah CSS diterapkan, layout halaman akan tampak lebih rapi dan terorganisir dengan pembagian area yang jelas antara header, navigasi, konten, dan footer.
