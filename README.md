# SOAL NOMOR 2
---
# PERSOALAN :
<blockquote>Tuliskan program dalam bahasa pemrograman C ataupun C++ untuk merepresentasikan
AND, OR, dan NOT Logic pada penerapannya di dalam bidang jaringan saraf tiruan!</blockquote>


# PENJELASAN SINGKAT :
<blockquote>Software compiler yang digunakan untuk membuat program ini adalah DEV C++ dan
Seluruh script baik script AND, OR, dan NOT Logic sudah di test run dan berhasil dijalankan
Tanpa masalah baik dari program maupun hasil keluaran/output</blockquote>

# NILAI BOBOT TIAP GATE :
Berikut nilai bobot atau saya sebut dengan 'w' pada masing-masing Logic Gate :

- AND Logic  
AND Logic memiliki 2 nilai bobot yang nilainya telah ditetapkan yaitu "1"
<blockquote>w1 = 1</blockquote>
<blockquote>w2 = 1</blockquote>

- OR Logic
OR Logic memiliki 2 nilai bobot yang nilainya telah ditetapkan yaitu "2"
<blockquote>w1 = 2</blockquote>
<blockquote>w2 = 2</blockquote>

- NOT Logic
NOT Logic hanya memiliki 1 nilai bobot yang telah ditetapkan yaitu "-1"
<blockquote>w = -1</blockquote>

# PENJELASAN RUMUS OUTPUT DAN KONDISI TIAP LOGIC GATE :
Untuk keseluruhan script baik itu AND, OR, dan NOT hampir mirip. Yang membedakan ketiganya adalah
Nilai bobot yang sudah di sesuaikan pada masing-masing jenis Logic Gatenya. Dan nantinya inputan dari user
Dan nilai bobot akan di jumlahkan sesuai dengan rumus OUTPUT yang telah ditetapkan.

Rumus Output untuk AND dan OR Logic :
<blockquote>O=x1*w1+x2*w2</blockquote>
<blockquote>Kondisi percabangannya adalah dimana ketika Output lebih besar sama dengan dua(O>=2),
Maka hasil akhir akan menunjukkan pernyataan TRUE</blockquote>

Untuk rumus Output NOT :
<blockquote>O=x*w</blockquote>
<blockquote>Kondisi percabangannya adalah dimana ketika Ouput lebih besar sama dengan negative setengah
(O>=-0.5), maka hasil akhir akan menunjukkan pernyataan TRUE</blockquote>




