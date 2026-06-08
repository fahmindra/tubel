---
slug: tpa-12-t
title: Statistika, Baris, Deret Angka & Huruf 
---
**Panduan Mengerjakan Soal Statistika dan Deret Angka/Huruf TPA**

Selamat siang, Teman-teman semuanya! Apa kabarnya hari ini? Semoga dalam keadaan sehat, ya. Hari ini kita akan membahas dua submateri, yaitu tentang statistika dan deret angka dan huruf. Sebelumnya, apakah Teman-teman sudah mengerjakan PR-nya? Sudah dicoba? Oke, untuk PR-nya saya lihat sih sebagian besar sudah benar, terutama ketika yang ditanya rata-rata. Paling hanya ada satu atau dua orang yang keliru. Berarti Teman-teman sebenarnya sudah mengerti konsep dasarnya. 

Tapi mungkin kita coba ulas sedikit kira-kira ada rumus apa saja yang sering dipakai untuk menjawab soal-soal terkait statistika.

### Statistika Data Tunggal: Rata-Rata (Mean)

Pertama, kita akan membahas tentang statistika data tunggal. Rumus dasarnya adalah:
**Rata-rata ($\bar{x}$) = Jumlah Data / Banyak Data**

*   **Jumlah data ($\Sigma x$):** Hasil penjumlahan semua nilai data. Misalnya ada data 2, 3, dan 4, maka jumlah datanya adalah $2 + 3 + 4 = 9$.
*   **Banyak data ($n$):** Ada berapa angka dalam data tersebut. Dari contoh di atas, banyak datanya adalah 3.

Maka, rata-rata ($\bar{x}$) dari data 2, 3, 4 adalah:
$\bar{x} = \frac{9}{3} = 3$

Rumus ini bisa dimodifikasi sesuai dengan apa yang ditanyakan:
*   Jika ditanya jumlah data ($\Sigma x$): $\Sigma x = \bar{x} \times n$
*   Jika ditanya banyak data ($n$): $n = \frac{\Sigma x}{\bar{x}}$

Yang penting Teman-teman sudah memahami rumus dasarnya.

#### Rata-Rata Gabungan

Terkadang, kalian akan menemui soal data tunggal yang dibagi atas beberapa kelompok, misalnya nilai siswa perempuan dan laki-laki. Jika kita diminta mencari rata-rata keseluruhan, kita harus menjumlahkan total nilai kedua kelompok, lalu membaginya dengan total anggota kedua kelompok.

*   Jumlah nilai perempuan = Rata-rata perempuan ($\bar{x}_A$) $\times$ Banyaknya perempuan ($n_A$)
*   Jumlah nilai laki-laki = Rata-rata laki-laki ($\bar{x}_B$) $\times$ Banyaknya laki-laki ($n_B$)

Maka, rumus rata-rata keseluruhan (rata-rata gabungan) adalah:
$\bar{x}_{\text{gabungan}} = \frac{(\bar{x}_A \times n_A) + (\bar{x}_B \times n_B)}{n_A + n_B}$

Jika ada lebih dari dua kelompok, tinggal ditambahkan saja polanya.

#### Trik Perbandingan Jumlah Data

Dari rumus rata-rata gabungan tersebut, kita bisa menyederhanakannya menjadi rumus cepat untuk mencari perbandingan jumlah anggota kelompok A ($n_A$) dan kelompok B ($n_B$):

$\frac{n_A}{n_B} = \frac{|\bar{x}_{\text{gabungan}} - \bar{x}_B|}{|\bar{x}_{\text{gabungan}} - \bar{x}_A|}$

**Konsep Penting:** Posisinya berbanding terbalik. 
*   Jika mencari jumlah kelompok A ($n_A$), perhatikan selisih rata-rata gabungan dengan rata-rata kelompok B ($\bar{x}_B$).
*   Jika mencari jumlah kelompok B ($n_B$), perhatikan selisih rata-rata gabungan dengan rata-rata kelompok A ($\bar{x}_A$).
*   Selisihnya selalu **nilai yang besar dikurangi nilai yang kecil**.

