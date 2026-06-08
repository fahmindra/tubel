---
slug: refresh-2
title: Jarak-Kecepatan-Waktu & Baris-Deret
---
**Panduan Menguasai Soal TPA: Jarak, Kecepatan, Waktu (JKW) dan Deret**

Halo teman-teman! Malam ini kita akan me-*refresh* kembali materi Jarak, Kecepatan, dan Waktu (JKW) serta Deret. Sambil mendengarkan, kita juga akan membahas beberapa *post-test* yang sudah kalian kerjakan. 

**Mengingat Kembali Rumus JKW**

Saya yakin teman-teman sudah cukup familier dengan materi JKW. Jarak disimbolkan dengan J atau S, kecepatan dengan V, dan waktu dengan T. Untuk memudahkan mengingat, kalian bisa menggunakan segitiga JKW:
*   **S (Jarak)** berada di atas.
*   **V (Kecepatan)** dan **T (Waktu)** berada di bawah.

Dari segitiga ini, kita bisa menurunkan rumus-rumus berikut:
*   Mencari Jarak ($S$): $S = V \times T$
*   Mencari Kecepatan ($V$): $V = \frac{S}{T}$
*   Mencari Waktu ($T$): $T = \frac{S}{V}$

Atau, ingat saja satuan kecepatan: km/jam. Kilometer adalah satuan jarak ($S$), dan jam adalah satuan waktu ($T$). Maka, $V = \frac{S}{T}$. Rumus ini sangat mendasar dan pasti akan sering digunakan. 

Secara lebih lengkap, kecepatan rata-rata dirumuskan sebagai:
**$V_{\text{rata-rata}} = \frac{S_{\text{total}}}{T_{\text{total}}}$**

Jika ada lebih dari satu perjalanan (misal: Jakarta-Bandung, Bandung-Jogja, Jogja-Bali), maka total jarak ($S_1 + S_2 + S_3$) dibagi dengan total waktu tempuh ($T_1 + T_2 + T_3$).

*Catatan:* Dalam soal TPA, jika disebutkan "kecepatan 50 km/jam", itu biasanya merujuk pada kecepatan rata-rata, kecuali jika disebutkan secara spesifik sebagai kecepatan konstan. 

---

**Kasus 1: Kecepatan Rata-Rata Pulang-Pergi**

Sering kali kita menjumpai soal tentang perjalanan dari titik A ke titik B, lalu kembali lagi dari titik B ke titik A. Jika tidak ada keterangan lain, kita asumsikan jarak berangkat dan pulang adalah sama ($S_1 = S_2$). 

**Hati-hati!** Jika ditanya rata-rata kecepatan perjalanan pulang-pergi, **jangan** pernah menjumlahkan kedua kecepatan lalu membaginya dua. (Misal: kecepatan berangkat 60, pulang 90. Rata-rata = (60+90)/2 = 75. Ini **SALAH BESAR!**)

Kita harus kembali ke konsep awal: $V = \frac{S_1 + S_2}{T_1 + T_2}$
Karena $S_1 = S_2$, mari kita sebut saja $S$. Kita tahu bahwa $T = \frac{S}{V}$, maka:
$V = \frac{S + S}{\frac{S}{V_1} + \frac{S}{V_2}}$
$V = \frac{2S}{\frac{S \cdot V_2 + S \cdot V_1}{V_1 \cdot V_2}}$
$V = \frac{2S \cdot (V_1 \cdot V_2)}{S(V_1 + V_2)}$
Coret $S$, maka didapat rumus cepat:
**$V_{\text{rata-rata}} = \frac{2 \cdot V_1 \cdot V_2}{V_1 + V_2}$**

*Contoh Soal:*
Jojo pergi dari Pontianak ke Singkawang dengan kecepatan 60 km/jam, lalu kembali dengan kecepatan 50 km/jam. Kecepatan rata-rata seluruh perjalanannya adalah?
*Jawab:* 
$V = \frac{2 \cdot 60 \cdot 50}{60 + 50}$
$V = \frac{6000}{110} \approx 54,54$ km/jam.
*(Sekali lagi, ingat ya, jangan gunakan 60+50 dibagi 2 = 55. Ini adalah jebakan).*

