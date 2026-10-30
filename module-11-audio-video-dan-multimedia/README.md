# Modul 11: Audio, Video, dan Multimedia

## Ringkasan Ruang Lingkup Materi
Modul ini membahas konsep dasar dan implementasi praktis seputar **Audio, Video, dan Multimedia**. Setiap submodul dirancang secara terisolasi agar pembelajar dapat memahami konsep satu per satu secara fokus dan terstruktur.

## Tujuan Pembelajaran Modul
Setelah menyelesaikan modul ini, peserta didik diharapkan mampu memahami, mengimplementasikan, dan menguji komponen-komponen utama dalam lingkup audio, video, dan multimedia sesuai standar modern W3C.

## Daftar Materi atau Submodul

- [181_audio_element.html](181_audio_element.html) - Elemen audio
- [182_audio_controls.html](182_audio_controls.html) - Kontrol audio
- [183_audio_sources.html](183_audio_sources.html) - Berbagai Sumber Audio
- [184_audio_fallback.html](184_audio_fallback.html) - Fallback audio
- [185_video_element.html](185_video_element.html) - Elemen video
- [186_video_controls.html](186_video_controls.html) - Kontrol video
- [187_video_dimensions.html](187_video_dimensions.html) - Dimensi video
- [188_video_poster.html](188_video_poster.html) - Atribut poster
- [189_video_sources.html](189_video_sources.html) - Berbagai Sumber Video
- [190_video_tracks.html](190_video_tracks.html) - Elemen track
- [191_video_subtitles.html](191_video_subtitles.html) - Subtitle video
- [192_webvtt_captions.html](192_webvtt_captions.html) - WebVTT Captions
- [193_audio_video_preload.html](193_audio_video_preload.html) - Atribut preload
- [194_iframe_video_embed.html](194_iframe_video_embed.html) - Menyematkan Video Melalui Iframe
- [195_multimedia_accessibility.html](195_multimedia_accessibility.html) - Aksesibilitas Multimedia

---

## Pembahasan Setiap Submodul

### 1. Elemen audio

- **Tujuan Pembelajaran:** Memahami pemutaran file audio digital dengan elemen <audio>.
- **Konsep Utama:** Elemen <audio> menyediakan pemutar suara terstandarisasi di semua peramban modern.
- **Penjelasan Source Code:** Menampilkan kontrol pemutar audio HTML5 dengan tombol putar dan bilah durasi.
- **Cara Menjalankan:** Buka file `181_audio_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Komponen pemutar suara audio bawaan dengan tombol play dan volume.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen audio](output/181_audio_element.png)

- **Lokasi Source Code:** [181_audio_element.html](181_audio_element.html)

---

### 2. Kontrol audio

- **Tujuan Pembelajaran:** Mengontrol pemutaran dan status audio dengan atribut controls dan muted.
- **Konsep Utama:** Atribut controls wajib dicantumkan jika ingin antarmuka pemutar suara terlihat oleh pengguna.
- **Penjelasan Source Code:** Menampilkan pemutar audio dalam status suara disenyapkan (muted).
- **Cara Menjalankan:** Buka file `182_audio_controls.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kontrol audio dengan ikon speaker bertanda silang senyap.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Kontrol audio](output/182_audio_controls.png)

- **Lokasi Source Code:** [182_audio_controls.html](182_audio_controls.html)

---

### 3. Berbagai Sumber Audio

- **Tujuan Pembelajaran:** Menjamin kompatibilitas lintas peramban menggunakan multi-sumber format suara.
- **Konsep Utama:** Peramban akan memilih format audio pertama yang kompatibel dengan codec sistemnya.
- **Penjelasan Source Code:** Menampilkan pemutar audio dengan tiga opsi source codec berbeda.
- **Cara Menjalankan:** Buka file `183_audio_sources.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Pemutar audio yang didukung tiga format berkas alternatif.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Berbagai Sumber Audio](output/183_audio_sources.png)

- **Lokasi Source Code:** [183_audio_sources.html](183_audio_sources.html)

---

### 4. Fallback audio

- **Tujuan Pembelajaran:** Menyediakan strategi fallback yang baik bagi pengguna dengan peramban terbatas.
- **Konsep Utama:** Konten di dalam tag audio diabaikan jika audio player didukung, dan tampil jika tidak didukung.
- **Penjelasan Source Code:** Menampilkan pemutar audio dengan tautan unduh alternatif.
- **Cara Menjalankan:** Buka file `184_audio_fallback.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Pemutar audio dengan teks cadangan unduh manual.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Fallback audio](output/184_audio_fallback.png)

