# Modul 15: Internasionalisasi dan Metadata Semantik

## Ringkasan Ruang Lingkup Materi
Modul ini membahas konsep dasar dan implementasi praktis seputar **Internasionalisasi dan Metadata Semantik**. Setiap submodul dirancang secara terisolasi agar pembelajar dapat memahami konsep satu per satu secara fokus dan terstruktur.

## Tujuan Pembelajaran Modul
Setelah menyelesaikan modul ini, peserta didik diharapkan mampu memahami, mengimplementasikan, dan menguji komponen-komponen utama dalam lingkup internasionalisasi dan metadata semantik sesuai standar modern W3C.

## Daftar Materi atau Submodul

- [246_lang_attribute.html](246_lang_attribute.html) - Atribut lang
- [247_direction_attribute.html](247_direction_attribute.html) - Atribut dir
- [248_rtl_content.html](248_rtl_content.html) - Konten Right-to-Left (RTL)
- [249_unicode_html.html](249_unicode_html.html) - Unicode dalam HTML
- [250_language_specific_content.html](250_language_specific_content.html) - Konten Multibahasa
- [251_bdi_element.html](251_bdi_element.html) - Elemen bdi (Bi-directional Isolation)
- [252_bdo_element.html](252_bdo_element.html) - Elemen bdo (Bi-directional Override)
- [253_ruby_annotation.html](253_ruby_annotation.html) - Elemen ruby
- [254_rp_element.html](254_rp_element.html) - Elemen rp
- [255_rt_element.html](255_rt_element.html) - Elemen rt
- [256_microdata_basic.html](256_microdata_basic.html) - Microdata Dasar
- [257_itemscope_itemtype.html](257_itemscope_itemtype.html) - Atribut itemscope dan itemtype
- [258_itemprop_attribute.html](258_itemprop_attribute.html) - Atribut itemprop
- [259_structured_data_content.html](259_structured_data_content.html) - Struktur Konten untuk Data Terstruktur
- [260_semantic_metadata.html](260_semantic_metadata.html) - Metadata Semantik Halaman

---

## Pembahasan Setiap Submodul

### 1. Atribut lang

- **Tujuan Pembelajaran:** Memahami pentingnya deklarasi atribut lang untuk internasionalisasi (i18n).
- **Konsep Utama:** Tanpa atribut lang yang benar, screen reader akan membacakan teks bahasa asing dengan aksen salah.
- **Penjelasan Source Code:** Menampilkan paragraf bahasa Indonesia dan kutipan bahasa Inggris berlatar biru.
- **Cara Menjalankan:** Buka file `246_lang_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Dua kalimat multibahasa dengan atribut identifikasi bahasa berbeda.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut lang](output/246_lang_attribute.png)

- **Lokasi Source Code:** [246_lang_attribute.html](246_lang_attribute.html)

---

### 2. Atribut dir

- **Tujuan Pembelajaran:** Menguasai pengelolaan arah penulisan teks dua arah (BiDi).
- **Konsep Utama:** Atribut dir membalik alur pengetikan, posisi tanda baca, dan scrollbar peramban.
- **Penjelasan Source Code:** Menampilkan kalimat kaligrafi Arab dengan arah penulisan kanan ke kiri.
- **Cara Menjalankan:** Buka file `247_direction_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Teks bahasa Arab tersusun rapat dari sisi kanan halaman.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut dir](output/247_direction_attribute.png)

- **Lokasi Source Code:** [247_direction_attribute.html](247_direction_attribute.html)

---

### 3. Konten Right-to-Left (RTL)

- **Tujuan Pembelajaran:** Mendesain komponen web yang ramah budaya baca Arab dan Timur Tengah.
- **Konsep Utama:** Tata letak RTL membalik seluruh orientasi visual margin, padding, dan penanda border.
- **Penjelasan Source Code:** Menampilkan kartu artikel bergaya RTL dengan aksen garis biru di sisi kanan.
- **Cara Menjalankan:** Buka file `248_rtl_content.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kartu informasi berbahasa Arab dengan garis tepi aksen di sebelah kanan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Konten Right-to-Left (RTL)](output/248_rtl_content.png)

- **Lokasi Source Code:** [248_rtl_content.html](248_rtl_content.html)

---

### 4. Unicode dalam HTML

- **Tujuan Pembelajaran:** Memahami sistem pengkodean karakter universal Unicode pada dokumen web.
- **Konsep Utama:** Setiap karakter di dunia memiliki titik kode (code point) unik yang dapat dipanggil di HTML.
- **Penjelasan Source Code:** Menampilkan aneka simbol mata uang, matematika, dan musik yang dirender tajam.
- **Cara Menjalankan:** Buka file `249_unicode_html.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Daftar simbol Unicode mata uang dan matematika yang tertata rapi.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Unicode dalam HTML](output/249_unicode_html.png)