---

**Kasus 2: Berpapasan**

Berpapasan terjadi ketika dua objek bergerak saling menuju dari titik yang berbeda (A menuju B, B menuju A). Suatu saat mereka akan bertemu di satu titik.
Dari ilustrasi ini, jarak yang ditempuh A ($S_A$) ditambah jarak yang ditempuh B ($S_B$) sama dengan total jarak yang memisahkan mereka berdua di awal ($S_{\text{total}}$).
Rumus dasarnya: **$S_A + S_B = S_{\text{total}}$**

*Contoh Ilustrasi:*
Jarak A dan B 120 km. A berangkat dengan kecepatan 40 km/jam, B berangkat dari arah berlawanan dengan kecepatan 20 km/jam. Mereka berangkat bersamaan pukul 08.00. Kapan mereka berpapasan?

Dalam 1 jam (pukul 09.00), A menempuh 40 km dan B menempuh 20 km. Total jarak yang ditempuh bersama adalah 60 km. Karena jarak awal 120 km, mereka butuh waktu 2 jam ($120 \div 60$). Pukul 08.00 ditambah 2 jam, mereka berpapasan pukul 10.00.

Dari logika ini, kita dapatkan rumus waktu berpapasan ($t_{\text{papasan}}$):
**$t_{\text{papasan}} = \frac{S_{\text{total}}}{V_1 + V_2}$**

*Bagaimana jika waktu berangkatnya berbeda?*
Misal A berangkat pukul 08.00 dan B pukul 09.30 (selisih waktu / $\Delta T$ = 1,5 jam).
Kita harus menghitung jarak yang sudah ditempuh A sebelum B berangkat ($S_0$).
$S_0 = V_A \times \Delta T = 40 \times 1,5 = 60$ km.
Sisa jarak yang akan ditempuh bersama: $120 - 60 = 60$ km.
Waktu berpapasan dihitung dari titik ketika **keduanya sudah mulai bergerak** (pukul 09.30).
$t_{\text{papasan}} = \frac{60}{40 + 20} = 1$ jam.
Maka mereka berpapasan pukul 09.30 + 1 jam = 10.30.

Rumus lengkapnya:
**$t_{\text{papasan}} = \frac{S_{\text{total}} - S_0}{V_1 + V_2}$**
*(Trik: Jadikan orang kedua yang berangkat sebagai POV (Point of View) untuk menghitung waktu papasan).*

---

**Kasus 3: Susul Menyusul**

Kasus ini terjadi jika ada objek yang berangkat lebih awal (A), lalu disusul oleh objek lain (B) dari titik awal yang sama. Syaratnya: kecepatan B harus lebih besar dari kecepatan A ($V_B > V_A$).
Rumus dasarnya adalah jarak tempuh keduanya sama: **$S_A = S_B$**.

Secara logika, untuk menyusul, si penyusul harus "menghabiskan" selisih jarak yang telah diciptakan oleh orang pertama yang berangkat duluan.
Selisih jarak = Jarak yang ditempuh A sebelum B berangkat ($V_1 \times \Delta T$).
Kecepatan menyusul = Selisih kecepatan keduanya ($V_2 - V_1$).

Rumus waktu menyusul ($t_{\text{susul}}$):
**$t_{\text{susul}} = \frac{V_1 \times \Delta T}{V_2 - V_1}$**

*Contoh Soal:*
Malik berlari 8 km/jam, Kamil berjalan 1 km/jam. Kamil selesai ujian pukul 12.00 dan pulang. Malik selesai pukul 12.35 dan mengejar Kamil. Pukul berapa Malik menyusul Kamil?

