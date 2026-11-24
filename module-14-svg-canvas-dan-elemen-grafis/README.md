# Modul 14: SVG, Canvas, dan Elemen Grafis

## Ringkasan Ruang Lingkup Materi
Modul ini membahas konsep dasar dan implementasi praktis seputar **SVG, Canvas, dan Elemen Grafis**. Setiap submodul dirancang secara terisolasi agar pembelajar dapat memahami konsep satu per satu secara fokus dan terstruktur.

## Tujuan Pembelajaran Modul
Setelah menyelesaikan modul ini, peserta didik diharapkan mampu memahami, mengimplementasikan, dan menguji komponen-komponen utama dalam lingkup svg, canvas, dan elemen grafis sesuai standar modern W3C.

## Daftar Materi atau Submodul

- [231_svg_inline.html](231_svg_inline.html) - SVG Inline
- [232_svg_shapes.html](232_svg_shapes.html) - Bentuk Dasar SVG
- [233_svg_rectangle.html](233_svg_rectangle.html) - Elemen rect
- [234_svg_circle.html](234_svg_circle.html) - Elemen circle
- [235_svg_ellipse.html](235_svg_ellipse.html) - Elemen ellipse
- [236_svg_line.html](236_svg_line.html) - Elemen line
- [237_svg_polygon.html](237_svg_polygon.html) - Elemen polygon
- [238_svg_polyline.html](238_svg_polyline.html) - Elemen polyline
- [239_svg_path.html](239_svg_path.html) - Elemen path
- [240_svg_text.html](240_svg_text.html) - Teks dalam SVG
- [241_svg_viewbox.html](241_svg_viewbox.html) - Atribut viewBox
- [242_svg_accessibility.html](242_svg_accessibility.html) - Aksesibilitas SVG
- [243_canvas_element.html](243_canvas_element.html) - Elemen canvas
- [244_canvas_fallback.html](244_canvas_fallback.html) - Fallback canvas
- [245_svg_vs_canvas.html](245_svg_vs_canvas.html) - Perbandingan SVG dan Canvas

---

## Pembahasan Setiap Submodul

### 1. SVG Inline

- **Tujuan Pembelajaran:** Memahami konsep penyematan SVG inline langsung pada struktur DOM.
- **Konsep Utama:** SVG inline dapat dimanipulasi dengan CSS dan JavaScript seperti elemen HTML biasa.
- **Penjelasan Source Code:** Menampilkan persegi panjang biru vektor berujung lengkung dengan teks di tengah.
- **Cara Menjalankan:** Buka file `231_svg_inline.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Grafik vektor tajam berlatar persegi panjang biru.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi SVG Inline](output/231_svg_inline.png)

- **Lokasi Source Code:** [231_svg_inline.html](231_svg_inline.html)

---

### 2. Bentuk Dasar SVG

- **Tujuan Pembelajaran:** Mengenali kumpulan bentuk geometris bawaan elemen SVG.
- **Konsep Utama:** Setiap elemen bentuk memiliki atribut posisi koordinat dan gaya warna isian (fill/stroke).
- **Penjelasan Source Code:** Menampilkan 4 bentuk geometris berdampingan: persegi biru, lingkaran merah, garis hijau, bintang kuning.
- **Cara Menjalankan:** Buka file `232_svg_shapes.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kanvas vektor yang memamerkan empat bentuk geometri beraneka warna.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Bentuk Dasar SVG](output/232_svg_shapes.png)

- **Lokasi Source Code:** [232_svg_shapes.html](232_svg_shapes.html)

---

### 3. Elemen rect

- **Tujuan Pembelajaran:** Menguasai pembuatan bangun persegi panjang dengan elemen <rect>.
- **Konsep Utama:** Atribut rx dan ry menentukan radius kelengkungan sudut persegi.
- **Penjelasan Source Code:** Menampilkan kartu persegi panjang ungu bersudut melengkung halus.
- **Cara Menjalankan:** Buka file `233_svg_rectangle.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Persegi panjang ungu berbingkai gelap dengan sudut membulat elegan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen rect](output/233_svg_rectangle.png)

- **Lokasi Source Code:** [233_svg_rectangle.html](233_svg_rectangle.html)

---

### 4. Elemen circle

- **Tujuan Pembelajaran:** Membuat bangun lingkaran presisi menggunakan elemen <circle>.
- **Konsep Utama:** Koordinat cx dan cy menempatkan titik pusat lingkaran di dalam kanvas.
- **Penjelasan Source Code:** Menampilkan lingkaran merah muda cerah berbingkai tegas.
- **Cara Menjalankan:** Buka file `234_svg_circle.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Lingkaran merah muda tajam berpusat presisi di tengah kanvas.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen circle](output/234_svg_circle.png)