- **Lokasi Source Code:** [249_unicode_html.html](249_unicode_html.html)

---

### 5. Konten Multibahasa

- **Tujuan Pembelajaran:** Mengorganisir presentasi konten multibahasa secara terstruktur.
- **Konsep Utama:** Setiap wadah bahasa dilabeli atribut lang yang spesifik agar diindeks akurat oleh mesin terjemahan.
- **Penjelasan Source Code:** Menampilkan dua kartu berdampingan versi Bahasa Indonesia dan Bahasa Inggris.
- **Cara Menjalankan:** Buka file `250_language_specific_content.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Dua kolom kartu komparasi bahasa Indonesia dan bahasa Inggris.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Konten Multibahasa](output/250_language_specific_content.png)

- **Lokasi Source Code:** [250_language_specific_content.html](250_language_specific_content.html)

---

### 6. Elemen bdi (Bi-directional Isolation)

- **Tujuan Pembelajaran:** Mencegah kekacauan tata letak teks akibat injeksi konten dinamis multibahasa.
- **Konsep Utama:** Elemen <bdi> mengisolasi perhitung algoritma BiDi agar teks di luar tidak terpengaruh.
- **Penjelasan Source Code:** Menampilkan dua kalimat daftar aktivitas pengguna dengan nama Arab dan Latin.
- **Cara Menjalankan:** Buka file `251_bdi_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Daftar notifikasi aktivitas pengguna yang tersusun rapi tanpa teks terbalik.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen bdi (Bi-directional Isolation)](output/251_bdi_element.png)

- **Lokasi Source Code:** [251_bdi_element.html](251_bdi_element.html)

---

### 7. Elemen bdo (Bi-directional Override)

- **Tujuan Pembelajaran:** Mempelajari mekanisme pembalikan paksa teks dengan elemen <bdo>.
- **Konsep Utama:** BDO mengabaikan algoritma bidirectional bawaan karakter dan memaksa arah yang ditentukan atribut dir.
- **Penjelasan Source Code:** Menampilkan kalimat normal dan kalimat yang karakternya dibalik dari kanan ke kiri.
- **Cara Menjalankan:** Buka file `252_bdo_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Perbandingan kalimat normal versus kalimat terbalik secara paksa.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen bdo (Bi-directional Override)](output/252_bdo_element.png)

- **Lokasi Source Code:** [252_bdo_element.html](252_bdo_element.html)

---

### 8. Elemen ruby

- **Tujuan Pembelajaran:** Memahami anotasi tipografi fonetik Asia Timur menggunakan elemen <ruby>.
- **Konsep Utama:** Anotasi ruby banyak digunakan pada buku pelajaran bahasa Jepang, Mandarin, dan Korea.
- **Penjelasan Source Code:** Menampilkan huruf kanji Jepang dengan panduan baca fonetik kecil di sisi atas.
- **Cara Menjalankan:** Buka file `253_ruby_annotation.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Dua huruf kanji besar dengan takarir pelafalan kecil di atasnya.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen ruby](output/253_ruby_annotation.png)

- **Lokasi Source Code:** [253_ruby_annotation.html](253_ruby_annotation.html)

---

### 9. Elemen rp

- **Tujuan Pembelajaran:** Menyediakan fallback tanda kurung yang elegan untuk pelafalan fonetik.
- **Konsep Utama:** Peramban modern menyembunyikan isi tag <rp>, sedangkan peramban lawas menampilkannya sebagai teks di dalam kurung.
- **Penjelasan Source Code:** Menampilkan huruf kanji Tokyo dengan pelafalan fonetik dan proteksi fallback rp.
- **Cara Menjalankan:** Buka file `254_rp_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Anotasi fonetik kanji Tokyo berpelindung tag kurung cadangan rp.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen rp](output/254_rp_element.png)

- **Lokasi Source Code:** [254_rp_element.html](254_rp_element.html)

---

### 10. Elemen rt

- **Tujuan Pembelajaran:** Menguasai penulisan teks pelafalan dengan elemen <rt>.
- **Konsep Utama:** Teks di dalam <rt> dirender lebih kecil dan mengambang di atas karakter dasarnya.
- **Penjelasan Source Code:** Menampilkan kanji 'ashita' (besok) dengan teks fonetik biru melayang di atasnya.
- **Cara Menjalankan:** Buka file `255_rt_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Karakter huruf kanji dengan pelafalan fonetik biru di atasnya.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen rt](output/255_rt_element.png)

