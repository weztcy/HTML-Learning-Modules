# Modul 4: List dan Pengelompokan Konten

## Ringkasan Ruang Lingkup Materi
Modul ini membahas konsep dasar dan implementasi praktis seputar **List dan Pengelompokan Konten**. Setiap submodul dirancang secara terisolasi agar pembelajar dapat memahami konsep satu per satu secara fokus dan terstruktur.

## Tujuan Pembelajaran Modul
Setelah menyelesaikan modul ini, peserta didik diharapkan mampu memahami, mengimplementasikan, dan menguji komponen-komponen utama dalam lingkup list dan pengelompokan konten sesuai standar modern W3C.

## Daftar Materi atau Submodul

- [51_unordered_list.html](51_unordered_list.html) - Unordered List
- [52_ordered_list.html](52_ordered_list.html) - Ordered List
- [53_list_item.html](53_list_item.html) - Elemen li
- [54_nested_list.html](54_nested_list.html) - Nested List
- [55_start_attribute.html](55_start_attribute.html) - Atribut start
- [56_reversed_list.html](56_reversed_list.html) - Atribut reversed
- [57_list_value.html](57_list_value.html) - Atribut value pada List Item
- [58_description_list.html](58_description_list.html) - Description List (dl)
- [59_description_term.html](59_description_term.html) - Elemen dt
- [60_description_details.html](60_description_details.html) - Elemen dd
- [61_mixed_list.html](61_mixed_list.html) - Kombinasi Berbagai Jenis List
- [62_navigation_list.html](62_navigation_list.html) - List untuk Navigasi

---

## Pembahasan Setiap Submodul

### 1. Unordered List

- **Tujuan Pembelajaran:** Membuat daftar butir tanpa nomor urut menggunakan tag <ul>.
- **Konsep Utama:** Elemen <ul> mengelompokkan item yang urutannya tidak mempengaruhi makna materi.
- **Penjelasan Source Code:** Menampilkan daftar keahlian frontend dengan simbol bullet bundar bawaan peramban.
- **Cara Menjalankan:** Buka file `51_unordered_list.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Daftar tiga butir materi bertanda bullet lingkaran hitam rapi.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Unordered List](output/51_unordered_list.png)

- **Lokasi Source Code:** [51_unordered_list.html](51_unordered_list.html)

---

### 2. Ordered List

- **Tujuan Pembelajaran:** Menguasai pembentukan daftar langkah berurutan dengan elemen <ol>.
- **Konsep Utama:** Elemen <ol> merender nomor angka urut naik secara otomatis pada setiap elemen anak <li>.
- **Penjelasan Source Code:** Menampilkan tiga tahapan instalasi proyek dengan nomor urut otomatis.
- **Cara Menjalankan:** Buka file `52_ordered_list.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Daftar bernomor 1, 2, 3 yang tersusun vertikal teratur.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Ordered List](output/52_ordered_list.png)

- **Lokasi Source Code:** [52_ordered_list.html](52_ordered_list.html)

---

### 3. Elemen li

- **Tujuan Pembelajaran:** Memahami aturan dan kapasitas konten di dalam elemen <li>.
- **Konsep Utama:** Elemen <li> berfungsi sebagai wadah serbaguna yang dapat menampung teks, link, gambar, bahkan list lain.
- **Penjelasan Source Code:** Menampilkan ragam jenis konten di dalam list item: teks, inline formatting, dan div kontainer.
- **Cara Menjalankan:** Buka file `53_list_item.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tiga butir list dengan format konten bervariasi dari teks hingga kotak div.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen li](output/53_list_item.png)

- **Lokasi Source Code:** [53_list_item.html](53_list_item.html)

---

### 4. Nested List

- **Tujuan Pembelajaran:** Menguasai teknik penulisan sub-daftar bersarang tanpa merusak validitas HTML.
- **Konsep Utama:** List bersarang harus ditempatkan di dalam tag <li> induk, bukan langsung di antara dua <li>.
- **Penjelasan Source Code:** Menampilkan kurikulum bertingkat dengan sub-daftar bullet dan sub-daftar angka di bawah induknya.
- **Cara Menjalankan:** Buka file `54_nested_list.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Daftar bersarang bertingkat dengan indentasi otomatis dari peramban.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Nested List](output/54_nested_list.png)

- **Lokasi Source Code:** [54_nested_list.html](54_nested_list.html)

---

### 5. Atribut start

- **Tujuan Pembelajaran:** Memahami konfigurasi angka awal pada ordered list dengan start.
- **Konsep Utama:** Atribut start menerima nilai integer untuk mengubah titik awal pencacahan penomoran otomatis.
- **Penjelasan Source Code:** Menampilkan daftar peringkat peserta yang dimulai langsung dari nomor 6.
- **Cara Menjalankan:** Buka file `55_start_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Daftar berangka yang urutannya dimulai dari angka 6, 7, 8.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut start](output/55_start_attribute.png)

- **Lokasi Source Code:** [55_start_attribute.html](55_start_attribute.html)

---

### 6. Atribut reversed

- **Tujuan Pembelajaran:** Mempelajari penomoran hitung mundur menggunakan atribut boolean reversed.
- **Konsep Utama:** Atribut boolean reversed membalik angka urut dari jumlah total item hingga angka 1.
- **Penjelasan Source Code:** Menampilkan simulasi hitung mundur tiga fase peluncuran wahana antariksa.
- **Cara Menjalankan:** Buka file `56_reversed_list.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Daftar terurut yang berangka mundur: 3, 2, 1.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut reversed](output/56_reversed_list.png)

