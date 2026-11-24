# Modul 16: Elemen dan Atribut HTML Modern

## Ringkasan Ruang Lingkup Materi
Modul ini membahas konsep dasar dan implementasi praktis seputar **Elemen dan Atribut HTML Modern**. Setiap submodul dirancang secara terisolasi agar pembelajar dapat memahami konsep satu per satu secara fokus dan terstruktur.

## Tujuan Pembelajaran Modul
Setelah menyelesaikan modul ini, peserta didik diharapkan mampu memahami, mengimplementasikan, dan menguji komponen-komponen utama dalam lingkup elemen dan atribut html modern sesuai standar modern W3C.

## Daftar Materi atau Submodul

- [261_data_attributes.html](261_data_attributes.html) - Atribut data-*
- [262_contenteditable_attribute.html](262_contenteditable_attribute.html) - Atribut contenteditable
- [263_draggable_attribute.html](263_draggable_attribute.html) - Atribut draggable
- [264_hidden_attribute.html](264_hidden_attribute.html) - Atribut hidden
- [265_inert_attribute.html](265_inert_attribute.html) - Atribut inert
- [266_translate_attribute.html](266_translate_attribute.html) - Atribut translate
- [267_spellcheck_attribute.html](267_spellcheck_attribute.html) - Atribut spellcheck
- [268_inputmode_attribute.html](268_inputmode_attribute.html) - Atribut inputmode
- [269_enterkeyhint_attribute.html](269_enterkeyhint_attribute.html) - Atribut enterkeyhint
- [270_popover_attribute.html](270_popover_attribute.html) - Popover API Melalui Atribut HTML
- [271_popover_auto_manual.html](271_popover_auto_manual.html) - Mode Popover Auto dan Manual
- [272_template_element.html](272_template_element.html) - Elemen template
- [273_slot_element.html](273_slot_element.html) - Elemen slot
- [274_custom_elements_intro.html](274_custom_elements_intro.html) - Struktur Custom Elements
- [275_dialog_form_integration.html](275_dialog_form_integration.html) - Integrasi Dialog dan Formulir

---

## Pembahasan Setiap Submodul

### 1. Atribut data-*

- **Tujuan Pembelajaran:** Memahami pemanfaatan atribut data-* untuk menyimpan state lokal pada DOM.
- **Konsep Utama:** Atribut data-* memberikan jembatan bersih antara markup HTML dan skrip interaktif JavaScript.
- **Penjelasan Source Code:** Menampilkan kartu artikel yang membawa data atribut kustom dan tombol baca data.
- **Cara Menjalankan:** Buka file `261_data_attributes.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kartu informasi dengan tombol biru interaktif yang membaca nilai dataset.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut data-*](output/261_data_attributes.png)

- **Lokasi Source Code:** [261_data_attributes.html](261_data_attributes.html)

---

### 2. Atribut contenteditable

- **Tujuan Pembelajaran:** Membangun editor teks langsung (inline rich editor) dengan contenteditable.
- **Konsep Utama:** Pengguna dapat mengklik dan mengubah teks apa pun di dalam elemen tersebut seketika.
- **Penjelasan Source Code:** Menampilkan kotak bergaris putus-putus biru yang teksnya dapat diedit bebas.
- **Cara Menjalankan:** Buka file `262_contenteditable_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak interaktif penyunting teks berbingkai putus-putus biru.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut contenteditable](output/262_contenteditable_attribute.png)

- **Lokasi Source Code:** [262_contenteditable_attribute.html](262_contenteditable_attribute.html)

---

### 3. Atribut draggable

- **Tujuan Pembelajaran:** Mengaktifkan antarmuka seret-lepas bawaan browser menggunakan draggable='true'.
- **Konsep Utama:** Atribut ini memicu serangkaian event dragstart, dragover, dan drop.
- **Penjelasan Source Code:** Menampilkan kartu biru yang dapat diseret dengan kursor tangan.
- **Cara Menjalankan:** Buka file `263_draggable_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kartu biru tebal dengan kursor genggam (grab) yang siap diseret.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut draggable](output/263_draggable_attribute.png)

- **Lokasi Source Code:** [263_draggable_attribute.html](263_draggable_attribute.html)

---

### 4. Atribut hidden

- **Tujuan Pembelajaran:** Memahami cara menyembunyikan konten secara universal dengan atribut hidden.
- **Konsep Utama:** Elemen berstatus hidden tidak dirender di layar dan tidak dibaca oleh assistive technology.
- **Penjelasan Source Code:** Menampilkan kotak penjelasan mengenai mekanisme penyembunyian bawaan HTML.
- **Cara Menjalankan:** Buka file `264_hidden_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak informasi berstatus semantik mengenai sifat atribut hidden.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut hidden](output/264_hidden_attribute.png)

