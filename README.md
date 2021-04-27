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
  <table border="0"><tr><td><i>Output :</i></td><td>>2 + 2</br> [1] 4</td></tr></table>
</details>

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE, comment = "", message = F, warning = F)
```

### Code Pertama, Hello World!
<a href="https://academy.dqlab.id/main/livecode/1/3/635">Link materi : https://academy.dqlab.id/main/livecode/1/3/635</a>

```plantuml
"Hello World"
1 + 5
```

### Teks, Angka dan Rumus Perhitungan
<a href="https://academy.dqlab.id/main/livecode/1/3/6">Link materi : https://academy.dqlab.id/main/livecode/1/3/6</a>

```plantuml
9
"Budi"
9 * 3
```

### Menampilkan dengan Fungsi Print
<a href="https://academy.dqlab.id/main/livecode/1/3/705">Link materi : https://academy.dqlab.id/main/livecode/1/3/705</a>

```plantuml
print("Hello World")
print(3 + 4)
```

### Huruf Besar, Huruf Kecil dan Format Angka
<a href="https://academy.dqlab.id/main/livecode/1/3/636">Link materi : https://academy.dqlab.id/main/livecode/1/3/636</a>

```plantuml
01
1
"01-01-1980"
"1-1-1980"
"Budi"
"BUDI"
```

### Function
<a href="https://academy.dqlab.id/main/livecode/1/3/7">Link materi : https://academy.dqlab.id/main/livecode/1/3/7</a>

```plantuml
c(5:10)
```

### Variable 
<a href="https://academy.dqlab.id/main/livecode/1/3/10">Link materi : https://academy.dqlab.id/main/livecode/1/3/10</a>

```plantuml
budi_berat_kg <- 68
santi_berat_kg <- 54.5
budi_berat_kg
santi_berat_kg
pi <- 3.14
pi
```

### Comment pada R
<a href="https://academy.dqlab.id/main/livecode/1/3/9">Link materi : https://academy.dqlab.id/main/livecode/1/3/9</a>

```plantuml
2 + 2 # Ini adalah baris komentar
```

### Vector 
<a href="https://academy.dqlab.id/main/livecode/1/4/14">Link materi : https://academy.dqlab.id/main/livecode/1/4/14</a>

```plantuml
#Ini adalah contoh vector untuk angka numerik dengan 3 data c(4, 5, 6)
c(4, 5, 6)
#Variable bernama angka dengan input berupa vector
angka <- c(4, 5, 6)
#Tampilkan isi variable angka dengan fungsi print
print(angka)
```

### Deretan Nilai dengan Operator : 
<a href="https://academy.dqlab.id/main/livecode/1/4/708">Link materi : https://academy.dqlab.id/main/livecode/1/4/708</a>

```plantuml
angka1 <- c(1, 2, 3, 4, 5, 6, 7, 8, 9, 10)
print(angka1)
angka2 <- c(1:10)
print(angka2)
```

### Vector dengan Isi Teks 
<a href="https://academy.dqlab.id/main/livecode/1/4/709">Link materi : https://academy.dqlab.id/main/livecode/1/4/709</a>

```plantuml
#Variable nama_mahasiswa dengan input character
nama_mahasiswa <- c("Amira","Budi","Charlie")
print(nama_mahasiswa)
```

### Index dan Accessor pada Vector 
<a href="https://academy.dqlab.id/main/livecode/1/4/15">Link materi : https://academy.dqlab.id/main/livecode/1/4/15</a>

```plantuml
#Buat vector variable bernama angka yang isinya 20 s/d 30
angka <- c(20:30)
print(angka)
#Tampilkan isi variable angka pada posisi ke 3
print(angka[3])
#Tampilkan isi variable angka pada posisi ke 5
print(angka[[5]])
#Tampilkan isi variable angka pada posisi ke 4 s/d 6
print(angka[4:6])
#Buat vector teks dengan nama kode_prodi yang diisi sesuai petunjuk soal
kode_prodi <- c("DKV","ILKOM","ICT")
#Tampilkan isi indeks ketiga dari kode_prodi
print(kode_prodi[3])
```

### Named Vector 
<a href="https://academy.dqlab.id/main/livecode/1/4/16">Link materi : https://academy.dqlab.id/main/livecode/1/4/16</a>

```plantuml
#Membuat named vector dengan nama nilai
nilai <- c(statistik = 89, 
           fisika = 95, 
           ilmukomunikasi = 100)
