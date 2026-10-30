# Modul 13: Aksesibilitas HTML

## Ringkasan Ruang Lingkup Materi
Modul ini membahas konsep dasar dan implementasi praktis seputar **Aksesibilitas HTML**. Setiap submodul dirancang secara terisolasi agar pembelajar dapat memahami konsep satu per satu secara fokus dan terstruktur.

## Tujuan Pembelajaran Modul
Setelah menyelesaikan modul ini, peserta didik diharapkan mampu memahami, mengimplementasikan, dan menguji komponen-komponen utama dalam lingkup aksesibilitas html sesuai standar modern W3C.

## Daftar Materi atau Submodul

- [211_accessible_document_structure.html](211_accessible_document_structure.html) - Struktur Dokumen Aksesibel
- [212_heading_hierarchy.html](212_heading_hierarchy.html) - Hierarki Heading
- [213_image_alt_text.html](213_image_alt_text.html) - Teks Alternatif Gambar
- [214_decorative_images.html](214_decorative_images.html) - Gambar Dekoratif
- [215_form_label_accessibility.html](215_form_label_accessibility.html) - Label Formulir Aksesibel
- [216_fieldset_accessibility.html](216_fieldset_accessibility.html) - Pengelompokan Input Aksesibel
- [217_keyboard_navigation.html](217_keyboard_navigation.html) - Navigasi Menggunakan Keyboard
- [218_tabindex_attribute.html](218_tabindex_attribute.html) - Atribut tabindex
- [219_aria_labels.html](219_aria_labels.html) - Atribut aria-label
- [220_aria_labelledby.html](220_aria_labelledby.html) - Atribut aria-labelledby
- [221_aria_describedby.html](221_aria_describedby.html) - Atribut aria-describedby
- [222_aria_hidden.html](222_aria_hidden.html) - Atribut aria-hidden
- [223_aria_live.html](223_aria_live.html) - Atribut aria-live
- [224_aria_expanded.html](224_aria_expanded.html) - Atribut aria-expanded
- [225_aria_controls.html](225_aria_controls.html) - Atribut aria-controls
- [226_landmark_roles.html](226_landmark_roles.html) - Landmark roles
- [227_accessible_tables.html](227_accessible_tables.html) - Tabel Aksesibel
- [228_accessible_links.html](228_accessible_links.html) - Link Aksesibel
- [229_accessible_buttons.html](229_accessible_buttons.html) - Tombol Aksesibel
- [230_accessibility_testing.html](230_accessibility_testing.html) - Pemeriksaan Aksesibilitas HTML

---

## Pembahasan Setiap Submodul

### 1. Struktur Dokumen Aksesibel

- **Tujuan Pembelajaran:** Memahami 4 pilar aksesibilitas web standar internasional (POUR).
- **Konsep Utama:** Dokumen aksesibel menjamin hak setara bagi pengguna dengan keterbatasan visual, motorik, atau auditori.
- **Penjelasan Source Code:** Menampilkan ringkasan 4 prinsip POUR dalam kotak informatif.
- **Cara Menjalankan:** Buka file `211_accessible_document_structure.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak penjelasan 4 pilar POUR aksesibilitas web.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Struktur Dokumen Aksesibel](output/211_accessible_document_structure.png)

- **Lokasi Source Code:** [211_accessible_document_structure.html](211_accessible_document_structure.html)

---

### 2. Hierarki Heading

- **Tujuan Pembelajaran:** Menyusun hierarki heading logis yang menjadi peta navigasi screen reader.
- **Konsep Utama:** Melompati tingkatan heading membingungkan pengguna yang menavigasi via outline suara.
- **Penjelasan Source Code:** Menampilkan struktur heading bertingkat rapi berlatar hijau keberhasilan.
- **Cara Menjalankan:** Buka file `212_heading_hierarchy.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Hierarki judul berurutan dengan penanda garis tepi hijau.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Hierarki Heading](output/212_heading_hierarchy.png)

- **Lokasi Source Code:** [212_heading_hierarchy.html](212_heading_hierarchy.html)

---

### 3. Teks Alternatif Gambar

