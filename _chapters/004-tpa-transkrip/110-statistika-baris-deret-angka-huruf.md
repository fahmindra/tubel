---
slug: tpa-11-t
title: Statistika, Baris, Deret Angka & Huruf 
---
**Panduan Memahami Statistika Dasar: Rata-Rata, Median, Kuartil, dan Modus**

Selamat siang, Teman-teman! Apa kabarnya hari ini? Semoga dalam keadaan sehat, ya. Hari ini kita akan kembali belajar TPA, setelah tadi pagi kalian sudah belajar TBI. Keren juga ya, kalian bisa belajar beberapa jam berturut-turut!

Tadi saya lihat masih banyak yang belum sempat mengerjakan tugas *pre-test* karena waktunya mungkin terlalu mepet. Jadi, tadi saya berikan waktu 10 menit untuk mengerjakan *pre-test* terlebih dahulu. Ini sangat membantu saya sebagai panduan untuk melihat sejauh mana pemahaman kalian tentang statistika dan deret angka—apakah kita perlu mulai dari awal atau kalian sudah memahami dasar-dasarnya. Sekarang sepertinya sudah lumayan banyak yang mengerjakan.

Mari kita bahas materi hari ini, yaitu Statistika dan Deret Angka/Huruf.

---

### Dasar-Dasar Statistika: Rata-Rata (Mean)

Mari kita mulai dengan rumus dasar yang paling sering muncul di statistika, yaitu rata-rata. 

Rata-rata, yang biasanya disimbolkan dengan $\bar{x}$ (x bar), adalah jumlah seluruh data dibagi dengan banyak data.
*   **Jumlah data ($\Sigma x$):** Hasil penjumlahan semua nilai data. Misalnya, ada data 2, 3, dan 4. Jumlah datanya adalah $2 + 3 + 4 = 9$.
*   **Banyak data ($n$):** Ada berapa angka dalam data tersebut. Dari contoh 2, 3, dan 4, banyak datanya adalah 3.

Maka, rata-rata ($\bar{x}$) dari data 2, 3, 4 adalah:
$\bar{x} = \frac{\text{Jumlah Data}}{\text{Banyak Data}} = \frac{9}{3} = 3$

Rumus ini bisa dibolak-balik sesuai kebutuhan:
*   Jika ditanya banyak data ($n$): $n = \frac{\Sigma x}{\bar{x}}$
*   Jika ditanya jumlah data ($\Sigma x$): $\Sigma x = \bar{x} \times n$

#### Rata-Rata Gabungan (Dua Kelompok atau Lebih)

Terkadang, kalian akan menemui soal yang menggabungkan beberapa kelompok data tunggal, misalnya nilai siswa laki-laki dan perempuan. Untuk mencari rata-rata keseluruhan, kita harus menjumlahkan total nilai kedua kelompok, lalu membaginya dengan total anggota kedua kelompok.

*   Jumlah nilai perempuan = Rata-rata perempuan ($\bar{x}_A$) $\times$ Banyaknya perempuan ($n_A$)
*   Jumlah nilai laki-laki = Rata-rata laki-laki ($\bar{x}_B$) $\times$ Banyaknya laki-laki ($n_B$)

Rumus rata-rata keseluruhan (rata-rata gabungan):
$\bar{x}_{\text{gabungan}} = \frac{(\bar{x}_A \times n_A) + (\bar{x}_B \times n_B)}{n_A + n_B}$

Jika ada lebih dari dua kelompok (misalnya ada kelompok C), tinggal ditambahkan saja polanya.

#### Trik Perbandingan Jumlah Data

Dari rumus rata-rata gabungan di atas, jika kita jabarkan dan pindah ruaskan persamaannya, kita akan mendapatkan rumus cepat untuk membandingkan banyak anggota kelompok A ($n_A$) dan kelompok B ($n_B$):

$\frac{n_A}{n_B} = \frac{|\bar{x}_{\text{gabungan}} - \bar{x}_B|}{|\bar{x}_{\text{gabungan}} - \bar{x}_A|}$