- **Lokasi Source Code:** [255_rt_element.html](255_rt_element.html)

---

### 11. Microdata Dasar

- **Tujuan Pembelajaran:** Mengenal penyematan metadata Schema.org berbasis Microdata.
- **Konsep Utama:** Microdata membantu Google Search memunculkan Rich Snippets pada hasil pencarian.
- **Penjelasan Source Code:** Menampilkan kartu profil yang dilabeli atribut Microdata itemprop.
- **Cara Menjalankan:** Buka file `256_microdata_basic.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kartu biodata singkat beranotasi Microdata data terstruktur.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Microdata Dasar](output/256_microdata_basic.png)

- **Lokasi Source Code:** [256_microdata_basic.html](256_microdata_basic.html)

---

### 12. Atribut itemscope dan itemtype

- **Tujuan Pembelajaran:** Mendeklarasikan ruang lingkup dan skema ontologi data terstruktur.
- **Konsep Utama:** Kombinasi itemscope dan itemtype mengunci konteks kamus data terstruktur.
- **Penjelasan Source Code:** Menampilkan entitas Person berskema Schema.org resmi berlatar hijau.
- **Cara Menjalankan:** Buka file `257_itemscope_itemtype.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kartu entitas bergaris tepi hijau beranotasi skema Person.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut itemscope dan itemtype](output/257_itemscope_itemtype.png)

- **Lokasi Source Code:** [257_itemscope_itemtype.html](257_itemscope_itemtype.html)

---

### 13. Atribut itemprop

- **Tujuan Pembelajaran:** Memetakan nilai data teks ke properti spesifik Schema.org dengan itemprop.
- **Konsep Utama:** Mesin pencari membaca nilai itemprop untuk menampilkan harga langsung di Google Shopping.
- **Penjelasan Source Code:** Menampilkan kartu produk dengan properti name, description, dan price terpetakan.
- **Cara Menjalankan:** Buka file `258_itemprop_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kartu produk buku dengan label harga teranotasi itemprop.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut itemprop](output/258_itemprop_attribute.png)

- **Lokasi Source Code:** [258_itemprop_attribute.html](258_itemprop_attribute.html)

---

### 14. Struktur Konten untuk Data Terstruktur

- **Tujuan Pembelajaran:** Mendesain konten yang secara otomatis memicu Rich Card di hasil pencarian.
- **Konsep Utama:** Format data terstruktur yang lengkap meningkatkan visibilitas dan kredibilitas situs web.
- **Penjelasan Source Code:** Menampilkan kartu resep beraroma kopi hangat dengan metadata waktu penyajian.
- **Cara Menjalankan:** Buka file `259_structured_data_content.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kartu resep bernuansa cokelat hangat dengan data terstruktur Recipe.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Struktur Konten untuk Data Terstruktur](output/259_structured_data_content.png)

- **Lokasi Source Code:** [259_structured_data_content.html](259_structured_data_content.html)

---

### 15. Metadata Semantik Halaman

- **Tujuan Pembelajaran:** Mengenal integrasi metadata modern berbasis JSON-LD bersanding dengan HTML semantik.
- **Konsep Utama:** JSON-LD memisahkan payload data mesin dari markup visual demi efisiensi pemeliharaan.
- **Penjelasan Source Code:** Menampilkan blok kode JSON-LD skema Course dalam wadah kode gelap.
- **Cara Menjalankan:** Buka file `260_semantic_metadata.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Blok kode skema JSON-LD terstruktur di dalam kotak gelap informatif.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Metadata Semantik Halaman](output/260_semantic_metadata.png)

- **Lokasi Source Code:** [260_semantic_metadata.html](260_semantic_metadata.html)

---

## Ringkasan Modul
Modul 15 menyajikan pondasi penting mengenai Internasionalisasi dan Metadata Semantik. Pemahaman menyeluruh terhadap submodul di atas menjadi prasyarat penting sebelum melangkah ke modul berikutnya.