#Menampilkan isi variable nilai
print(nilai)
#Menampilkan isi dengan nama fisika
print(nilai["fisika"])
#Buat variable profil sesuai permintaan soal
profil <- c(nama = "Budi", 
            tempat_tinggal = "Jakarta", 
            tingkat_pendidikan = "S1")
#Tampilkan variable profil
print(profil)
```

### List 

<a href="https://academy.dqlab.id/main/livecode/1/4/17">Link materi : https://academy.dqlab.id/main/livecode/1/4/17</a>


```plantuml
#List disimpan dalam variable dengan nama list_random
list_random <- list(2, "Budi", 4)
#Menampilkan isi list
list_random 
#List disimpan dalam variable dengan nama dati2
dati2 <- list(nama = "Denpasar", 
              propinsi = "Bali")
#Menampilkan isi list dati2
dati2 
#Buat variable kota sesuai permintaan soal
kota <- list(nama_kota = "Makassar", 
             propinsi = "Sulawesi Selatan", 
             luas_km2 = 199.3)
#Tampilkan isi variable list kota
print(kota)
```

### List Index 
<a href="https://academy.dqlab.id/main/livecode/1/4/18">Link materi : https://academy.dqlab.id/main/livecode/1/4/18</a>

```plantuml
#Membentuk list dengan 2 angka dan 1 character
list_saya <- list(2, "Budi", 4)
#Menampilkan index kedua dengan aksesor kurung siku tunggal 
list_saya[2]
#Menampilkan index kedua dengan aksesor kurung siku ganda
list_saya[[2]]
#Menampilkan index kedua s/d ketiga
list_saya[2:3]
list_satu <- list(1, "Online", TRUE)
list_satu[1]
```

### Data Frame 
<a href="https://academy.dqlab.id/main/livecode/1/4/20">Link materi : https://academy.dqlab.id/main/livecode/1/4/20</a>

```plantuml
#Membuat dua variable vector
fakultas <- c("Bisnis", "D3 Perhotelan", "ICT", "Ilmu Komunikasi", "Seni dan Desain")
jumlah_mahasiswa <- c(260, 28, 284, 465, 735)
#Membuat data frame dari kedua vector di atas
info_mahasiswa <- data.frame(fakultas, jumlah_mahasiswa)
#Melihat isi data frame
info_mahasiswa
#Buat vector baru sebagai representasi akreditasi
akreditasi <- c("A","A","B","A","A")
#Buat data frame dari ketiga vector di atas
info_mahasiswa <- data.frame(info_mahasiswa, akreditasi)
info_mahasiswa
```

### Cara Akses Data Frame 
<a href="https://academy.dqlab.id/main/livecode/1/4/21">Link materi : https://academy.dqlab.id/main/livecode/1/4/21</a>
```plantuml
# Membuat tiga variable vector
fakultas <- c("Bisnis", "D3 Perhotelan", "ICT", "Ilmu Komunikasi", "Seni dan Desain")
jumlah_mahasiswa <- c(260, 28, 284, 465, 735)
akreditasi <- c("A","A","B","A","A")
# Membuat data frame dari kedua vector di atas
info_mahasiswa <- data.frame(fakultas, jumlah_mahasiswa, akreditasi)
# Menampilkan kolom jumlah_mahasiswa
info_mahasiswa$jumlah_mahasiswa
# Menampilkan kolom fakultas
info_mahasiswa$fakultas
```

### Package ggplot2 
<a href="https://academy.dqlab.id/main/livecode/1/5/766">Link materi : https://academy.dqlab.id/main/livecode/1/5/766</a>

```plantuml
fakultas <- c("Bisnis", "D3 Perhotelan", "ICT", "Ilmu Komunikasi", "Seni dan Desain")
jumlah_mahasiswa <- c(260, 28, 284, 465, 735)
akreditasi <- c("A","A","B","A","A")
info_mahasiswa <- data.frame(fakultas, jumlah_mahasiswa, akreditasi)
info_mahasiswa
# Menggunakan package ggplot2
library("ggplot2")
# Membuat kanvas
gambar <- ggplot(info_mahasiswa, aes(x=fakultas, y=jumlah_mahasiswa, fill=fakultas)) + 
          geom_bar(width=1, stat="identity")