### Jangkauan, Simpangan Kuartil, dan Median

Selain rata-rata, ada beberapa ukuran statistik lain:
*   **Jangkauan (Range):** Nilai terbesar dikurangi nilai terkecil ($x_{max} - x_{min}$).
*   **Simpangan Kuartil (QD):** Setengah dari selisih antara Kuartil 3 dan Kuartil 1. Rumusnya: $QD = \frac{1}{2}(Q3 - Q1)$.
*   **Median (Nilai Tengah):** Nilai yang membagi data yang telah diurutkan menjadi dua bagian yang sama banyak.
    *   Jika jumlah data ganjil, median adalah data tepat di tengah: $x_{\frac{n+1}{2}}$.
    *   Jika jumlah data genap, median adalah rata-rata dari dua data di tengah: $\frac{X_{\frac{n}{2}} + X_{\frac{n}{2} + 1}}{2}$.

### Statistika Data Berkelompok

Data berkelompok adalah data yang disajikan dalam rentang kelas (misalnya berat badan 50-54, 55-59, dst). 
*   **Panjang kelas ($C$):** Banyaknya nilai dalam satu kelas. (Misal: 50, 51, 52, 53, 54 berarti panjang kelasnya 5).
*   **Frekuensi ($f_i$):** Banyaknya data di kelas tersebut.

#### 1. Rata-Rata Data Berkelompok
Rumusnya: $\bar{x} = \frac{\Sigma (f_i \times x_i)}{\Sigma f_i}$
*   $x_i$ adalah **nilai tengah** kelas, didapat dari $\frac{\text{Batas Bawah} + \text{Batas Atas}}{2}$. Contoh: untuk kelas 50-54, nilai tengahnya adalah $\frac{50 + 54}{2} = 52$.

Jadi, untuk mencari rata-ratanya, cari dulu nilai tengah ($x_i$) masing-masing kelas, kalikan dengan frekuensinya ($f_i \times x_i$), jumlahkan semua hasilnya, lalu bagi dengan total frekuensi ($\Sigma f_i$).

#### 2. Median Data Berkelompok
Rumusnya: $\text{Median} = TB + \left( \frac{\frac{1}{2}n - f_k}{f_m} \right) \times C$
*   **$TB$ (Tepi Bawah):** Batas bawah kelas median dikurangi 0,5. (Misal batas bawah 50, maka $TB = 49,5$).
*   **$n$:** Total frekuensi.
*   **$f_k$:** Jumlah frekuensi seluruh kelas *sebelum* kelas median.
*   **$f_m$:** Frekuensi pada kelas median.
*   **$C$:** Panjang kelas.

#### 3. Modus Data Berkelompok
Modus adalah kelas dengan frekuensi terbesar.
Rumusnya: $\text{Modus} = TB + \left( \frac{d_1}{d_1 + d_2} \right) \times C$
*   **$TB$:** Tepi bawah kelas modus.
*   **$d_1$:** Selisih frekuensi kelas modus dengan kelas *sebelumnya*.
*   **$d_2$:** Selisih frekuensi kelas modus dengan kelas *setelahnya*.

---

### Pembahasan Latihan Soal Statistika

**Soal 1: Mencari Nilai Kelima**
*Seorang mahasiswa mendapat nilai 78, 86, 88, dan 91 untuk empat mata kuliah. Berapa nilai yang harus diperoleh untuk mata kuliah yang kelima agar diperoleh nilai rata-rata 83?*

Penyelesaian:
Rata-rata ($\bar{x}$) = 83, banyak data ($n$) = 5.
$83 = \frac{78 + 86 + 88 + 91 + x}{5}$
$415 = 343 + x$
$x = 415 - 343 = 72$
Jadi, nilai kelima haruslah 72.

