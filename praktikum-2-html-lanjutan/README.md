# Web1Lab2: Laporan Praktikum 2 - HTML Lanjutan

Repositori ini berisi hasil pengerjaan Praktikum 2 mata kuliah Pemrograman Web mengenai penggunaan tag-tag HTML lanjutan, mencakup pembuatan tabel, formulir (form) beserta validasinya, elemen semantic HTML, integrasi media (audio & video), dan penggabungan seluruh materi ke dalam satu halaman web[cite: 1].

## Data Mahasiswa
- **Nama:** Nurfaiz Pradibto Nugroho
- **NIM:** 312510172
- **Kelas:** TI.25.C.3
- **Mata Kuliah:** Pemrograman Web
- **Program Studi:** Teknik Informatika
- **Instansi:** Universitas Pelita Bangsa

---

## Langkah-langkah Praktikum

Berikut adalah alur pengerjaan Praktikum 2 beserta rincian struktur kode dan tampilannya

### 1. Membuat Tabel Data Mahasiswa
Membuat tabel untuk menampilkan data nilai praktikum mahasiswa menggunakan tag `<table>` pada file `index.html`. Struktur tabel disusun menggunakan `<caption>`, `<thead>`, `<tbody>`, dan `<tfoot>`, serta menggunakan atribut `colspan="2"` untuk menampilkan rata-rata nilai.

![Kode Tabel Data Mahasiswa](/image/1.png)
![Hasil Tabel Data Mahasiswa](/image/2.png)

### 2. Membuat Form Mahasiswa
Membuat formulir registrasi dasar mahasiswa menggunakan tag `<form>`. Elemen input yang digunakan meliputi tipe `text` (Nama Lengkap), `email` (Email), `password` (Password), dan `date` (Tanggal Lahir), serta tombol `<button>` bertipe `submit` (Daftar) dan `reset`.

![Kode Form Mahasiswa](/image/3.png)
![Hasil Form Mahasiswa](/image/4.png)

### 3. Menambahkan Jenis Kelamin, Keahlian, & Validasi Form
Mengembangkan formulir registrasi dengan menambahkan elemen input lanjutan dan validasi bawaan HTML5:
- **Radio Button:** Menambahkan atribut `type="radio"` untuk pilihan Jenis Kelamin (`Laki-laki` / `Perempuan`).
- **Checkbox:** Menambahkan atribut `type="checkbox"` untuk pilihan Keahlian (`HTML`, `CSS`, `JavaScript`).
- **Input Umur & Textarea:** Menambahkan input tipe `number` untuk umur (dengan batasan `min="17"` dan `max="60"`), serta `<textarea>` untuk alamat.
- **Validasi HTML5:** Menerapkan atribut `required` dan `minlength="3"` pada elemen input untuk memastikan validasi data sebelum dikirim.

![Kode Jenis Kelamin & Keahlian](/image/5.png)
![Kode Validasi Form](/image/6.png)
![Hasil Form Lanjutan](/image/7.png)

### 4. Menambahkan Portal Mahasiswa (Semantic HTML)
Membuat halaman `index2.html` menggunakan elemen-elemen Semantic HTML untuk membangun struktur layout halaman yang lebih terorganisir. Elemen yang digunakan meliputi `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, dan `<footer>`.

![Kode Portal Mahasiswa](/image/8.png)
![Hasil Portal Mahasiswa](/image/9.png)

### 5. Menambahkan Media (Audio & Video)
Menyisipkan media interaktif berupa pemutar suara dan pemutar video ke dalam halaman web menggunakan elemen `<audio>` dan `<video>` yang dilengkapi dengan atribut `controls` serta pemanggilan berkas media (`media/audio.mp3` dan `media/video.mp4`).

![Kode Elemen Media](/image/10.png)
![Hasil Elemen Media](/image/11.png)

### 6. Menggabungkan Seluruh Materi (`index3.html`)
Mengintegrasikan seluruh konsep materi HTML lanjutan ke dalam satu halaman web terpadu (`index3.html`). Halaman ini berisi:
- **Header & Navigasi:** Menggunakan tautan navigasi internal (anchor link `#biodata` dan `#form`).
- **Tabel Biodata Mahasiswa:** Menampilkan data NIM, Nama, dan Program Studi.
- **Form Biodata:** Formulir pendaftaran interaktif dengan pilihan menu dropdown Program Studi (`<select>`), teks area alamat (`<textarea>`), serta tombol Simpan dan Reset.
- **Footer:** Menampilkan catatan hak cipta program studi.

![Kode Penggabungan Materi Part 1](/image/12.png)
![Kode Penggabungan Materi Part 2](/image/13.png)

---

### 7. Dokumentasi dan Commit ke GitHub
Memperbarui repositori GitHub **Web1Lab2** menggunakan Git Bash dengan alur perintah sebagai berikut:

```bash
# Masuk ke folder workspace praktikum
cd praktikum-2-html-lanjutan

# Memindahkan perubahan file ke staging area
git add .

# Melakukan commit perubahan
git commit -m "Update laporan Praktikum 2 - HTML Lanjutan"

# Memunculkan/mengunggah perubahan ke repositori GitHub
git push origin main