# Modul 1: Pengenalan HTML dan Struktur Dokumen

## Ringkasan Ruang Lingkup Materi
Modul ini membahas konsep dasar dan implementasi praktis seputar **Pengenalan HTML dan Struktur Dokumen**. Setiap submodul dirancang secara terisolasi agar pembelajar dapat memahami konsep satu per satu secara fokus dan terstruktur.

## Tujuan Pembelajaran Modul
Setelah menyelesaikan modul ini, peserta didik diharapkan mampu memahami, mengimplementasikan, dan menguji komponen-komponen utama dalam lingkup pengenalan html dan struktur dokumen sesuai standar modern W3C.

## Daftar Materi atau Submodul

- [01_hello_html.html](01_hello_html.html) - Halaman HTML Pertama
- [02_html_document_structure.html](02_html_document_structure.html) - Struktur Dokumen HTML
- [03_doctype_declaration.html](03_doctype_declaration.html) - Deklarasi DOCTYPE
- [04_html_element.html](04_html_element.html) - Elemen HTML
- [05_html_tags.html](05_html_tags.html) - Tag HTML
- [06_html_attributes.html](06_html_attributes.html) - Atribut HTML
- [07_html_nesting.html](07_html_nesting.html) - Nested Elements
- [08_html_indentation.html](08_html_indentation.html) - Indentasi HTML
- [09_html_comments.html](09_html_comments.html) - Komentar HTML
- [10_html_entities.html](10_html_entities.html) - HTML Entities
- [11_html_whitespace.html](11_html_whitespace.html) - Whitespace dalam HTML
- [12_html_case_sensitivity.html](12_html_case_sensitivity.html) - Penulisan Tag dan Atribut
- [13_html_void_elements.html](13_html_void_elements.html) - Void Elements
- [14_html_global_attributes.html](14_html_global_attributes.html) - Global Attributes
- [15_html_parent_child_elements.html](15_html_parent_child_elements.html) - Parent dan Child Elements

---

## Pembahasan Setiap Submodul

### 1. Halaman HTML Pertama

- **Tujuan Pembelajaran:** Memahami cara membuat dan menampilkan halaman HTML pertama di peramban web.
- **Konsep Utama:** HTML merupakan bahasa markup standar untuk membuat halaman web. Dokumen HTML terdiri dari serangkaian tag yang memberitahu peramban cara menampilkan konten.
- **Penjelasan Source Code:** File ini mendemonstrasikan dokumen HTML valid yang berisi elemen heading <h1> dan paragraf <p>. Setiap elemen membungkus teks konten dan dirender secara blok oleh browser.
- **Cara Menjalankan:** Buka file `01_hello_html.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Teks judul berukuran besar 'Halo Dunia HTML!' diikuti dua blok paragraf teks yang tertata rapi.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Halaman HTML Pertama](output/01_hello_html.png)

- **Lokasi Source Code:** [01_hello_html.html](01_hello_html.html)

---

### 2. Struktur Dokumen HTML

- **Tujuan Pembelajaran:** Memahami hierarki kerangka dokumen HTML5 dari akar (root) hingga ranting konten.
- **Konsep Utama:** Struktur dokumen HTML5 terdiri dari <!DOCTYPE html>, elemen root <html>, elemen kepala <head> untuk metadata, dan elemen tubuh <body> untuk konten visual.
- **Penjelasan Source Code:** Program mendemonstrasikan visualisasi bertingkat tentang bagaimana elemen-elemen fondasi saling bersarang dan berfungsi membangun dokumen web utuh.
- **Cara Menjalankan:** Buka file `02_html_document_structure.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Diagram pohon hirarki DOM yang menunjukkan hubungan antara DOCTYPE, html, head, dan body.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Struktur Dokumen HTML](output/02_html_document_structure.png)

- **Lokasi Source Code:** [02_html_document_structure.html](02_html_document_structure.html)

---

### 3. Deklarasi DOCTYPE

- **Tujuan Pembelajaran:** Memahami fungsi instruksi <!DOCTYPE html> dalam mencegah browser masuk ke mode rendering kuno (quirks mode).
- **Konsep Utama:** DOCTYPE bukan tag HTML melainkan prolog instruksi bagi engine peramban untuk menerapkan spesifikasi HTML5 standar.
- **Penjelasan Source Code:** Source code menjelaskan perbedaan sintaks DOCTYPE modern HTML5 dengan HTML versi terdahulu serta implikasinya terhadap rendering tata letak.
- **Cara Menjalankan:** Buka file `03_doctype_declaration.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tampilan artikel perbandingan sintaks DOCTYPE dengan highlight blok standar vs versi lama.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Deklarasi DOCTYPE](output/03_doctype_declaration.png)

- **Lokasi Source Code:** [03_doctype_declaration.html](03_doctype_declaration.html)

---

### 4. Elemen HTML

- **Tujuan Pembelajaran:** Membedakan antara konsep tag dan elemen dalam ekosistem HTML.
- **Konsep Utama:** Elemen adalah satu unit utuh yang tersusun dari start tag, konten isi, dan end tag.
- **Penjelasan Source Code:** Program mendemonstrasikan visualisasi warna dari anatomi elemen HTML sehingga pemula dapat melihat batasan awal dan akhir suatu elemen.
- **Cara Menjalankan:** Buka file `04_html_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Diagram visual terpecah tiga warna: biru (start tag), kuning (konten), merah (end tag).
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen HTML](output/04_html_element.png)