**Soal 2: Rata-Rata Gabungan**
*Tinggi rata-rata wanita = 158. Tinggi rata-rata pria = 168. Rata-rata seluruh siswa = 165. Jumlah seluruh siswa = 30. Berapa jumlah siswa wanita?*

Penyelesaian dengan perbandingan:
$\frac{n_{\text{wanita}}}{n_{\text{pria}}} = \frac{|\bar{x}_{\text{seluruh}} - \bar{x}_{\text{pria}}|}{|\bar{x}_{\text{seluruh}} - \bar{x}_{\text{wanita}}|}$
$\frac{n_{\text{wanita}}}{n_{\text{pria}}} = \frac{168 - 165}{165 - 158} = \frac{3}{7}$
Perbandingan Wanita : Pria = 3 : 7. 
Jumlah total perbandingan = 3 + 7 = 10.
Maka, jumlah siswa wanita = $\frac{3}{10} \times 30 = 9$ siswa.

**Soal 3: Jangkauan, Median, dan Kuartil**
*Jangkauan dan rata-rata nilai ujian enam siswa adalah 6. Jika median data tersebut adalah 6 dan selisih kuartil 3 dan kuartil 1 adalah 4, maka jumlah dua nilai ujian tertinggi adalah...*

Penyelesaian:
Urutkan data: $x_1, x_2, x_3, x_4, x_5, x_6$.
1.  **Jangkauan = 6:** $x_6 - x_1 = 6 \rightarrow x_1 = x_6 - 6$.
2.  **Median = 6:** Karena genap (6 data), median ada di antara $x_3$ dan $x_4$. $\frac{x_3 + x_4}{2} = 6 \rightarrow x_3 + x_4 = 12$.
3.  **Kuartil:** $Q_1$ adalah nilai tengah separuh kiri ($x_2$). $Q_3$ adalah nilai tengah separuh kanan ($x_5$). $Q_3 - Q_1 = 4 \rightarrow x_5 - x_2 = 4 \rightarrow x_2 = x_5 - 4$.
4.  **Rata-rata = 6:** $\Sigma x = 6 \times 6 = 36$.
    $x_1 + x_2 + x_3 + x_4 + x_5 + x_6 = 36$
    $(x_6 - 6) + (x_5 - 4) + 12 + x_5 + x_6 = 36$
    $2x_5 + 2x_6 + 2 = 36$
    $2(x_5 + x_6) = 34 \rightarrow x_5 + x_6 = 17$.
Jadi, jumlah dua nilai tertinggi adalah 17.

**Soal 4: Kesalahan Membaca Data**
*Rata-rata sekelompok bilangan adalah 40. Ada bilangan yang sebenarnya 60 tetapi terbaca 30. Setelah dihitung kembali ternyata rata-rata yang benar adalah 41. Banyak bilangan dalam kelompok tersebut adalah...*

Penyelesaian (Cara Cepat):
Karena banyak data ($n$) tetap, gunakan rumus selisih:
$n = \frac{\text{Selisih Nilai Sebenarnya dan Tertulis}}{\text{Selisih Rata-rata}}$
$n = \frac{|60 - 30|}{|41 - 40|} = \frac{30}{1} = 30$.

**Soal 5: Mencari Rentang Rata-Rata**
*Dari 5 buah bilangan, terkecil 40, terbesar 75, median 50. Range rata-ratanya adalah...*

Penyelesaian:
Urutkan data: $x_1, x_2, x_3, x_4, x_5$.
Diketahui: $x_1 = 40, x_3 = 50, x_5 = 75$.
Agar totalnya minimal: $x_2$ sekecil mungkin (40), $x_4$ sekecil mungkin (50). Total = 255. Rata-rata minimal = 255/5 = 51.
Agar totalnya maksimal: $x_2$ sebesar mungkin (50), $x_4$ sebesar mungkin (75). Total = 290. Rata-rata maksimal = 290/5 = 58.
Jadi range rata-ratanya adalah 51 sampai 58.