**Konsep Penting:** Jumlah anggota dan rata-rata itu posisinya berkebalikan (menyilang). 
*   Jika kalian mencari perbandingan kelompok A ($n_A$), maka perhatikan selisih antara rata-rata gabungan dengan rata-rata kelompok B ($\bar{x}_B$).
*   Jika kalian mencari perbandingan kelompok B ($n_B$), maka perhatikan selisih antara rata-rata gabungan dengan rata-rata kelompok A ($\bar{x}_A$).
*   Selisihnya selalu **nilai yang besar dikurangi nilai yang kecil** agar hasilnya tidak negatif.

---

### Jangkauan, Median, dan Kuartil

Selain rata-rata, ada beberapa ukuran statistik lain yang sering ditanyakan:

*   **Jangkauan (Range):** Selisih antara nilai data terbesar ($x_{max}$) dikurangi nilai data terkecil ($x_{min}$).
*   **Median (Nilai Tengah):** Nilai yang membagi data yang telah diurutkan menjadi dua bagian yang sama banyak. 
    *   Jika jumlah data ($n$) ganjil, median adalah data tepat di tengah.
    *   Jika jumlah data ($n$) genap, median adalah rata-rata dari dua data di tengah: $\frac{X_{\frac{n}{2}} + X_{\frac{n}{2} + 1}}{2}$.
*   **Kuartil:** Nilai yang membagi data yang telah diurutkan menjadi empat bagian yang sama banyak. Ada Kuartil 1 (Q1), Kuartil 2 (Q2 = Median), dan Kuartil 3 (Q3).
    *   Q1 adalah nilai tengah dari separuh data di sebelah kiri median.
    *   Q3 adalah nilai tengah dari separuh data di sebelah kanan median.
*   **Simpangan Kuartil (Quartile Deviation / QD):** Setengah dari selisih antara Q3 dan Q1. Rumusnya: $QD = \frac{1}{2}(Q3 - Q1)$.

*(Catatan: Biasakan untuk selalu mengurutkan data dari yang terkecil ke terbesar sebelum mencari median dan kuartil).*

---

### Statistika Data Berkelompok

Data berkelompok adalah data yang disajikan dalam rentang kelas, misalnya nilai 50-54 ada 5 orang, nilai 55-60 ada 3 orang, dan seterusnya. 

#### 1. Rata-Rata Data Berkelompok
Rumusnya: $\bar{x} = \frac{\Sigma (f_i \times x_i)}{\Sigma f_i}$
*   $f_i$ = Frekuensi (banyaknya data) di kelas tersebut.
*   $x_i$ = Nilai tengah kelas. Didapat dari $\frac{\text{Batas Bawah} + \text{Batas Atas}}{2}$.
    Contoh: Kelas 50-54. Maka nilai tengahnya ($x_i$) adalah $\frac{50 + 54}{2} = 52$.

#### 2. Median Data Berkelompok
Rumusnya: $\text{Median} = TB + \left( \frac{\frac{1}{2}n - f_k}{f_m} \right) \times C$
*   **$TB$ (Tepi Bawah Kelas Median):** Batas bawah kelas median dikurangi 0,5. (Misal kelas median 50-54, maka $TB = 50 - 0,5 = 49,5$).
*   **$n$:** Total frekuensi seluruh data.
*   **$f_k$ (Frekuensi Kumulatif):** Jumlah frekuensi seluruh kelas *sebelum* kelas median.
*   **$f_m$:** Frekuensi pada kelas median itu sendiri.
*   **$C$ (Panjang Kelas):** Banyaknya nilai dalam satu kelas. (Misal kelas 50-54, isinya 50, 51, 52, 53, 54. Maka $C = 5$). Panjang kelas di setiap kelompok data pasti sama.