gambar
```

### Membuat Grafik Sebaran Mahasiswa (1) 
<a href="https://academy.dqlab.id/main/livecode/1/5/22">Link materi : https://academy.dqlab.id/main/livecode/1/5/22</a>

```plantuml
#Membuat dua vector
fakultas <- c("Bisnis", "D3 Perhotelan", "ICT", "Ilmu Komunikasi", "Seni dan Desain")
jumlah_mahasiswa <- c(260, 28, 284, 465, 735)
akreditasi <- c("A","A","B","A","A")
#Buat data frame dari ketiga vector di atas
info_mahasiswa <- data.frame(fakultas, jumlah_mahasiswa, akreditasi)
info_mahasiswa
#Menggunakan package ggplot2
library(ggplot2)
#Membuat kanvas
gambar <- ggplot(info_mahasiswa, aes(x=fakultas, y=jumlah_mahasiswa, fill=fakultas))
#Menambahkan objek bar chart, simpan kembali sebagai variable gambar
gambar <- gambar + geom_bar(width=1, stat="identity")
#Menambahkan judul grafik
gambar <- gambar + ggtitle("Jumlah Mahasiswa per Fakultas")
#Menambahkan caption pada sumbu x
gambar <- gambar + xlab("Nama Fakultas")
#Menambahkan caption pada sumbu y
gambar <- gambar + ylab("Jumlah Mahasiswa")
#Menggambar grafik
gambar
```

### Membaca File Excel 
<a href="https://academy.dqlab.id/main/livecode/1/5/24">Link materi : https://academy.dqlab.id/main/livecode/1/5/24</a>

```plantuml
#Menggunakan package ggplot2
library(ggplot2)
#Menggunakan package openxlsx
library(openxlsx)
#Membaca file mahasiswa.xlsx
mahasiswa <- read.xlsx("https://academy.dqlab.id/dataset/mahasiswa.xlsx", sheet = "Sheet 1")
#Menampilkan data
print(mahasiswa)
#Menampilkan kolom Prodi
print(mahasiswa$Prodi)
```

### Membuat Grafik Sebaran Mahasiswa (2) 
<a href="https://academy.dqlab.id/main/livecode/1/5/770">Link materi : https://academy.dqlab.id/main/livecode/1/5/770</a>

```plantuml
library(ggplot2)
#Menggunakan package openxlsx
library(openxlsx)
#Membaca file mahasiswa.xlsx
mahasiswa <- read.xlsx("https://academy.dqlab.id/dataset/mahasiswa.xlsx", sheet = "Sheet 1")
#Membuat kanvas
gambar <- ggplot(mahasiswa, aes(x=Fakultas, y=JUMLAH, fill=Fakultas))
#Menambahkan objek bar chart, simpan kembali sebagai variable gambar
gambar <- gambar + geom_bar(width=1, stat="identity")
#Menggambar grafik
gambar
```

### Trend Jumlah Mahasiswa dari Tahun ke Tahun 
<a href="https://academy.dqlab.id/main/livecode/1/5/767">Link materi : https://academy.dqlab.id/main/livecode/1/5/767</a>

```plantuml
library(ggplot2)
#Menggunakan package openxlsx
library(openxlsx)
#Membaca file mahasiswa.xlsx
mahasiswa <- read.xlsx("https://academy.dqlab.id/dataset/mahasiswa.xlsx", sheet = "Sheet 1")
#Menghitung Jumlah Data by Fakultas
summarybyfakultas <- aggregate(x=mahasiswa$JUMLAH, 
                               by=list(Kategori=mahasiswa$Fakultas, Tahun=mahasiswa$ANGKATAN), 
                               FUN=sum)