---

### Tips Mengerjakan Deret Angka dan Huruf

Soal deret meminta kita mencari pola untuk melengkapi suku berikutnya. Berikut panduannya:
1.  **Satu Larik:** Cek hubungan antar suku yang bersebelahan (misal +2, +2).
2.  **Dua Larik (Lompat Satu):** Jika angkanya naik-turun, curigai pola ini. Hubungkan suku ke-1 dengan ke-3, ke-2 dengan ke-4, dst.
3.  **Tiga Larik:** Jika ada angka yang berulang secara konstan setiap 3 suku, coba lompat dua angka.
4.  **Barisan Bertingkat:** Polanya tidak langsung terlihat, tapi baru muncul di tingkat selisih kedua atau ketiga.
5.  **Fibonacci:** Suatu suku adalah hasil operasi (penjumlahan, pengurangan, perkalian) dari suku-suku sebelumnya.
6.  **Pola Unik:** Jika semua pola di atas tidak berhasil, coba cari hubungan khusus antara suku yang berurutan. Misalnya, suku berikutnya adalah hasil penjumlahan kuadrat digit suku sebelumnya (Contoh: $18 \rightarrow 1^2 + 8^2 = 65$).

**Tips Tambahan:**
*   Untuk deret huruf, jika kesulitan melihat pola, ubahlah menjadi deret angka berdasarkan urutan abjad (A=1, B=2, E=5, dst).
*   Soal deret seharusnya bisa dikerjakan dengan cepat. Jika *stuck* lebih dari 30 detik, lewati dulu dan kerjakan soal lain.

---

### Pembahasan Post-Test (Soal Terpilih)

**Soal 1 Post-Test: Rata-Rata Bilangan Maksimal**
*Jika rata-rata 20 bilangan bulat positif berbeda adalah 20, maka bilangan terbesar yang mungkin adalah...*
*(Catatan: Ralat dari soal asli yang tertulis "non-negatif". Jika non-negatif, angka 0 masuk. Jika positif, dimulai dari 1).*

Penyelesaian (Versi Positif):
Rata-rata 20, $n$ = 20. Maka total $\Sigma x = 400$.
Agar $x_{20}$ maksimal, $x_1$ sampai $x_{19}$ harus seminimal mungkin dan berbeda: $1, 2, 3, ..., 19$.
Gunakan rumus jumlah deret aritmatika untuk 1-19: $\frac{n}{2}(a + U_n) = \frac{19}{2}(1 + 19) = 190$.
Maka, $190 + x_{20} = 400 \rightarrow x_{20} = 210$.

**Soal 2 Post-Test: Mencari Angka yang Hilang**
*11 siswa mengikuti tes, median 91. Diketahui nilai: 100(3), 96(1), 90(3), 86(2). Nilai dua siswa yang belum diketahui adalah...*

Penyelesaian:
Data diurutkan: 86, 86, 90, 90, 90, ..., 96, 100, 100, 100.
Median dari 11 data ada di data ke-6. Karena mediannya 91, maka salah satu data yang hilang adalah 91. Posisinya ada di antara 90 dan 96.
Agar seimbang (5 data di kiri, 5 data di kanan), angka satu lagi harus diletakkan di sebelah kanan 91. Dari pilihan, angka yang logis adalah 93 (jangan pilih 86 karena akan membuat data kiri lebih banyak). Jadi jawabannya 91 dan 93.

Demikian pembahasan materi kita hari ini. Kunci menguasai deret dan statistika adalah dengan memperbanyak latihan soal agar insting mencari polanya semakin tajam. Terima kasih sudah bergabung dan semangat terus belajarnya! Wassalamualaikum warahmatullahi wabarakatuh. Selamat beristirahat!