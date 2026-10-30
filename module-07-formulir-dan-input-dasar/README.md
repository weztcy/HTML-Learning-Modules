# Modul 7: Formulir dan Input Dasar

## Ringkasan Ruang Lingkup Materi
Modul ini membahas konsep dasar dan implementasi praktis seputar **Formulir dan Input Dasar**. Setiap submodul dirancang secara terisolasi agar pembelajar dapat memahami konsep satu per satu secara fokus dan terstruktur.

## Tujuan Pembelajaran Modul
Setelah menyelesaikan modul ini, peserta didik diharapkan mampu memahami, mengimplementasikan, dan menguji komponen-komponen utama dalam lingkup formulir dan input dasar sesuai standar modern W3C.

## Daftar Materi atau Submodul

- [96_basic_form.html](96_basic_form.html) - Formulir Dasar
- [97_form_action.html](97_form_action.html) - Atribut action
- [98_form_method.html](98_form_method.html) - Atribut method
- [99_form_get_method.html](99_form_get_method.html) - Formulir dengan Metode GET
- [100_form_post_method.html](100_form_post_method.html) - Formulir dengan Metode POST
- [101_input_text.html](101_input_text.html) - Input Teks
- [102_input_password.html](102_input_password.html) - Input Kata Sandi
- [103_input_email.html](103_input_email.html) - Input Email
- [104_input_number.html](104_input_number.html) - Input Angka
- [105_input_tel.html](105_input_tel.html) - Input Nomor Telepon
- [106_input_url.html](106_input_url.html) - Input URL
- [107_input_search.html](107_input_search.html) - Input Pencarian
- [108_input_date.html](108_input_date.html) - Input Tanggal
- [109_input_time.html](109_input_time.html) - Input Waktu
- [110_input_datetime_local.html](110_input_datetime_local.html) - Input Tanggal dan Waktu
- [111_input_month.html](111_input_month.html) - Input Bulan
- [112_input_week.html](112_input_week.html) - Input Minggu
- [113_input_color.html](113_input_color.html) - Input Warna
- [114_input_range.html](114_input_range.html) - Input Rentang (Slider)
- [115_input_checkbox.html](115_input_checkbox.html) - Input Checkbox
- [116_input_radio.html](116_input_radio.html) - Input Radio
- [117_input_file.html](117_input_file.html) - Input File
- [118_input_hidden.html](118_input_hidden.html) - Input Hidden
- [119_input_submit.html](119_input_submit.html) - Tombol Submit
- [120_input_reset.html](120_input_reset.html) - Tombol Reset
- [121_button_element.html](121_button_element.html) - Elemen button
- [122_textarea_element.html](122_textarea_element.html) - Elemen textarea
- [123_select_element.html](123_select_element.html) - Elemen select
- [124_option_element.html](124_option_element.html) - Elemen option
- [125_optgroup_element.html](125_optgroup_element.html) - Elemen optgroup

---

## Pembahasan Setiap Submodul

### 1. Formulir Dasar

- **Tujuan Pembelajaran:** Memahami struktur tag <form> sebagai penampung kontrol input.
- **Konsep Utama:** Elemen <form> mengoordinasikan pengiriman data pengguna ke server.
- **Penjelasan Source Code:** Menampilkan formulir input teks dengan tombol kirim biru.
- **Cara Menjalankan:** Buka file `96_basic_form.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Formulir dasar dengan satu kolom isian nama dan tombol kirim.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Formulir Dasar](output/96_basic_form.png)

- **Lokasi Source Code:** [96_basic_form.html](96_basic_form.html)

---

### 2. Atribut action

- **Tujuan Pembelajaran:** Menentukan URL target pengolahan data dengan atribut action.
- **Konsep Utama:** Atribut action berisi URI tempat browser mengirim payload form.
- **Penjelasan Source Code:** Menampilkan formulir registrasi yang menargetkan endpoint /api/v1/pendaftaran.
- **Cara Menjalankan:** Buka file `97_form_action.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Formulir email dengan keterangan endpoint tujuan yang jelas.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut action](output/97_form_action.png)

- **Lokasi Source Code:** [97_form_action.html](97_form_action.html)

---

### 3. Atribut method