#### 3. Modus Data Berkelompok
Modus adalah nilai yang paling sering muncul (frekuensinya paling besar).
Rumusnya: $\text{Modus} = TB + \left( \frac{d_1}{d_1 + d_2} \right) \times C$
*   **$TB$ (Tepi Bawah Kelas Modus):** Batas bawah kelas modus dikurangi 0,5.
*   **$d_1$:** Selisih frekuensi kelas modus dengan frekuensi kelas *sebelumnya*.
*   **$d_2$:** Selisih frekuensi kelas modus dengan frekuensi kelas *setelahnya*.
*   **$C$:** Panjang kelas.

---

### Latihan Soal Statistika

Mari kita praktikkan rumus-rumus tadi ke dalam beberapa soal.

**Soal 1: Mencari Nilai Kelima**
*Seorang mahasiswa mendapat nilai 78, 86, 88, dan 91 untuk empat mata kuliah. Berapa nilai yang harus diperoleh untuk mata kuliah kelima agar nilai rata-ratanya 83?*

Penyelesaian:
Rata-rata ($\bar{x}$) = 83, banyak data ($n$) = 5.
$\bar{x} = \frac{\Sigma x}{n}$
$83 = \frac{78 + 86 + 88 + 91 + x}{5}$
$415 = 343 + x$
$x = 415 - 343 = 72$
Jadi, nilai kelima haruslah 72.

**Soal 2: Rata-Rata Gabungan**
*Tinggi rata-rata siswa wanita ($\bar{x}_A$) = 158. Tinggi rata-rata pria ($\bar{x}_B$) = 168. Rata-rata seluruh siswa = 165. Jumlah seluruh siswa = 30. Berapa jumlah siswa wanita ($n_A$)?*

Penyelesaian menggunakan rumus perbandingan:
$\frac{n_A}{n_B} = \frac{|\bar{x}_{\text{seluruh}} - \bar{x}_B|}{|\bar{x}_{\text{seluruh}} - \bar{x}_A|}$
$\frac{n_A}{n_B} = \frac{168 - 165}{165 - 158} = \frac{3}{7}$
Perbandingannya adalah 3 : 7. 
Jumlah total perbandingan = 3 + 7 = 10.
Karena total siswa ada 30, maka jumlah siswa wanita ($n_A$) adalah:
$n_A = \frac{3}{10} \times 30 = 9$ siswa.

**Soal 3: Aplikasi Rumus Kompleks**
*Jangkauan dan rata-rata nilai ujian enam siswa adalah 6. Jika mediannya 6 dan selisih kuartil 3 dan kuartil 1 adalah 4, maka jumlah dua nilai ujian tertinggi adalah...*

Penyelesaian:
Misalkan data diurutkan: $x_1, x_2, x_3, x_4, x_5, x_6$.
1.  **Jangkauan = 6:** $x_6 - x_1 = 6 \rightarrow x_1 = x_6 - 6$.
2.  **Median = 6:** Karena genap, median adalah rata-rata $x_3$ dan $x_4$. $\frac{x_3 + x_4}{2} = 6 \rightarrow x_3 + x_4 = 12$.
3.  **Kuartil:** Q1 adalah nilai tengah separuh kiri ($x_2$). Q3 adalah nilai tengah separuh kanan ($x_5$). Diketahui $Q3 - Q1 = 4$, maka $x_5 - x_2 = 4 \rightarrow x_2 = x_5 - 4$.
4.  **Rata-rata = 6:** Total nilai ($\Sigma x$) = $6 \times 6 = 36$.
    $x_1 + x_2 + x_3 + x_4 + x_5 + x_6 = 36$
    Substitusi persamaan yang kita punya:
    $(x_6 - 6) + (x_5 - 4) + 12 + x_5 + x_6 = 36$
    $2x_5 + 2x_6 + 2 = 36$
    $2(x_5 + x_6) = 34$
    $x_5 + x_6 = 17$
Jadi, jumlah dua nilai tertinggi adalah 17.

**Soal 4: Kesalahan Membaca Data**
*Rata-rata sekelompok bilangan adalah 40. Ada bilangan yang sebenarnya 60 terbaca 30. Setelah dihitung kembali, rata-ratanya 41. Banyak bilangan dalam kelompok itu adalah...*