summarybyfakultas <- setNames(summarybyfakultas, c("fakultas","tahun", "jumlah_mahasiswa"))
summarybyfakultas
summarybyfakultas$tahun = as.factor(summarybyfakultas$tahun)
ggplot(summarybyfakultas, aes(x=fakultas, y=jumlah_mahasiswa)) + 
  geom_bar(stat="identity", aes(fill=tahun), width=0.8, position=position_dodge(width=0.8)) + 
  theme_classic()
```

### Pie Chart 
<a href="https://academy.dqlab.id/main/livecode/1/5/768">Link materi : https://academy.dqlab.id/main/livecode/1/5/768</a>

```plantuml
library(ggplot2)
library(openxlsx)
#Membaca file mahasiswa.xlsx
mahasiswa <- read.xlsx("https://academy.dqlab.id/dataset/mahasiswa.xlsx", sheet = "Sheet 1")
#Menghitung Jumlah Data by Fakultas
summarybyfakultas <- aggregate(x=mahasiswa$JUMLAH, 
                               by=list(Kategori=mahasiswa$Fakultas), 
                               FUN=sum)
summarybyfakultas <- setNames(summarybyfakultas, 
                              c("fakultas","jumlah_mahasiswa"))
piechart<- ggplot(summarybyfakultas, aes(x="", y=jumlah_mahasiswa, fill=fakultas)) + 
            geom_bar(width = 1, stat = "identity")
piechart <- piechart + coord_polar("y", start=0)
piechart <- piechart + ggtitle("Disribusi Mahasiswa per Fakultas")
piechart <- piechart + scale_fill_brewer(palette="Blues") + theme_minimal()
piechart <- piechart + guides(fill=guide_legend(title="Fakultas"))
piechart <- piechart + ylab("Jumlah Mahasiswa") 
piechart
```

### Filtering 
<a href="https://academy.dqlab.id/main/livecode/1/5/769">Link materi : https://academy.dqlab.id/main/livecode/1/5/769</a>

```plantuml
library("ggplot2")
library("openxlsx")
#Membaca file mahasiswa.xlsx
mahasiswa <- read.xlsx("https://academy.dqlab.id/dataset/mahasiswa.xlsx", sheet = "Sheet 1")
#Menghitung Jumlah Data by Fakultas
summarybyfakultas <- aggregate(x=mahasiswa$JUMLAH, 
                               by=list(Kategori=mahasiswa$Fakultas, Tahun=mahasiswa$ANGKATAN), 
                               FUN=sum)
summarybyfakultas <- setNames(summarybyfakultas, c("fakultas","tahun", "jumlah_mahasiswa"))
summarybyfakultas
summarybyfakultas$tahun = as.factor(summarybyfakultas$tahun)
summarybyfakultas[summarybyfakultas$fakultas %in% c("ICT", "Ilmu Komunikasi"),]
ggplot(summarybyfakultas[summarybyfakultas$fakultas %in% c("ICT", "Ilmu Komunikasi"),], 
       aes(x=fakultas, y=jumlah_mahasiswa)) + 
  geom_bar(stat = "identity", aes(fill = tahun), width=0.8, position = position_dodge(width=0.8)) + 
  theme_classic() 
```

<p align="center"><b>E-Sertifikat </b></br><img src="https://github.com/yenysyafitry/R_Fundamental_for_Data_Science/blob/main/e-sertifikat.jpg"></p>