- **Lokasi Source Code:** [264_hidden_attribute.html](264_hidden_attribute.html)

---

### 5. Atribut inert

- **Tujuan Pembelajaran:** Menguasai teknik isolasi interaksi latar belakang modern dengan atribut inert.
- **Konsep Utama:** Inert secara otomatis memblokir pointer-events, keyboard focus, dan assistive tech sekaligus.
- **Penjelasan Source Code:** Menampilkan seksi formulir redup (opacity 0.5) yang terkunci dari interaksi.
- **Cara Menjalankan:** Buka file `265_inert_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Wilayah abu-abu transparan yang tidak dapat menerima klik atau fokus tab.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut inert](output/265_inert_attribute.png)

- **Lokasi Source Code:** [265_inert_attribute.html](265_inert_attribute.html)

---

### 6. Atribut translate

- **Tujuan Pembelajaran:** Melindungi nama merek, kode, atau istilah paten dari penerjemahan mesin otomatis.
- **Konsep Utama:** Atribut translate='no' mencegah distorsi makna nama dagang saat situs diterjemahkan.
- **Penjelasan Source Code:** Menampilkan kalimat dengan nama merek yang diproteksi translate='no'.
- **Cara Menjalankan:** Buka file `266_translate_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Teks paragraf dengan penanda nama merek biru yang terlindungi.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut translate](output/266_translate_attribute.png)

- **Lokasi Source Code:** [266_translate_attribute.html](266_translate_attribute.html)

---

### 7. Atribut spellcheck

- **Tujuan Pembelajaran:** Mengontrol fitur pemeriksa ejaan bawaan peramban dengan atribut spellcheck.
- **Konsep Utama:** Menonaktifkan spellcheck sangat ideal pada field kode lisensi, URL, atau istilah asing.
- **Penjelasan Source Code:** Menampilkan input teks kode yang bebas dari garis merah koreksi ejaan.
- **Cara Menjalankan:** Buka file `267_spellcheck_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field kode lisensi rapi tanpa gangguan garis koreksi ejaan merah.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut spellcheck](output/267_spellcheck_attribute.png)

- **Lokasi Source Code:** [267_spellcheck_attribute.html](267_spellcheck_attribute.html)

---

### 8. Atribut inputmode

- **Tujuan Pembelajaran:** Mengoptimalkan kenyamanan mengetik pengguna smartphone dengan inputmode.
- **Konsep Utama:** Inputmode mengubah jenis keyboard layar sentuh tanpa mengubah tipe data input.
- **Penjelasan Source Code:** Menampilkan field kode OTP dengan konfigurasi inputmode numerik.
- **Cara Menjalankan:** Buka file `268_inputmode_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak isian kode verifikasi OTP yang ramah keyboard ponsel.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut inputmode](output/268_inputmode_attribute.png)

- **Lokasi Source Code:** [268_inputmode_attribute.html](268_inputmode_attribute.html)

---

### 9. Atribut enterkeyhint

- **Tujuan Pembelajaran:** Memberikan petunjuk aksi yang jelas pada tombol Enter keyboard seluler.
- **Konsep Utama:** Nilai enter, done, go, next, search, atau send meningkatkan kejelasan aksi formulir.
- **Penjelasan Source Code:** Menampilkan input pencarian berkonfigurasi enterkeyhint='search'.
- **Cara Menjalankan:** Buka file `269_enterkeyhint_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field input pencarian dengan petunjuk tombol eksekusi pencarian.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut enterkeyhint](output/269_enterkeyhint_attribute.png)

- **Lokasi Source Code:** [269_enterkeyhint_attribute.html](269_enterkeyhint_attribute.html)

---

### 10. Popover API Melalui Atribut HTML

- **Tujuan Pembelajaran:** Mengimplementasikan Popover API HTML modern murni tanpa script.
- **Konsep Utama:** Elemen popover dirender di lapisan teratas (Top Layer) peramban dan mendukung light-dismiss.
- **Penjelasan Source Code:** Menampilkan tombol biru yang memicu gelembung popover terapung.
- **Cara Menjalankan:** Buka file `270_popover_attribute.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tombol biru pemicu gelembung popover mengambang bawaan HTML5.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Popover API Melalui Atribut HTML](output/270_popover_attribute.png)