- **Tujuan Pembelajaran:** Memilih metode HTTP yang tepat (GET vs POST) sesuai kebutuhan keamanan dan fungsi.
- **Konsep Utama:** GET menyertakan parameter di URL, sedangkan POST menyembunyikannya dalam request body.
- **Penjelasan Source Code:** Menyajikan dua kartu perbandingan karakteristik metode GET dan POST.
- **Cara Menjalankan:** Buka file `98_form_method.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Dua kartu komparasi karakteristik metode GET dan POST berdampingan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut method](output/98_form_method.png)

- **Lokasi Source Code:** [98_form_method.html](98_form_method.html)

---

### 4. Formulir dengan Metode GET

- **Tujuan Pembelajaran:** Mengimplementasikan form pencarian menggunakan metode GET.
- **Konsep Utama:** Metode GET ideal untuk pencarian karena URL hasilnya dapat dibookmark atau dibagikan.
- **Penjelasan Source Code:** Menampilkan form pencarian yang memetakan input ke parameter query URL 'q'.
- **Cara Menjalankan:** Buka file `99_form_get_method.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Input pencarian dengan tombol 'Cari Artikel' bergaya modern.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Formulir dengan Metode GET](output/99_form_get_method.png)

- **Lokasi Source Code:** [99_form_get_method.html](99_form_get_method.html)

---

### 5. Formulir dengan Metode POST

- **Tujuan Pembelajaran:** Mengamankan data kredensial sensitif menggunakan metode POST.
- **Konsep Utama:** POST mencegah data sandi terekam di riwayat peramban atau log server proxy.
- **Penjelasan Source Code:** Menampilkan form otentikasi login dengan input nama dan password bertipe post.
- **Cara Menjalankan:** Buka file `100_form_post_method.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Formulir login yang rapi dengan field username dan password.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Formulir dengan Metode POST](output/100_form_post_method.png)

- **Lokasi Source Code:** [100_form_post_method.html](100_form_post_method.html)

---

### 6. Input Teks

- **Tujuan Pembelajaran:** Menguasai kontrol input teks satu baris standar HTML.
- **Konsep Utama:** Tipe input text adalah kontrol isian serbaguna untuk karakter alfanumerik.
- **Penjelasan Source Code:** Menampilkan field teks nama lengkap dengan placeholder yang informatif.
- **Cara Menjalankan:** Buka file `101_input_text.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak isian teks ber-border halus dengan fokus interaktif.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Teks](output/101_input_text.png)

- **Lokasi Source Code:** [101_input_text.html](101_input_text.html)

---

### 7. Input Kata Sandi

- **Tujuan Pembelajaran:** Menjaga privasi input pengguna dengan menyamarkan karakter sandi.
- **Konsep Utama:** Atribut type='password' mencegah orang lain di sekitar melihat karakter yang diketik.
- **Penjelasan Source Code:** Menampilkan field input sandi yang otomatis mengaburkan teks menjadi bulatan hitam.
- **Cara Menjalankan:** Buka file `102_input_password.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field kata sandi dengan proteksi penyamaran karakter visual.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Kata Sandi](output/102_input_password.png)

- **Lokasi Source Code:** [102_input_password.html](102_input_password.html)

---

### 8. Input Email

- **Tujuan Pembelajaran:** Menerapkan validasi sintaks alamat surel bawaan peramban.
- **Konsep Utama:** Atribut type='email' mengaktifkan validasi sintaks alamat surel sebelum formulir dikirim.
- **Penjelasan Source Code:** Menampilkan field email yang menolak pengiriman jika format @domain tidak lengkap.
- **Cara Menjalankan:** Buka file `103_input_email.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field email dengan tombol uji validasi format peramban.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Email](output/103_input_email.png)

- **Lokasi Source Code:** [103_input_email.html](103_input_email.html)

---

### 9. Input Angka

- **Tujuan Pembelajaran:** Mengontrol masukan nilai numerik dengan batas rentang min dan max.
- **Konsep Utama:** Input number menyediakan kontrol stepper panah dan memfilter karakter non-angka.
- **Penjelasan Source Code:** Menampilkan input angka tiket dengan nilai awal 1 dan batasan rentang 1-10.
- **Cara Menjalankan:** Buka file `104_input_number.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field angka dengan kontrol tombol panah stepper otomatis di sebelah kanan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Angka](output/104_input_number.png)

- **Lokasi Source Code:** [104_input_number.html](104_input_number.html)

---

### 10. Input Nomor Telepon

- **Tujuan Pembelajaran:** Menyediakan kontrol input ramah perangkat mobile untuk nomor telepon.
- **Konsep Utama:** Tipe tel memanggil dialpad angka di perangkat layar sentuh ponsel pintar.
- **Penjelasan Source Code:** Menampilkan field input nomor telepon berformat internasional.
- **Cara Menjalankan:** Buka file `105_input_tel.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak isian nomor telepon dengan placeholder format Indonesia.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Nomor Telepon](output/105_input_tel.png)