- **Lokasi Source Code:** [04_html_element.html](04_html_element.html)

---

### 5. Tag HTML

- **Tujuan Pembelajaran:** Menguasai cara menuliskan tag pembuka dan tag penutup secara benar.
- **Konsep Utama:** Tag adalah token markup dengan kurung sudut yang memberi instruksi kepada parser peramban web.
- **Penjelasan Source Code:** File mendemonstrasikan penggunaan tag berpasangan seperti <h3>, <p>, dan <strong> beserta aturan penutupan dengan garis miring.
- **Cara Menjalankan:** Buka file `05_html_tags.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Halaman yang merender heading dan paragraf dengan penekanan kata selesai.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Tag HTML](output/05_html_tags.png)

- **Lokasi Source Code:** [05_html_tags.html](05_html_tags.html)

---

### 6. Atribut HTML

- **Tujuan Pembelajaran:** Menguasai penggunaan atribut untuk mengontrol identifikasi, gaya, dan perilaku elemen.
- **Konsep Utama:** Atribut dituliskan pada start tag untuk menambahkan metadata, identifier unik (id), kelas CSS (class), atau konfigurasi khusus (href, title).
- **Penjelasan Source Code:** Menampilkan paragraf yang dilengkapi atribut id, class, dan title (tooltip peramban), serta tag tautan dengan atribut href.
- **Cara Menjalankan:** Buka file `06_html_attributes.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Teks interaktif yang menampilkan tooltip ketika pengguna mengarahkan mouse ke atasnya.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut HTML](output/06_html_attributes.png)

- **Lokasi Source Code:** [06_html_attributes.html](06_html_attributes.html)

---

### 7. Nested Elements

- **Tujuan Pembelajaran:** Memahami konsep nesting elemen HTML dan menghindari kesalahan overlapping tag.
- **Konsep Utama:** Elemen yang dibuka paling akhir harus ditutup paling awal (prinsip Last-In First-Out) untuk menjaga keutuhan pohon DOM.
- **Penjelasan Source Code:** Mendemonstrasikan perbandingan kontras antara pola nesting yang valid (kotak hijau) dengan pola invalid yang dilarang (kotak merah).
- **Cara Menjalankan:** Buka file `07_html_nesting.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Dua kotak perbandingan visual hijau dan merah yang menjelaskan aturan nesting.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Nested Elements](output/07_html_nesting.png)

- **Lokasi Source Code:** [07_html_nesting.html](07_html_nesting.html)

---

### 8. Indentasi HTML

- **Tujuan Pembelajaran:** Memahami peran indentasi dalam menjaga keterbacaan dan struktur hierarki kode HTML.
- **Konsep Utama:** Meskipun peramban mengabaikan spasi kosong, indentasi sangat esensial bagi pemeliharaan kode oleh software engineer.
- **Penjelasan Source Code:** Menampilkan contoh penulisan markup bersarang dengan indentasi standar bertingkat dalam blok kode.
- **Cara Menjalankan:** Buka file `08_html_indentation.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tampilan blok kode berlatar gelap yang memperlihatkan hierarki indentasi secara jelas.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Indentasi HTML](output/08_html_indentation.png)

- **Lokasi Source Code:** [08_html_indentation.html](08_html_indentation.html)

---

### 9. Komentar HTML

- **Tujuan Pembelajaran:** Mempelajari sintaks <!-- ... --> untuk menyematkan catatan edukatif tanpa merusak tampilan visual.
- **Konsep Utama:** Komentar diabaikan oleh parser rendering browser namun dapat dibaca di source code untuk dokumentasi.
- **Penjelasan Source Code:** File mendemonstrasikan komentar satu baris dan multi-baris di samping elemen paragraf aktif.
- **Cara Menjalankan:** Buka file `09_html_comments.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Halaman yang merender paragraf tanpa memunculkan teks komentar internal.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Komentar HTML](output/09_html_comments.png)

- **Lokasi Source Code:** [09_html_comments.html](09_html_comments.html)

---

### 10. HTML Entities

- **Tujuan Pembelajaran:** Memahami cara menampilkan karakter yang bertabrakan dengan sintaks markup atau tidak ada di keyboard.
- **Konsep Utama:** HTML entities ditulis dalam format &nama; atau &#nomor; untuk merepresentasikan karakter terlarang atau simbol khusus.
- **Penjelasan Source Code:** Menampilkan daftar entitas esensial (&lt;, &gt;, &amp;, &quot;, &copy;, &nbsp;) dan hasil visualisasinya.
- **Cara Menjalankan:** Buka file `10_html_entities.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Daftar entitas kode dan simbol hasil render nyata seperti <, >, &, ©.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi HTML Entities](output/10_html_entities.png)