- **Lokasi Source Code:** [56_reversed_list.html](56_reversed_list.html)

---

### 7. Atribut value pada List Item

- **Tujuan Pembelajaran:** Mengontrol loncatan penomoran pada elemen <li> tertentu.
- **Konsep Utama:** Atribut value pada <li> memaksa nomor urut item tersebut melompat ke angka yang ditentukan.
- **Penjelasan Source Code:** Menampilkan daftar pasal yang melompat dari nomor 2 langsung ke nomor 10 dan berlanjut ke 11.
- **Cara Menjalankan:** Buka file `57_list_value.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Daftar bernomor 1, 2, kemudian melompat ke 10 dan 11.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut value pada List Item](output/57_list_value.png)

- **Lokasi Source Code:** [57_list_value.html](57_list_value.html)

---

### 8. Description List (dl)

- **Tujuan Pembelajaran:** Memahami penggunaan description list <dl> untuk glosarium istilah dan metadata.
- **Konsep Utama:** Elemen <dl> membungkus pasangan nama-nilai atau istilah dan definisinya.
- **Penjelasan Source Code:** Menampilkan glosarium istilah teknis API dan DOM dengan penataan khas description list.
- **Cara Menjalankan:** Buka file `58_description_list.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak glosarium berpenataan istilah biru dengan definisi menjorok ke dalam.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Description List (dl)](output/58_description_list.png)

- **Lokasi Source Code:** [58_description_list.html](58_description_list.html)

---

### 9. Elemen dt

- **Tujuan Pembelajaran:** Memahami peran elemen <dt> sebagai penampung istilah atau term.
- **Konsep Utama:** Tag <dt> bertindak sebagai subjek atau kunci dalam daftar relasi key-value.
- **Penjelasan Source Code:** Menyajikan dua istilah teknis 'Bahasa Pemrograman' dan 'Bahasa Markup' menggunakan elemen dt.
- **Cara Menjalankan:** Buka file `59_description_term.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Dua istilah judul tebal diikuti penjelasan definisi masing-masing.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen dt](output/59_description_term.png)

- **Lokasi Source Code:** [59_description_term.html](59_description_term.html)

---

### 10. Elemen dd

- **Tujuan Pembelajaran:** Menguasai penggunaan multipel elemen <dd> untuk mendeskripsikan satu istilah tunggal.
- **Konsep Utama:** Satu <dt> diperbolehkan memiliki lebih dari satu <dd> untuk merinci aspek yang berbeda dari istilah tersebut.
- **Penjelasan Source Code:** Menampilkan istilah 'Kopi Arabika' yang dilengkapi dua rincian deskripsi terpisah.
- **Cara Menjalankan:** Buka file `60_description_details.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Istilah tebal tunggal yang memiliki dua baris poin penjelasan menjorok ke dalam.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen dd](output/60_description_details.png)

- **Lokasi Source Code:** [60_description_details.html](60_description_details.html)

---

### 11. Kombinasi Berbagai Jenis List

- **Tujuan Pembelajaran:** Mengintegrasikan ul, ol, dan dl dalam satu skenario struktur informasi nyata.
- **Konsep Utama:** Kombinasi jenis list yang tepat menghasilkan visualisasi hierarki informasi yang sangat teratur.
- **Penjelasan Source Code:** Menyajikan rencana kurikulum terpadu yang memadukan bullet list, numbered list, dan definition list.
- **Cara Menjalankan:** Buka file `61_mixed_list.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak rencana studi yang memuat perpaduan harmonis bullet, angka, dan definisi.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Kombinasi Berbagai Jenis List](output/61_mixed_list.png)

- **Lokasi Source Code:** [61_mixed_list.html](61_mixed_list.html)

---

### 12. List untuk Navigasi

- **Tujuan Pembelajaran:** Membangun komponen navbar semantik berbasis struktur daftar HTML.
- **Konsep Utama:** Screen reader dapat mengumumkan jumlah link menu kepada pengguna tunanetra jika navbar dibuat dari list.
- **Penjelasan Source Code:** Menampilkan menu bar horisontal modern berbasis list ul/li dengan tombol aktif berwarna biru.
- **Cara Menjalankan:** Buka file `62_navigation_list.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Bilah menu navigasi responsif gelap dengan tombol aktif Beranda yang menonjol.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi List untuk Navigasi](output/62_navigation_list.png)

- **Lokasi Source Code:** [62_navigation_list.html](62_navigation_list.html)

---

## Ringkasan Modul
Modul 4 menyajikan pondasi penting mengenai List dan Pengelompokan Konten. Pemahaman menyeluruh terhadap submodul di atas menjadi prasyarat penting sebelum melangkah ke modul berikutnya.