- **Lokasi Source Code:** [270_popover_attribute.html](270_popover_attribute.html)

---

### 11. Mode Popover Auto dan Manual

- **Tujuan Pembelajaran:** Menguasai perbedaan mode popover auto dan manual.
- **Konsep Utama:** Mode manual ideal untuk notifikasi toast atau tooltip persisten yang butuh konfirmasi.
- **Penjelasan Source Code:** Menampilkan tombol popover manual dengan tombol penutup internal.
- **Cara Menjalankan:** Buka file `271_popover_auto_manual.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Popover mode manual berbingkai biru dengan tombol tutup khusus.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Mode Popover Auto dan Manual](output/271_popover_auto_manual.png)

- **Lokasi Source Code:** [271_popover_auto_manual.html](271_popover_auto_manual.html)

---

### 12. Elemen template

- **Tujuan Pembelajaran:** Memahami mekanisme cetak biru HTML dengan elemen <template>.
- **Konsep Utama:** Konten di dalam <template> tidak memicu request jaringan (gambar tidak diunduh) hingga dikloning.
- **Penjelasan Source Code:** Menampilkan tombol pengganda template yang menduplikasi kartu interaktif.
- **Cara Menjalankan:** Buka file `272_template_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Antarmuka kloning kartu dinamis berbasis tag template HTML5.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen template](output/272_template_element.png)

- **Lokasi Source Code:** [272_template_element.html](272_template_element.html)

---

### 13. Elemen slot

- **Tujuan Pembelajaran:** Mengenal prinsip komposisi komponen berbasis elemen <slot>.
- **Konsep Utama:** Slot memungkinkan pengembang menyuntikkan konten kustom ke dalam bayangan Shadow DOM yang terenkapsulasi.
- **Penjelasan Source Code:** Menampilkan visualisasi penampung slot judul dan konten.
- **Cara Menjalankan:** Buka file `273_slot_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Diagram visual penampung slot komponen bergaris putus-putus.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen slot](output/273_slot_element.png)

- **Lokasi Source Code:** [273_slot_element.html](273_slot_element.html)

---

### 14. Struktur Custom Elements

- **Tujuan Pembelajaran:** Mempelajari sintaks dasar registrasi tag HTML kustom sendiri dengan customElements API.
- **Konsep Utama:** Tag kustom harus memuat minimal satu tanda hubung (-) untuk membedakannya dari tag bawaan HTML.
- **Penjelasan Source Code:** Menampilkan elemen kustom <user-card> yang dirender aktif.
- **Cara Menjalankan:** Buka file `274_custom_elements_intro.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kartu komponen kustom biru muda hasil registrasi tag user-card.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Struktur Custom Elements](output/274_custom_elements_intro.png)

- **Lokasi Source Code:** [274_custom_elements_intro.html](274_custom_elements_intro.html)

---

### 15. Integrasi Dialog dan Formulir

- **Tujuan Pembelajaran:** Memadukan formulir interaktif dengan modal dialog bawaan peramban.
- **Konsep Utama:** Tombol submit pada form ber-method dialog otomatis menutup jendela modal dan mencatat nilai tombol.
- **Penjelasan Source Code:** Menampilkan tombol untuk membuka dialog pemilihan metode pembayaran.
- **Cara Menjalankan:** Buka file `275_dialog_form_integration.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tombol aktivasi modal pembayaran dengan form terpadu.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Integrasi Dialog dan Formulir](output/275_dialog_form_integration.png)

- **Lokasi Source Code:** [275_dialog_form_integration.html](275_dialog_form_integration.html)

---

## Ringkasan Modul
Modul 16 menyajikan pondasi penting mengenai Elemen dan Atribut HTML Modern. Pemahaman menyeluruh terhadap submodul di atas menjadi prasyarat penting sebelum melangkah ke modul berikutnya.