- **Tujuan Pembelajaran:** Menyusun teks deskripsi alt yang memberikan nilai informasi setara dengan visualnya.
- **Konsep Utama:** Teks alternatif menjelaskan konteks dan maksud gambar, bukan sekadar nama file.
- **Penjelasan Source Code:** Menampilkan contoh penulisan deskripsi alt yang memenuhi standar WCAG.
- **Cara Menjalankan:** Buka file `213_image_alt_text.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak biru panduan penulisan alt text efektif.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Teks Alternatif Gambar](output/213_image_alt_text.png)

- **Lokasi Source Code:** [213_image_alt_text.html](213_image_alt_text.html)

---

### 4. Gambar Dekoratif

- **Tujuan Pembelajaran:** Mencegah polusi suara pada screen reader akibat gambar hiasan non-informasi.
- **Konsep Utama:** Memberikan alt='' menandai gambar sebagai dekoratif dan menginstruksikan screen reader untuk melewatkannya.
- **Penjelasan Source Code:** Menampilkan ikon dekoratif yang diabaikan oleh teknologi asistif.
- **Cara Menjalankan:** Buka file `214_decorative_images.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Baris kartu pemanis visual dengan keterangan atribut aria-hidden.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Gambar Dekoratif](output/214_decorative_images.png)

- **Lokasi Source Code:** [214_decorative_images.html](214_decorative_images.html)

---

### 5. Label Formulir Aksesibel

- **Tujuan Pembelajaran:** Mengikat label dengan field input secara eksplisit demi screen reader.
- **Konsep Utama:** Tanpa atribut for yang cocok dengan id, screen reader hanya akan membaca 'edit text blank' yang membingungkan.
- **Penjelasan Source Code:** Menampilkan field NIK dengan relasi label yang kokoh.
- **Cara Menjalankan:** Buka file `215_form_label_accessibility.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field input formulir dengan label teks tebal yang terikat sempurna.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Label Formulir Aksesibel](output/215_form_label_accessibility.png)

- **Lokasi Source Code:** [215_form_label_accessibility.html](215_form_label_accessibility.html)

---

### 6. Pengelompokan Input Aksesibel

- **Tujuan Pembelajaran:** Menjamin pengguna screen reader memahami konteks pertanyaan pada kelompok tombol radio.
- **Konsep Utama:** Legend dibacakan ulang saat pengguna berpindah antar-opsi di dalam fieldset.
- **Penjelasan Source Code:** Menampilkan kuesioner radio dalam bingkai fieldset aksesibel.
- **Cara Menjalankan:** Buka file `216_fieldset_accessibility.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Bingkai kuesioner dengan pertanyaan di garis bingkai atas.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Pengelompokan Input Aksesibel](output/216_fieldset_accessibility.png)

- **Lokasi Source Code:** [216_fieldset_accessibility.html](216_fieldset_accessibility.html)

---

### 7. Navigasi Menggunakan Keyboard

- **Tujuan Pembelajaran:** Mendukung navigasi tanpa mouse untuk pengguna dengan keterbatasan motorik.
- **Konsep Utama:** Indikator fokus keyboard (:focus-visible) adalah syarat wajib kepatuhan WCAG 2.1.
- **Penjelasan Source Code:** Menampilkan tombol dan tautan dengan garis luar fokus (focus ring) yang kontras.
- **Cara Menjalankan:** Buka file `217_keyboard_navigation.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Dua elemen interaktif dengan cincin fokus visual tegas.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Navigasi Menggunakan Keyboard](output/217_keyboard_navigation.png)

- **Lokasi Source Code:** [217_keyboard_navigation.html](217_keyboard_navigation.html)

---

### 8. Atribut tabindex

- **Tujuan Pembelajaran:** Mengelola urutan tab keyboard secara bijaksana tanpa mengacaukan navigasi.
- **Konsep Utama:** Tabindex 0 mengizinkan elemen non-interaktif menerima fokus, sedangkan -1 khusus manipulasi skrip.
- **Penjelasan Source Code:** Menampilkan kotak khusus yang dapat difokuskan dengan keyboard melalui tabindex 0.
- **Cara Menjalankan:** Buka file `218_tabindex_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak informasi berbingkai biru yang dapat di-tab langsung.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut tabindex](output/218_tabindex_attribute.png)

- **Lokasi Source Code:** [218_tabindex_attribute.html](218_tabindex_attribute.html)

---

### 9. Atribut aria-label