- **Lokasi Source Code:** [184_audio_fallback.html](184_audio_fallback.html)

---

### 5. Elemen video

- **Tujuan Pembelajaran:** Memahami pemutaran berkas video digital menggunakan elemen <video>.
- **Konsep Utama:** Elemen <video> menghentikan ketergantungan pada plugin pihak ketiga kuno seperti Flash.
- **Penjelasan Source Code:** Menampilkan pemutar video hitam beresolusi 480x270 dengan kontrol play.
- **Cara Menjalankan:** Buka file `185_video_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Layar pemutar video hitam berbingkai rapi dengan kontrol bawaan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen video](output/185_video_element.png)

- **Lokasi Source Code:** [185_video_element.html](185_video_element.html)

---

### 6. Kontrol video

- **Tujuan Pembelajaran:** Mengoptimalkan pengalaman pemutaran video mobile dengan playsinline.
- **Konsep Utama:** Atribut controls mengaktifkan tombol play, pause, timeline, dan tombol layar penuh.
- **Penjelasan Source Code:** Menampilkan kontrol video lengkap dengan fitur inline playback.
- **Cara Menjalankan:** Buka file `186_video_controls.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Pemutar video dengan timeline interaktif dan tombol fullscreen.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Kontrol video](output/186_video_controls.png)

- **Lokasi Source Code:** [186_video_controls.html](186_video_controls.html)

---

### 7. Dimensi video

- **Tujuan Pembelajaran:** Mencegah pergeseran layout saat video dimuat menggunakan dimensi eksplisit.
- **Konsep Utama:** Menentukan width dan height mencegah browser merender ulang tata letak halaman.
- **Penjelasan Source Code:** Menampilkan video berdimensi presisi rasio 16:9.
- **Cara Menjalankan:** Buka file `187_video_dimensions.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Jendela pemutar video berdimensi 480x270 piksel terkunci.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Dimensi video](output/187_video_dimensions.png)

- **Lokasi Source Code:** [187_video_dimensions.html](187_video_dimensions.html)

---

### 8. Atribut poster

- **Tujuan Pembelajaran:** Meningkatkan daya tarik visual video dengan thumbnail poster yang relevan.
- **Konsep Utama:** Atribut poster menampilkan gambar pratinjau yang menarik saat video belum diputar.
- **Penjelasan Source Code:** Menampilkan pemutar video dengan gambar poster thumbnail merah-gelap.
- **Cara Menjalankan:** Buka file `188_video_poster.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Layar video menampilkan gambar poster thumbnail sebelum diputar.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut poster](output/188_video_poster.png)

- **Lokasi Source Code:** [188_video_poster.html](188_video_poster.html)

---

### 9. Berbagai Sumber Video

- **Tujuan Pembelajaran:** Menguasai negosiasi format video berbasis codec WebM dan MP4.
- **Konsep Utama:** Format WebM menawarkan ukuran berkas lebih ramping untuk browser Chromium dan Firefox.
- **Penjelasan Source Code:** Menampilkan video dengan dua format sumber berbeda.
- **Cara Menjalankan:** Buka file `189_video_sources.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Pemutar video dengan dukungan multi-codec efisien.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Berbagai Sumber Video](output/189_video_sources.png)

- **Lokasi Source Code:** [189_video_sources.html](189_video_sources.html)

---

### 10. Elemen track

- **Tujuan Pembelajaran:** Menyematkan berkas trek teks menggunakan elemen <track>.
- **Konsep Utama:** Tag <track> adalah void element yang menghubungkan berkas format .vtt dengan video.
- **Penjelasan Source Code:** Menampilkan pemutar video yang dilengkapi opsi menu subtitle.
- **Cara Menjalankan:** Buka file `190_video_tracks.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Video player dengan tombol CC (Closed Captions) aktif.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen track](output/190_video_tracks.png)