- **Lokasi Source Code:** [234_svg_circle.html](234_svg_circle.html)

---

### 5. Elemen ellipse

- **Tujuan Pembelajaran:** Memahami parameter bangun lonjong elips dengan <ellipse>.
- **Konsep Utama:** Perbedaan nilai rx dan ry menciptakan proporsi bentuk lonjong yang diinginkan.
- **Penjelasan Source Code:** Menampilkan bangun elips toska horizontal.
- **Cara Menjalankan:** Buka file `235_svg_ellipse.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Bangun elips toska lonjong dengan garis tepi hijau gelap.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen ellipse](output/235_svg_ellipse.png)

- **Lokasi Source Code:** [235_svg_ellipse.html](235_svg_ellipse.html)

---

### 6. Elemen line

- **Tujuan Pembelajaran:** Menggambar segmen garis lurus presisi dengan elemen <line>.
- **Konsep Utama:** Atribut stroke, stroke-width, dan stroke-linecap mengontrol ketebalan serta ujung garis.
- **Penjelasan Source Code:** Menampilkan garis oranye tebal diagonal berujung melengkung.
- **Cara Menjalankan:** Buka file `236_svg_line.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Garis diagonal oranye tegas membentang dari kiri bawah ke kanan atas.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen line](output/236_svg_line.png)

- **Lokasi Source Code:** [236_svg_line.html](236_svg_line.html)

---

### 7. Elemen polygon

- **Tujuan Pembelajaran:** Membuat bentuk poligon bebas seperti segitiga atau segi lima dengan <polygon>.
- **Konsep Utama:** Titik akhir koordinat points secara otomatis terhubung kembali ke titik awal.
- **Penjelasan Source Code:** Menampilkan bangun segitiga ungu teratur dengan garis batas gelap.
- **Cara Menjalankan:** Buka file `237_svg_polygon.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Segitiga ungu simetris bergaris tepi tegas.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen polygon](output/237_svg_polygon.png)

- **Lokasi Source Code:** [237_svg_polygon.html](237_svg_polygon.html)

---

### 8. Elemen polyline

- **Tujuan Pembelajaran:** Membuat grafik garis data terbuka (chart trend line) dengan <polyline>.
- **Konsep Utama:** Polyline tidak menutup area secara otomatis, sangat ideal untuk diagram tren fluktuasi data.
- **Penjelasan Source Code:** Menampilkan grafik garis berombak biru yang menggambarkan tren data naik turun.
- **Cara Menjalankan:** Buka file `238_svg_polyline.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Grafik garis tren data berliku biru di atas kanvas abu-abu terang.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen polyline](output/238_svg_polyline.png)

- **Lokasi Source Code:** [238_svg_polyline.html](238_svg_polyline.html)

---

### 9. Elemen path

- **Tujuan Pembelajaran:** Menguasai sintaks elemen <path> untuk kurva dan ikon grafis rumit.
- **Konsep Utama:** Atribut d menerima bahasa instruksi pergerakan pena virtual (M untuk move, Q/C untuk kurva).
- **Penjelasan Source Code:** Menampilkan kurva lengkung halus merah muda berbentuk busur panah.
- **Cara Menjalankan:** Buka file `239_svg_path.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kurva lengkung mulus merah muda berbentuk kubah.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen path](output/239_svg_path.png)

- **Lokasi Source Code:** [239_svg_path.html](239_svg_path.html)

---

### 10. Teks dalam SVG

- **Tujuan Pembelajaran:** Merender teks yang dapat diseleksi dan diindeks mesin pencari di dalam SVG.
- **Konsep Utama:** Teks SVG diskalakan tanpa pecah bersama seluruh kanvas vektor.
- **Penjelasan Source Code:** Menampilkan teks biru terang 'Tipografi Vektor SVG' di dalam kotak gelap.
- **Cara Menjalankan:** Buka file `240_svg_text.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Teks biru muda kontras di atas kanvas latar belakang gelap.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Teks dalam SVG](output/240_svg_text.png)