- **Lokasi Source Code:** [10_html_entities.html](10_html_entities.html)

---

### 11. Whitespace dalam HTML

- **Tujuan Pembelajaran:** Memahami perilaku peramban dalam memproses karakter spasi, tab, dan baris baru.
- **Konsep Utama:** Peramban secara otomatis menyusutkan deretan spasi berturut-turut menjadi satu spasi tunggal, kecuali jika dibungkus oleh elemen <pre>.
- **Penjelasan Source Code:** Mendemonstrasikan perbedaan rendering antara teks biasa dengan spasi berlebih dan teks dalam elemen <pre>.
- **Cara Menjalankan:** Buka file `11_html_whitespace.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Perbandingan dua blok yang memperlihatkan spasi yang disusutkan versus spasi yang dipertahankan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Whitespace dalam HTML](output/11_html_whitespace.png)

- **Lokasi Source Code:** [11_html_whitespace.html](11_html_whitespace.html)

---

### 12. Penulisan Tag dan Atribut

- **Tujuan Pembelajaran:** Memahami konvensi penulisan nama tag dan atribut sesuai standar W3C modern.
- **Konsep Utama:** HTML5 mengizinkan penulisan case-insensitive, namun standar industri secara universal menetapkan huruf kecil (lowercase).
- **Penjelasan Source Code:** Menjelaskan aturan toleransi case pada HTML5 serta standar praktik profesional.
- **Cara Menjalankan:** Buka file `12_html_case_sensitivity.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Penjelasan panduan gaya kode yang rapi dengan kotak anjuran praktik terbaik W3C.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Penulisan Tag dan Atribut](output/12_html_case_sensitivity.png)

- **Lokasi Source Code:** [12_html_case_sensitivity.html](12_html_case_sensitivity.html)

---

### 13. Void Elements

- **Tujuan Pembelajaran:** Mengenali elemen-elemen void yang tidak memerlukan tag penutup terpisah.
- **Konsep Utama:** Void element (elemen hampa) hanya terdiri dari satu tag awal tanpa konten teks atau anak di dalamnya.
- **Penjelasan Source Code:** File mendemonstrasikan elemen <br> dan <hr> dalam memecah baris teks dan memisahkan konten secara visual.
- **Cara Menjalankan:** Buka file `13_html_void_elements.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Teks dua baris yang terpisah oleh <br> dan dibatasi garis pembatas <hr>.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Void Elements](output/13_html_void_elements.png)

- **Lokasi Source Code:** [13_html_void_elements.html](13_html_void_elements.html)

---

### 14. Global Attributes

- **Tujuan Pembelajaran:** Menguasai atribut-atribut global yang dapat disematkan pada seluruh elemen HTML.
- **Konsep Utama:** Global attributes adalah atribut standar yang sah disematkan pada elemen apapun di dalam HTML5.
- **Penjelasan Source Code:** Program mendemonstrasikan kombinasi atribut id, class, title, style, dan hidden pada elemen kontainer.
- **Cara Menjalankan:** Buka file `14_html_global_attributes.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak berbingkai biru dengan informasi atribut aktif serta pembuktian teks hidden yang tersembunyi.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Global Attributes](output/14_html_global_attributes.png)

- **Lokasi Source Code:** [14_html_global_attributes.html](14_html_global_attributes.html)

---

### 15. Parent dan Child Elements

- **Tujuan Pembelajaran:** Memahami konsep hubungan pohon DOM yang menjadi pondasi styling CSS dan scripting JS.
- **Konsep Utama:** Setiap elemen yang membungkus elemen lain disebut parent, elemen di dalamnya disebut child, dan elemen pada tingkat yang sama disebut sibling.
- **Penjelasan Source Code:** Visualisasi wadah terputus-putus yang dengan jelas melabeli peran parent, child, dan sibling.
- **Cara Menjalankan:** Buka file `15_html_parent_child_elements.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Diagram visual terstruktur dengan label parent, child, dan list item bertingkat.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Parent dan Child Elements](output/15_html_parent_child_elements.png)

- **Lokasi Source Code:** [15_html_parent_child_elements.html](15_html_parent_child_elements.html)

---

## Ringkasan Modul
Modul 1 menyajikan pondasi penting mengenai Pengenalan HTML dan Struktur Dokumen. Pemahaman menyeluruh terhadap submodul di atas menjadi prasyarat penting sebelum melangkah ke modul berikutnya.