- **Lokasi Source Code:** [105_input_tel.html](105_input_tel.html)

---

### 11. Input URL

- **Tujuan Pembelajaran:** Memvalidasi tautan web yang valid dengan skema protokol.
- **Konsep Utama:** Input url memvalidasi apakah nilai yang dimasukkan diawali oleh skema seperti http:// atau https://.
- **Penjelasan Source Code:** Menampilkan input URL yang menuntut format web tautan valid.
- **Cara Menjalankan:** Buka file `106_input_url.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field input URL berpenanda placeholder protokol https://.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input URL](output/106_input_url.png)

- **Lokasi Source Code:** [106_input_url.html](106_input_url.html)

---

### 12. Input Pencarian

- **Tujuan Pembelajaran:** Mengoptimalkan pengalaman pencarian pengguna dengan type='search'.
- **Konsep Utama:** Input search menyediakan semantik pencarian dan kontrol pembersihan teks otomatis.
- **Penjelasan Source Code:** Menampilkan field pencarian dengan sudut membulat elegan.
- **Cara Menjalankan:** Buka file `107_input_search.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field pencarian modern yang mendukung tombol reset cepat.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Pencarian](output/107_input_search.png)

- **Lokasi Source Code:** [107_input_search.html](107_input_search.html)

---

### 13. Input Tanggal

- **Tujuan Pembelajaran:** Memanfaatkan pemilih tanggal bawaan tanpa library datepicker eksternal.
- **Konsep Utama:** Input date menjamin format data ISO 8601 YYYY-MM-DD yang seragam ke server.
- **Penjelasan Source Code:** Menampilkan input tanggal dengan kalender visual bawaan.
- **Cara Menjalankan:** Buka file `108_input_date.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field tanggal lengkap dengan ikon kalender interaktif peramban.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Tanggal](output/108_input_date.png)

- **Lokasi Source Code:** [108_input_date.html](108_input_date.html)

---

### 14. Input Waktu

- **Tujuan Pembelajaran:** Mengatur masukan jam dan menit secara presisi dengan type='time'.
- **Konsep Utama:** Input time mengunci format waktu jam:menit sesuai standar lokal sistem operasi.
- **Penjelasan Source Code:** Menampilkan pemilih waktu pertemuan dengan nilai default pukul 09:00.
- **Cara Menjalankan:** Buka file `109_input_time.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field pemilih waktu dengan ikon jam di sebelah kanan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Waktu](output/109_input_time.png)

- **Lokasi Source Code:** [109_input_time.html](109_input_time.html)

---

### 15. Input Tanggal dan Waktu

- **Tujuan Pembelajaran:** Memilih tanggal dan jam sekaligus dalam satu komponen form terpadu.
- **Konsep Utama:** Format datetime-local menghasilkan string ISO kombinasi tanggal dan jam (YYYY-MM-DDTHH:MM).
- **Penjelasan Source Code:** Menampilkan pemilih tanggal-waktu terpadu untuk penjadwalan acara.
- **Cara Menjalankan:** Buka file `110_input_datetime_local.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field terpadu tanggal dan jam dengan kontrol kalender ganda.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Tanggal dan Waktu](output/110_input_datetime_local.png)

- **Lokasi Source Code:** [110_input_datetime_local.html](110_input_datetime_local.html)

---

### 16. Input Bulan

- **Tujuan Pembelajaran:** Mengelola pemilihan bulan dan tahun tanpa memilih tanggal harian.
- **Konsep Utama:** Sangat ideal untuk masa berlaku kartu pembayaran atau periode laporan bulanan.
- **Penjelasan Source Code:** Menampilkan kontrol pemilih bulan dengan format tahun 2026.
- **Cara Menjalankan:** Buka file `111_input_month.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field bulan dan tahun dengan kalender tingkat bulan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Bulan](output/111_input_month.png)

- **Lokasi Source Code:** [111_input_month.html](111_input_month.html)

---

### 17. Input Minggu