Penyelesaian (Cara Cepat):
Jika banyak data ($n$) tetap dan hanya ada kesalahan catat/ubah nilai, gunakan rumus:
$n = \frac{\text{Selisih Nilai (Sebenarnya vs Tertulis)}}{\text{Selisih Rata-Rata}}$
$n = \frac{|60 - 30|}{|41 - 40|} = \frac{30}{1} = 30$
Banyak bilangan adalah 30.

**Soal 5: Mencari Rentang Rata-Rata**
*Dari lima bilangan, terkecil 40, terbesar 75, median 50. Range rata-ratanya adalah...*

Penyelesaian:
Urutkan data: $x_1, x_2, x_3, x_4, x_5$.
Diketahui: $x_1 = 40, x_3 = 50, x_5 = 75$.
Agar tidak mengubah urutan, nilai minimal untuk $x_2$ adalah sama dengan angka sebelumnya (40), dan $x_4$ sama dengan sebelumnya (50).
Nilai maksimal untuk $x_2$ adalah sama dengan angka setelahnya (50), dan $x_4$ sama dengan setelahnya (75).
*   **Total Maksimal:** $40 + 50 + 50 + 75 + 75 = 290$. Rata-rata maksimal = $\frac{290}{5} = 58$.
*   **Total Minimal:** $40 + 40 + 50 + 50 + 75 = 255$. Rata-rata minimal = $\frac{255}{5} = 51$.
Jadi, range rata-ratanya adalah 51 sampai 58.

---

### Deret Angka dan Huruf

Soal deret meminta kita menemukan pola dari angka atau huruf untuk melengkapi barisan. Berikut beberapa tipe pola yang sering muncul:

1.  **Satu Larik:** Pola langsung terlihat antar suku yang bersebelahan. (Misal: +2, +2, +2, dst).
2.  **Dua Larik (Lompat Satu):** Pola terbentuk dari suku 1 ke 3, lalu ke 5, dst. Ciri-cirinya angkanya naik-turun.
3.  **Barisan Bertingkat:** Polanya tidak terlihat pada tingkat pertama, melainkan pada tingkat selisih berikutnya. (Misal tingkat pertama selisihnya +4, +6, +8, baru di tingkat kedua terlihat polanya yaitu +2).
4.  **Fibonacci:** Nilai suatu suku adalah hasil penjumlahan (atau operasi lain) dari suku-suku sebelumnya. Contoh: 3, 4, 7, 11, 18 (di mana 3+4=7, 4+7=11).

**Tips Mengerjakan Deret:**
*   Untuk deret huruf, jika kesulitan melihat polanya, ubahlah menjadi deret angka berdasarkan urutan abjad (A=1, B=2, E=5, J=10, O=15, T=20, dst).
*   Jika ada dua angka kosong yang harus diisi, pastikan pola yang kalian temukan berlaku untuk *keduanya*, bukan hanya salah satu.
*   Jika pola operasi matematika biasa (+, -, $\times$, $\div$) tidak membuahkan hasil, cobalah mencari hubungan khusus, misalnya hasil kuadrat. (Contoh: 18 menjadi 65 didapat dari $1^2 + 8^2 = 1 + 64 = 65$).
*   Soal deret seharusnya bisa dikerjakan dengan cepat. Jika kalian *stuck* lebih dari 1 menit dan tidak menemukan polanya, lewati dulu. Jangan sampai waktu kalian habis di satu soal.

---

Demikianlah pelajaran kita hari ini mengenai Statistika dan Deret Angka/Huruf. Kunci utama untuk menguasai materi ini, terutama deret, adalah dengan memperbanyak latihan soal agar kalian semakin peka melihat pola. Jaga terus semangat belajarnya, semoga hasilnya sesuai dengan yang kita harapkan. Wassalamualaikum warahmatullahi wabarakatuh. Selamat beristirahat!