- **Lokasi Source Code:** [190_video_tracks.html](190_video_tracks.html)

---

### 11. Subtitle video

- **Tujuan Pembelajaran:** Memfasilitasi penonton internasional dengan trek terjemahan bahasa.
- **Konsep Utama:** Atribut kind='subtitles' dikhususkan untuk terjemahan dialog bagi penonton yang mengerti suaranya namun beda bahasa.
- **Penjelasan Source Code:** Menampilkan pemutar video dengan pilihan subtitle bahasa Indonesia dan Inggris.
- **Cara Menjalankan:** Buka file `191_video_subtitles.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Video player dengan dua opsi bahasa subtitle.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Subtitle video](output/191_video_subtitles.png)

- **Lokasi Source Code:** [191_video_subtitles.html](191_video_subtitles.html)

---

### 12. WebVTT Captions

- **Tujuan Pembelajaran:** Memahami sintaks berkas WebVTT (.vtt) untuk aksesibilitas tunarungu.
- **Konsep Utama:** Takarir captions (kind='captions') menyertakan transkrip dialog serta deskripsi audio non-verbal.
- **Penjelasan Source Code:** Menampilkan contoh format sintaks penulisan berkas WebVTT standar W3C.
- **Cara Menjalankan:** Buka file `192_webvtt_captions.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Blok kode berkas teks WebVTT dengan stempel waktu dan teks narasi.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi WebVTT Captions](output/192_webvtt_captions.png)

- **Lokasi Source Code:** [192_webvtt_captions.html](192_webvtt_captions.html)

---

### 13. Atribut preload

- **Tujuan Pembelajaran:** Mengelola konsumsi bandwidth server dan pengguna dengan atribut preload.
- **Konsep Utama:** Preload='none' mencegah browser mengunduh megabyte video secara sia-sia sebelum diminta.
- **Penjelasan Source Code:** Menampilkan video yang dikonfigurasi hemat data dengan preload='none'.
- **Cara Menjalankan:** Buka file `193_audio_video_preload.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Pemutar video hemat bandwidth dengan poster thumbnail siap putar.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut preload](output/193_audio_video_preload.png)

- **Lokasi Source Code:** [193_audio_video_preload.html](193_audio_video_preload.html)

---

### 14. Menyematkan Video Melalui Iframe

- **Tujuan Pembelajaran:** Mengintegrasikan video streaming pihak ketiga secara responsif dan aman.
- **Konsep Utama:** Iframe memungkinkan pemutaran video tanpa membebani penyimpanan hosting sendiri.
- **Penjelasan Source Code:** Menampilkan bingkai iframe video dengan izin fullscreen.
- **Cara Menjalankan:** Buka file `194_iframe_video_embed.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Bingkai pemutar video tersemat berlatar belakang gelap rapi.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Menyematkan Video Melalui Iframe](output/194_iframe_video_embed.png)

- **Lokasi Source Code:** [194_iframe_video_embed.html](194_iframe_video_embed.html)

---

### 15. Aksesibilitas Multimedia

- **Tujuan Pembelajaran:** Menyajikan alternatif teks transkripsi untuk aksesibilitas tuna rungu.
- **Konsep Utama:** Transkrip teks di bawah media memastikan seluruh konten dapat dinikmati oleh semua pengguna.
- **Penjelasan Source Code:** Menampilkan pemutar audio disertai panel akordeon transkrip teks lengkap.
- **Cara Menjalankan:** Buka file `195_multimedia_accessibility.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Pemutar suara dengan akordeon transkrip teks interaktif di bawahnya.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Aksesibilitas Multimedia](output/195_multimedia_accessibility.png)

- **Lokasi Source Code:** [195_multimedia_accessibility.html](195_multimedia_accessibility.html)

---

## Ringkasan Modul
Modul 11 menyajikan pondasi penting mengenai Audio, Video, dan Multimedia. Pemahaman menyeluruh terhadap submodul di atas menjadi prasyarat penting sebelum melangkah ke modul berikutnya.