*Jawab:*
$\Delta T$ = 35 menit. $V_1$ (Kamil) = 1 km/jam, $V_2$ (Malik) = 8 km/jam.
$t_{\text{susul}} = \frac{1 \times 35}{8 - 1} = \frac{35}{7} = 5$ menit.
Malik mulai menyusul dari pukul 12.35. Maka, ia menyusul Kamil pada pukul 12.35 + 5 menit = 12.40.

*(Catatan: Dalam perbandingan rumus ini, satuan waktu (menit/jam) tidak perlu diubah ke jam karena satuan kecepatannya akan saling menghilangkan).*

---

**Kasus 4: Soal Modifikasi / Pemahaman Konsep**

Seringkali soal tidak bisa diselesaikan langsung dengan rumus cepat, sehingga kita harus kembali ke konsep dasar.

*Contoh Soal:*
Sebuah maskapai penerbangan melakukan penerbangan domestik sejauh 600 km. Karena cuaca buruk, kecepatan rata-ratanya berkurang 200 km/jam dan waktu tempuh bertambah 30 menit. Berapa durasi penerbangan dalam kondisi normal?

*Jawab:*
Kita tahu jarak ($S$) selalu 600 km. 
Kondisi normal: $V_1, T_1$. 
Kondisi cuaca buruk: $V_2 = V_1 - 200$, dan $T_2 = T_1 + 0,5$ jam.

*Logika Cepat:*
Cuaca buruk membuat waktu bertambah 0,5 jam karena kecepatan berkurang 200 km/jam. Ini mengisyaratkan bahwa setiap 0,5 jam (dalam kecepatan normal yang hilang) setara dengan jarak 200 km.
Untuk menempuh total 600 km dengan asumsi ini, dibutuhkan $3 \times 0,5 \text{ jam} = 1,5$ jam (Ini adalah waktu tempuh saat cuaca buruk).
Maka, waktu tempuh normal adalah $1,5 \text{ jam} - 0,5 \text{ jam} = 1$ jam.

*Penyelesaian Aljabar:*
$S_1 = S_2 = 600$
$V_1 \cdot T_1 = V_2 \cdot T_2$
Karena $V = \frac{S}{T}$, maka $\frac{600}{T_1} = \frac{600}{T_2} + 200$
Substitusikan $T_2 = T_1 + 0,5$. Persamaan ini akan membentuk persamaan kuadrat:
$t_1^2 + 0,5 t_1 - 1,5 = 0$
Kalikan 2 agar tidak ada pecahan: $2t_1^2 + t_1 - 3 = 0$
Faktorkan: $(2t_1 + 3)(t_1 - 1) = 0$
Diperoleh $t_1 = -\frac{3}{2}$ (tidak mungkin negatif) atau $t_1 = 1$.
Jadi, waktu normal adalah 1 jam. 
*(Jika kesulitan menemukan logika cepat, berlatihlah membentuk persamaan aljabar).*

---

**Konsep Deret Angka dan Huruf**

Untuk menguasai materi deret, kunci utamanya adalah banyak berlatih. Jika dalam 10-30 detik polanya belum terlihat, segera *skip* agar waktu tidak terbuang. Berikut beberapa tipe pola deret:
1.  **Fibonacci:** Nilai suatu suku adalah hasil operasi (biasanya penjumlahan atau pengurangan) dari dua suku sebelumnya. (Contoh: 3, 4, 7, 11... dimana 3+4=7, 4+7=11). Pola ini bisa juga digabung dengan pola lompat.
2.  **Larik (Pola Tunggal/Ganda):** 
    *   1 Larik: Pola konsisten di setiap suku berurutan (misal selalu +2). Biasanya angkanya selalu naik atau selalu turun.
    *   2 Larik (Lompat 1): Ada pola tersendiri untuk suku ganjil dan suku genap. Ciri-cirinya angkanya sering naik-turun.
    *   3 Larik (Lompat 2): Jika ada angka yang berulang secara konstan setiap 3 suku, curigai ini adalah pola 3 larik.