- **Tujuan Pembelajaran:** Menentukan periode kerja mingguan berdasarkan standar nomor minggu kalender.
- **Konsep Utama:** Format data type='week' berguna untuk sistem manajemen proyek dan sprint Agile.
- **Penjelasan Source Code:** Menampilkan pemilih minggu kerja proyek.
- **Cara Menjalankan:** Buka file `112_input_week.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field seleksi nomor minggu dalam setahun.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Minggu](output/112_input_week.png)

- **Lokasi Source Code:** [112_input_week.html](112_input_week.html)

---

### 18. Input Warna

- **Tujuan Pembelajaran:** Mengintegrasikan palet pemilih warna visual dengan type='color'.
- **Konsep Utama:** Input color mengembalikan nilai heksadesimal 7 karakter (misal: #2563eb).
- **Penjelasan Source Code:** Menampilkan swatch kotak warna interaktif yang dapat diklik.
- **Cara Menjalankan:** Buka file `113_input_color.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tombol swatch warna biru dengan antarmuka picker peramban.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Warna](output/113_input_color.png)

- **Lokasi Source Code:** [113_input_color.html](113_input_color.html)

---

### 19. Input Rentang (Slider)

- **Tujuan Pembelajaran:** Membuat pengatur nilai numerik berbasis tuas geser (slider).
- **Konsep Utama:** Input range sangat intuitif untuk pengaturan persentase, volume suara, atau brightness.
- **Penjelasan Source Code:** Menampilkan tuas penggeser horizontal dengan nilai posisi 70%.
- **Cara Menjalankan:** Buka file `114_input_range.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Slider pengatur nilai horizontal interaktif.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Rentang (Slider)](output/114_input_range.png)

- **Lokasi Source Code:** [114_input_range.html](114_input_range.html)

---

### 20. Input Checkbox

- **Tujuan Pembelajaran:** Mengelola pemilihan beberapa pilihan sekaligus menggunakan checkbox.
- **Konsep Utama:** Setiap kotak centang bersifat independen dan dapat dicentang secara bersamaan.
- **Penjelasan Source Code:** Menampilkan tiga opsi keahlian dengan opsi HTML5 sudah tercentang awal.
- **Cara Menjalankan:** Buka file `115_input_checkbox.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Daftar kotak centang dengan opsi pertama bertanda centang aktif.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Checkbox](output/115_input_checkbox.png)

- **Lokasi Source Code:** [115_input_checkbox.html](115_input_checkbox.html)

---

### 21. Input Radio

- **Tujuan Pembelajaran:** Menguasai pemilihan tunggal eksklusif dengan tombol radio.
- **Konsep Utama:** Kunci radio button berada pada kesamaan atribut name yang mengelompokkannya.
- **Penjelasan Source Code:** Menampilkan dua opsi paket langganan dengan pilihan tunggal eksklusif.
- **Cara Menjalankan:** Buka file `116_input_radio.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Dua tombol lingkaran radio dengan opsi 'Paket Pemula' terpilih aktif.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Radio](output/116_input_radio.png)

- **Lokasi Source Code:** [116_input_radio.html](116_input_radio.html)

---

### 22. Input File

- **Tujuan Pembelajaran:** Memahami mekanisme unggah file dari sistem penyimpanan pengguna.
- **Konsep Utama:** Formulir pengunggah berkas wajib menggunakan metode POST dan enctype multipart/form-data.
- **Penjelasan Source Code:** Menampilkan tombol 'Choose File' peramban untuk memilih dokumen lokal.
- **Cara Menjalankan:** Buka file `117_input_file.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field pengunggah file dengan tombol pemilihan berkas sistem operasi.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input File](output/117_input_file.png)

- **Lokasi Source Code:** [117_input_file.html](117_input_file.html)

---

### 23. Input Hidden

- **Tujuan Pembelajaran:** Mengirimkan state data atau token keamanan tanpa mengganggu antarmuka visual.
- **Konsep Utama:** Input hidden bernilai tetap yang terkirim bersama payload form tanpa tampilan fisik.
- **Penjelasan Source Code:** Menampilkan formulir yang membawa data token rahasia secara aman.
- **Cara Menjalankan:** Buka file `118_input_hidden.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Teks konfirmasi keamanan dengan tombol aksi kirim tanpa field fisik tambahan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Input Hidden](output/118_input_hidden.png)

- **Lokasi Source Code:** [118_input_hidden.html](118_input_hidden.html)

---

### 24. Tombol Submit

- **Tujuan Pembelajaran:** Memahami tombol eksekusi submit bawaan tag input.
- **Konsep Utama:** Input type='submit' memicu event submit pada form dan validasi otomatis.
- **Penjelasan Source Code:** Menampilkan tombol pengiriman bertipe input submit berwarna biru.
- **Cara Menjalankan:** Buka file `119_input_submit.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tombol submit biru dengan teks nilai kustom 'Kirim Data Formulir'.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Tombol Submit](output/119_input_submit.png)

