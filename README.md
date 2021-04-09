<h1>Bahasa Pemrograman R</h1>
<p align="justify"><b>Bahasa Pemrograman R</b> adalah nama sebuah bahasa pemrograman sekaligus software untuk pengolahan data dan grafik. Mulai dari membaca file teks, membaca database, menghasilkan berbagai grafik, menghasilkan dashboard yang menarik, sampai ke penggunaan machine learning semuanya tersedia di R. Selain itu, R bersifat gratis dan open source. </p>
<p align="justify"><b>Ada empat alasan utama membuat para data scientist tertarik belajar dan menggunakan Pemrograman R :</b> </br>
1. Lebih kaya fitur (Richer): Dengan puluhan ribu fitur yang terus berkembang, hampir semua permasalahan data dapat dijawab oleh R. Sebagai contoh, untuk mengatasi permasalahan optimasi stok di e-commerce, R memiliki fungsi menghasilkan rekomendasi product packaging. </br>
2. Lebih Mudah Dipelajari (Easier): R relatif lebih mudah dipelajari dibandingkan dengan bahasa lain, seperti Java, C#, Javascript, dan lain-lain. </br>
3. Telah terbukti (Proven): R sudah digunakan oleh banyak data scientist perusahaan besar seperti Anz, Uber, dan Facebook dan memberikan solusi riil. Tidak heran jika akhirnya dari kisah sukses ini, banyak lowongan data scientist mencamtumkan R sebagai syarat keterampilan yang harus dimiliki.</br>
4. Lebih Cepat (Faster): Banyak fungsi R memberikan hasil jauh lebih cepat dibandingkan dengan aplikasi lain.
Contoh: R dapat menghasilkan berbagai visualisasi yang menarik dalam waktu singkat, sehingga data scientist dapat jauh lebih produktif dalam memahami data dan menghasilkan informasi.</p>
<table><tr><th style="width:130px">Source Coding</th>   <th style="width:80px">Output</th> </tr>
  <tr><td> 9</td>        <td>>9</br>[1] 9</td>      </tr>
  <tr><td> "Budi"</td>   <td>>"Budi" </br>[1] "Budi"</td> </tr>
  <tr><td> 9 * 3 </td>   <td>>9 * 3 </br>[1] 27</td>     </tr>     </table>
<table><caption><b>Keterangan Dari Source Coding Diatas : </b></caption>
  <tr><th>Nama</th> <th>Keterangan</th></tr>
  <tr> <td>></td> <td>Prompt dari R</td></tr>
  <tr>  <td>9 * 3</td><td>Perintah untuk melakukan perkalian angka 9 dan 3</td></tr>
   <tr>  <td>[1]</td> <td>Menunjukkan posisi urutan dari hasil output pertama. Kebetulan disini output hanya ada satu item, yaitu angka 27 jadi posisinya otomatis adalah 1.</td></tr>
  <tr> <td>27</td> <td>Hasil output.</td></tr></table>
 <table><caption><b> Menampilkan dengan Fungsi Print</b></caption>
<tr><th style="width:130px">Source Coding</th>   <th style="width:80px">Output</th> </tr>
  <tr><td> print("Hello World")</td>  <td>>print("Hello World")</br>[1] "Hello World"</td></tr>
  <tr><td> print(3 + 4) </td>   <td>>print(3 + 4)</br>[1] 7 </td> </tr></table>

<table><caption><b> Variable :</b></caption>
<tr><th>Source Coding</th>   <th >Output</th> </tr>
<tr><td>budi_berat_kg<- 68 </br> santi_berat_kg <- 54.5 </br> budi_berat_kg </br></br> santi_berat_kg</br></br></td> <td></br></br>>budi_berat_kg</br>[1] 68</br> >santi_berat_kg </br>[1] 54.5</td> </tr> 
   <tr><td> pi <- 3.14 </br> pi</br></br></td>  <td></br>>pi <- 3.14</br>[1] 3.14 </td>      </tr>    </table>
<p align="justify"><b>Comment pada R </b></br>Comment atau komentar adalah teks yang bisa dimasukkan di R, tapi tidak dianggap sebagai code yang bisa dieksekusi. Comment ini biasanya digunakan sebagai catatan untuk menjelaskan potongan code yang ada. Membuat comment sangat mudah. Caranya adalah menuliskan tanda pagar (<b></b>#) yang kemudian diikuti dengan tulisan apapun.</p>
<details>
  <summary>2 + 2 #Ini adalah baris komentar</summary>
  <p><i>Output :</i> [1] 4</p>
</details>