3.  **Barisan Bertingkat:** Polanya tidak terlihat pada selisih tingkat pertama, melainkan baru terlihat konsisten di tingkat kedua atau ketiga.
4.  **Kombinasi/Pola Tidak Beraturan:** Terkadang suatu suku adalah hasil dari pengkuadratan angka pada suku sebelumnya (Misal: 18 $\rightarrow$ $1^2 + 8^2 = 65$).
5.  **Deret Huruf:** Jika kebingungan, segera konversi huruf menjadi angka (A=1, E=5, J=10, O=15, T=20) agar otak lebih mudah mencerna polanya.

*Contoh Soal Deret Huruf (Post-test 10):*
B, Y, D, T, H, P, P... (Dikonversi: 2, 25, 4, 20, 8, 16, 16...)
Angka terlihat naik turun, kita curigai pola 2 larik.
*   Suku ganjil: 2 $\rightarrow$ 4 $\rightarrow$ 8 $\rightarrow$ 16. (Polanya bisa $\times 2$ atau bertingkat $+2, +4, +8$).
*   Suku genap: 25 $\rightarrow$ 20 $\rightarrow$ 16. (Polanya $-5, -4$, maka selanjutnya $-3 \rightarrow 13$).
Suku berikutnya adalah 14 (dari $8+6$) dan 13. Dikonversi ke huruf menjadi N dan M.

---

**Pembahasan Post-Test (Soal Tambahan JKW)**

*Dua buah pesawat terbang meninggalkan bandara pukul 17.00. Pesawat pertama ke timur dengan kecepatan 150 km/jam, pesawat kedua ke utara dengan kecepatan 200 km/jam. Berapa jarak antara kedua pesawat pada pukul 19.00 jika keduanya terbang lurus?*

*Jawab:*
Waktu tempuh ($\Delta T$) dari 17.00 ke 19.00 adalah 2 jam.
Jarak pesawat 1 (Timur) = $150 \times 2 = 300$ km.
Jarak pesawat 2 (Utara) = $200 \times 2 = 400$ km.
Karena arah Timur dan Utara tegak lurus, kita gunakan rumus Pythagoras (atau ingat *triple pythagoras* 3-4-5).
Sisi alas 300, sisi tegak 400, maka sisi miring (jarak kedua pesawat) adalah **500 km**.

*Sebuah kolam dapat diisi penuh oleh pipa A dalam 4 jam dan pipa B dalam 6 jam. Kebocoran di dasar kolam menghabiskan air dalam 12 jam. Jika kedua pipa dibuka dan kebocoran belum diperbaiki, berapa lama kolam terisi penuh?*

*Jawab:*
Gunakan konsep kecepatan kerja: $\frac{1}{T_{\text{total}}} = \frac{1}{T_A} + \frac{1}{T_B} - \frac{1}{T_{\text{bocor}}}$
$\frac{1}{T} = \frac{1}{4} + \frac{1}{6} - \frac{1}{12}$
Samakan penyebut menjadi 24 (atau 12 juga bisa):
$\frac{1}{T} = \frac{6 + 4 - 2}{24} = \frac{8}{24} = \frac{1}{3}$
Maka $T = 3$ jam.

*Berlin mengendarai motor 40 km setiap hari dengan waktu 55 menit. Suatu hari ia telat berangkat 7 menit. Berapa kecepatannya agar tiba di waktu yang sama seperti biasanya?*

*Jawab:*
Jarak ($S$) tetap 40 km.
Waktu normal 55 menit. Karena telat 7 menit, sisa waktunya ($T$) adalah $55 - 7 = 48$ menit.
Ingat! Konversi menit ke jam: $T = \frac{48}{60}$ jam.
$V = \frac{S}{T} = \frac{40}{\frac{48}{60}} = \frac{40 \times 60}{48} = \frac{2400}{48} = 50$ km/jam.

Terima kasih atas partisipasi aktif teman-teman malam ini. Pasti lelah bekerja seharian lalu lanjut belajar. Semoga lelahnya menjadi *lillah* dan membuahkan hasil yang kita harapkan. Selamat beristirahat! Wassalamualaikum warahmatullahi wabarakatuh.