- **Tujuan Pembelajaran:** Mengatasi tombol tanpa teks kasat mata dengan atribut aria-label.
- **Konsep Utama:** Aria-label menggantikan teks visual sebagai nama komputasi elemen pada pohon aksesibilitas.
- **Penjelasan Source Code:** Menampilkan tombol ikon kaca pembesar yang dilengkapi atribut aria-label deskriptif.
- **Cara Menjalankan:** Buka file `219_aria_labels.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tombol pencarian biru berikon kaca pembesar dengan keterangan ARIA.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut aria-label](output/219_aria_labels.png)

- **Lokasi Source Code:** [219_aria_labels.html](219_aria_labels.html)

---

### 10. Atribut aria-labelledby

- **Tujuan Pembelajaran:** Menghubungkan label dari elemen lain menggunakan aria-labelledby.
- **Konsep Utama:** Aria-labelledby memanfaatkan teks yang sudah ada di halaman sehingga tidak perlu duplikasi string.
- **Penjelasan Source Code:** Menampilkan kartu informasi yang dinamai langsung dari ID heading utamanya.
- **Cara Menjalankan:** Buka file `220_aria_labelledby.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Wilayah konten berbingkai yang terasosiasi dengan judul teks ID di dalamnya.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut aria-labelledby](output/220_aria_labelledby.png)

- **Lokasi Source Code:** [220_aria_labelledby.html](220_aria_labelledby.html)

---

### 11. Atribut aria-describedby

- **Tujuan Pembelajaran:** Menyediakan deskripsi pelengkap input untuk pembaca layar.
- **Konsep Utama:** Aria-describedby dibacakan setelah label utama selesai diumumkan oleh screen reader.
- **Penjelasan Source Code:** Menampilkan field sandi yang terikat dengan teks petunjuk keamanan di bawahnya.
- **Cara Menjalankan:** Buka file `221_aria_describedby.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field kata sandi dengan teks petunjuk format aman di sisi bawah.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut aria-describedby](output/221_aria_describedby.png)

- **Lokasi Source Code:** [221_aria_describedby.html](221_aria_describedby.html)

---

### 12. Atribut aria-hidden

- **Tujuan Pembelajaran:** Mengeliminasi elemen visual membingungkan dari teknologi asistif.
- **Konsep Utama:** Aria-hidden='true' menghapus elemen beserta anak-anaknya dari pohon aksesibilitas.
- **Penjelasan Source Code:** Menampilkan teks dengan ikon sampah yang dilindungi aria-hidden.
- **Cara Menjalankan:** Buka file `222_aria_hidden.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Teks informatif dengan ikon pemanis berstatus aria-hidden.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut aria-hidden](output/222_aria_hidden.png)

- **Lokasi Source Code:** [222_aria_hidden.html](222_aria_hidden.html)

---

### 13. Atribut aria-live

- **Tujuan Pembelajaran:** Menyampaikan pesan pembaruan konten dinamis (AJAX/Fetch) kepada pengguna tunanetra.
- **Konsep Utama:** Nilai 'polite' menunggu jeda bicara pembaca layar, sedangkan 'assertive' memotong seketika.
- **Penjelasan Source Code:** Menampilkan kotak notifikasi hijau dengan atribut live region.
- **Cara Menjalankan:** Buka file `223_aria_live.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak notifikasi hijau ramah screen reader dengan status aria-live.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut aria-live](output/223_aria_live.png)

- **Lokasi Source Code:** [223_aria_live.html](223_aria_live.html)

---

### 14. Atribut aria-expanded

- **Tujuan Pembelajaran:** Memberikan status visual interaktif kepada teknologi asistif.
- **Konsep Utama:** Aria-expanded memberitahu apakah sub-konten yang dikontrol saat ini sedang terbuka atau tertutup.
- **Penjelasan Source Code:** Menampilkan tombol pemicu menu dengan metadata aria-expanded.
- **Cara Menjalankan:** Buka file `224_aria_expanded.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tombol menu abu-abu yang membawa atribut status buka-tutup.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut aria-expanded](output/224_aria_expanded.png)

- **Lokasi Source Code:** [224_aria_expanded.html](224_aria_expanded.html)

---

### 15. Atribut aria-controls