- **Lokasi Source Code:** [119_input_submit.html](119_input_submit.html)

---

### 25. Tombol Reset

- **Tujuan Pembelajaran:** Mempelajari fungsi tombol pembersihan form dengan type='reset'.
- **Konsep Utama:** Tombol reset merestorasi seluruh nilai kontrol form kembali ke nilai default saat dimuat.
- **Penjelasan Source Code:** Menampilkan field teks yang dilengkapi tombol reset abu-abu.
- **Cara Menjalankan:** Buka file `120_input_reset.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Field input dan tombol abu-abu reset yang mengembalikan nilai awal.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Tombol Reset](output/120_input_reset.png)

- **Lokasi Source Code:** [120_input_reset.html](120_input_reset.html)

---

### 26. Elemen button

- **Tujuan Pembelajaran:** Menguasai tag <button> untuk kontrol interaktif antarmuka yang fleksibel.
- **Konsep Utama:** Elemen <button> memiliki tag penutup sehingga dapat memuat markup HTML lain di dalamnya.
- **Penjelasan Source Code:** Menampilkan dua tombol tombol berpenampilan modern dengan icon teks.
- **Cara Menjalankan:** Buka file `121_button_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Dua tombol interaktif berdampingan: tombol abu-abu dan tombol biru tebal.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen button](output/121_button_element.png)

- **Lokasi Source Code:** [121_button_element.html](121_button_element.html)

---

### 27. Elemen textarea

- **Tujuan Pembelajaran:** Mengimplementasikan kontrol teks multibaris dengan elemen <textarea>.
- **Konsep Utama:** Elemen <textarea> membungkus teks default di antara tag pembuka dan penutupnya.
- **Penjelasan Source Code:** Menampilkan kotak input pesan 4 baris yang dapat diperbesar pengguna.
- **Cara Menjalankan:** Buka file `122_textarea_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak isian teks luas multibarir dengan placeholder panduan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen textarea](output/122_textarea_element.png)

- **Lokasi Source Code:** [122_textarea_element.html](122_textarea_element.html)

---

### 28. Elemen select

- **Tujuan Pembelajaran:** Membuat komponen dropdown menu pilihan dengan tag <select>.
- **Konsep Utama:** Elemen <select> menghemat ruang layar dengan menyembunyikan opsi hingga dibuka.
- **Penjelasan Source Code:** Menampilkan dropdown pemilih kota dengan opsi default pemandu.
- **Cara Menjalankan:** Buka file `123_select_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak dropdown menu dengan ikon panah bawah bawaan peramban.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen select](output/123_select_element.png)

- **Lokasi Source Code:** [123_select_element.html](123_select_element.html)

---

### 29. Elemen option

- **Tujuan Pembelajaran:** Menguasai konfigurasi butir opsi dropdown dengan atribut value dan selected.
- **Konsep Utama:** Atribut selected menetapkan opsi default yang langsung aktif saat halaman dibuka.
- **Penjelasan Source Code:** Menampilkan menu dropdown bahasa dengan bahasa Inggris terpilih otomatis.
- **Cara Menjalankan:** Buka file `124_option_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Dropdown pilihan bahasa dengan opsi 'English' terpilih sejak awal.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen option](output/124_option_element.png)

- **Lokasi Source Code:** [124_option_element.html](124_option_element.html)

---

### 30. Elemen optgroup

- **Tujuan Pembelajaran:** Mengelompokkan puluhan opsi pilihan dengan label tajuk kategori via <optgroup>.
- **Konsep Utama:** Elemen <optgroup> meningkatkan navigasi dropdown dengan memisahkan grup opsi.
- **Penjelasan Source Code:** Menampilkan dropdown kendaraan dengan dua kategori tebal: Sepeda Motor dan Mobil Pribadi.
- **Cara Menjalankan:** Buka file `125_optgroup_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Dropdown hierarkis dengan judul kategori abu-abu tebal yang tidak dapat dipilih.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen optgroup](output/125_optgroup_element.png)

- **Lokasi Source Code:** [125_optgroup_element.html](125_optgroup_element.html)

---

## Ringkasan Modul
Modul 7 menyajikan pondasi penting mengenai Formulir dan Input Dasar. Pemahaman menyeluruh terhadap submodul di atas menjadi prasyarat penting sebelum melangkah ke modul berikutnya.