- **Lokasi Source Code:** [240_svg_text.html](240_svg_text.html)

---

### 11. Atribut viewBox

- **Tujuan Pembelajaran:** Memahami konsep koordinat virtual viewBox untuk vektor responsif.
- **Konsep Utama:** ViewBox memetakan kanvas internal ke resolusi fisik container luar.
- **Penjelasan Source Code:** Menampilkan lingkaran biru responsif yang menyesuaikan ukuran wadah induk.
- **Cara Menjalankan:** Buka file `241_svg_viewbox.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Lingkaran biru simetris di dalam kotak fleksibel responsif.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Atribut viewBox](output/241_svg_viewbox.png)

- **Lokasi Source Code:** [241_svg_viewbox.html](241_svg_viewbox.html)

---

### 12. Aksesibilitas SVG

- **Tujuan Pembelajaran:** Menyusun grafik SVG yang dapat diinterpretasikan oleh screen reader.
- **Konsep Utama:** Kombinasi role='img', <title>, dan <desc> menjamin kepatuhan aksesibilitas.
- **Penjelasan Source Code:** Menampilkan ikon centang hijau sukses lengkap dengan metadata aksesibilitas.
- **Cara Menjalankan:** Buka file `242_svg_accessibility.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Ikon lingkaran hijau berisi tanda centang putih sukses.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Aksesibilitas SVG](output/242_svg_accessibility.png)

- **Lokasi Source Code:** [242_svg_accessibility.html](242_svg_accessibility.html)

---

### 13. Elemen canvas

- **Tujuan Pembelajaran:** Memahami dasar kanvas grafis raster berbasis skrip dengan elemen <canvas>.
- **Konsep Utama:** Canvas menggambar piksel demi piksel, sangat cocok untuk game dan visualisasi data performa tinggi.
- **Penjelasan Source Code:** Menampilkan kotak merah dan teks yang digambar dinamis melalui script JS Canvas.
- **Cara Menjalankan:** Buka file `243_canvas_element.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Kotak merah dengan teks hitam yang digambar di atas bidang kanvas 2D.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Elemen canvas](output/243_canvas_element.png)

- **Lokasi Source Code:** [243_canvas_element.html](243_canvas_element.html)

---

### 14. Fallback canvas

- **Tujuan Pembelajaran:** Menyiapkan penanganan cadangan apabila API kanvas tidak dapat dijalankan.
- **Konsep Utama:** Teks di antara tag pembuka dan penutup canvas berfungsi sebagai pesan fallback darurat.
- **Penjelasan Source Code:** Menampilkan kanvas dengan mekanisme fallback cadangan.
- **Cara Menjalankan:** Buka file `244_canvas_fallback.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Bidang kanvas dengan pesan cadangan bawaan.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Fallback canvas](output/244_canvas_fallback.png)

- **Lokasi Source Code:** [244_canvas_fallback.html](244_canvas_fallback.html)

---

### 15. Perbandingan SVG dan Canvas

- **Tujuan Pembelajaran:** Memilih dengan tepat antara SVG dan Canvas berdasarkan kebutuhan arsitektur aplikasi.
- **Konsep Utama:** SVG unggul dalam resolusi mandiri dan aksesibilitas, Canvas unggul dalam manipulasi ribuan objek bergerak cepat.
- **Penjelasan Source Code:** Menampilkan tabel komparasi teknis komprehensif antara SVG dan Canvas.
- **Cara Menjalankan:** Buka file `245_svg_vs_canvas.html` secara langsung di peramban web (Google Chrome, Mozilla Firefox, atau Microsoft Edge), atau jalankan ekstensi Live Server pada VS Code.
- **Hasil yang Diharapkan:** Tabel perbandingan teknis karakteristik SVG versus Canvas.
- **Screenshot Hasil Eksekusi:**

![Hasil eksekusi Perbandingan SVG dan Canvas](output/245_svg_vs_canvas.png)

- **Lokasi Source Code:** [245_svg_vs_canvas.html](245_svg_vs_canvas.html)

---

## Ringkasan Modul
Modul 14 menyajikan pondasi penting mengenai SVG, Canvas, dan Elemen Grafis. Pemahaman menyeluruh terhadap submodul di atas menjadi prasyarat penting sebelum melangkah ke modul berikutnya.