- **Tujuan Pembelajaran:** Membangun hubungan kendali semantik antara pemicu dan target konten.
- **Konsep Utama:** Aria-controls mempermudah navigasi pintas screen reader menuju panel target.
- **Penjelasan Source Code:** Menampilkan relasi tombol pemicu dengan panel target berlatar biru.
- **Cara Menjalankan:** Buka file `225_aria_controls.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tombol aksi biru yang terhubung secara semantik ke panel konten di bawahnya.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut aria-controls](output/225_aria_controls.png)

- **Lokasi Source Code:** [225_aria_controls.html](225_aria_controls.html)

---

### 16. Landmark roles

- **Tujuan Pembelajaran:** Memahami relasi tag semantik HTML5 dengan peran landmark ARIA.
- **Konsep Utama:** Gunakan elemen HTML5 asli jika tersedia, dan gunakan ARIA roles hanya sebagai pelengkap.
- **Penjelasan Source Code:** Menampilkan tabel padanan antara tag HTML5 dan ARIA landmark roles.
- **Cara Menjalankan:** Buka file `226_landmark_roles.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Daftar perbandingan elemen semantik HTML5 dan ARIA roles.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Landmark roles](output/226_landmark_roles.png)

- **Lokasi Source Code:** [226_landmark_roles.html](226_landmark_roles.html)

---

### 17. Tabel Aksesibel

- **Tujuan Pembelajaran:** Menyusun tabel data yang ramah bagi pengguna teknologi asistif suara.
- **Konsep Utama:** Atribut scope='col' dan scope='row' memungkinkan screen reader mengumumkan tajuk sebelum membaca sel data.
- **Penjelasan Source Code:** Menampilkan tabel jadwal belajar dua kolom dengan penataan aksesibel.
- **Cara Menjalankan:** Buka file `227_accessible_tables.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tabel data dua baris dengan tajuk kolom dan tajuk baris tegas.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Tabel Aksesibel](output/227_accessible_tables.png)

- **Lokasi Source Code:** [227_accessible_tables.html](227_accessible_tables.html)

---

### 18. Link Aksesibel

- **Tujuan Pembelajaran:** Menerapkan standar aksesibilitas tautan sesuai panduan WCAG.
- **Konsep Utama:** Teks link harus mandiri menjelaskan tujuan dan menyertakan peringatan jika membuka jendela baru.
- **Penjelasan Source Code:** Menampilkan tautan biru dengan kontras rasio tinggi dan penanda tab baru.
- **Cara Menjalankan:** Buka file `228_accessible_links.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tautan bergaris bawah dengan teks penjelasan tujuan yang transparan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Link Aksesibel](output/228_accessible_links.png)

- **Lokasi Source Code:** [228_accessible_links.html](228_accessible_links.html)

---

### 19. Tombol Aksesibel

- **Tujuan Pembelajaran:** Mengapa elemen <button> asli selalu lebih unggul dibanding div ber-role button.
- **Konsep Utama:** Elemen bawaan HTML memiliki fitur aksesibilitas keyboard gratis yang kokoh.
- **Penjelasan Source Code:** Menampilkan tombol button asli yang otomatis memenuhi standar aksesibilitas.
- **Cara Menjalankan:** Buka file `229_accessible_buttons.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tombol aksi biru asli peramban berfitur aksesibel bawaan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Tombol Aksesibel](output/229_accessible_buttons.png)

- **Lokasi Source Code:** [229_accessible_buttons.html](229_accessible_buttons.html)

---

### 20. Pemeriksaan Aksesibilitas HTML

- **Tujuan Pembelajaran:** Menguasai teknik audit dan pengujian kepatuhan aksesibilitas web.
- **Konsep Utama:** Audit mandiri menjamin aplikasi web inklusif dan lolos standar pengujian kepatuhan pemerintah.
- **Penjelasan Source Code:** Menampilkan daftar centang 5 butir pengujian aksesibilitas WCAG.
- **Cara Menjalankan:** Buka file `230_accessibility_testing.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Checklist evaluasi kepatuhan aksesibilitas dengan tanda centang hijau.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Pemeriksaan Aksesibilitas HTML](output/230_accessibility_testing.png)

- **Lokasi Source Code:** [230_accessibility_testing.html](230_accessibility_testing.html)

---

## Ringkasan Modul
Modul 13 menyajikan pondasi penting mengenai Aksesibilitas HTML. Pemahaman menyeluruh terhadap submodul di atas menjadi prasyarat penting sebelum melangkah ke modul berikutnya.
