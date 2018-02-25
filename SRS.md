**Software Requirements Specification**

**Version beta**

22/2/2018

**MORSA LOHBENER**
**Monitoring Desa Lohbener**


kelompok 1 :
- Hilmy lazuardi (1603099)
- Ismatul maula (1603100)
- Jakaria (1603101)

**Jurusan D3 Teknik Informatika**
**Politeknik Negeri Indramayu**
**2018**


1. BAB I Pendahuluan

1.1 Tujuan

Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun "Aplikasi Monitoring Desa Lohbener". Dokumen ini dibangun untuk memudahkan penduduk desa Lohbener dalam melihat perkembangan yang ada didesa nya dan memudahkan admin untuk menginput data-data kependudukan yang ada di Lohbener. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "MOSRA LOHBENER" (monitoring desa lohbener).

1.2	Lingkup

MORSA LOHBENER merupakan aplikasi yang kami bangun untuk mempermudah penduduk desa Lohbener dalam melihat perkembangan yang ada di desanya khususnya perkembangan Anggaran desa, Kelulusan, piramida, pendidikan, kependudukan, agama, pekerjaan. dan memudahkan admin dalam mnginput data-datanya.

1.3	 Akronim, singkatan, definisi

Akronim dan singkatan :
 - Morsa : Monitoring Desa Lohbener
- SRS : Software Requirement Specification

Definisi :
- software Requirement Specification adalah perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna
- use case adalah situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda. 

1.4	Referensi
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :
- https://code18.blogspot.co.id/2016/01/definisi-android-studio.html
- http://hasantarmizi.blogspot.co.id/2017/04/pengertian-sublime-text.html

1.5	Overview		

Dokumen SRS ini dibagi menjadi tiga bagian utama, yaitu :
- bagian pertama berisi penjelasan tentang dokumen SRS yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan oleh perangkat lunak yang dikembangkan, definisi, referensi dan deskripsi umum.
- Bagian kedua berisi penjelasan secara umum mengenai Aplikasi Random Grup yang akan dibangun, meliputi fungsi dari perangkat lunak, karakteristik pengguna, batasan dan asumsi yang diambil dala pembuatan perangkat lunak.
- Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih rinci.

2. BAB II Gambaran umum

2.1	Perspektif produk

- Antarmuka sistem

Perangkat lunak ini mempunyai ketergantungan kepada sistem admin.

- Antarmuka pengguna

Antarmuka pengguna yang digunakan untuk mengoperasikan Perangkat Lunak MORSA Lohbener antara lain :
   <ol><li> Tampilan awal web </li>
    <li>Tampilan Input Kependudukan, Pendidikan, Agama, Pekerjaan, Anggaran Desa dan Laporan untuk admin. </li> 
    <li>Tampilan monitoring pada menu user dan fungsi komentar </li>
    <li>Tampilan login di website </li> 
    <li>Tampilan login di Android </li>
    <li>Tampilan pendaftaran akun user pada android </li></ol>
    
- Antarmuka perangkat keras

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak MORSA Lohbener antara lain :
  <ol><li>PC atau Laptop</li>
  <li>Android</li>
  <li>Mouse</li>
  <li>Keyboard</li>
  <li>Monitor</li>
  
- Antarmuka komunikasi

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak MORSA Lohbener antara lain :
 <ol><li>Kabel Lan UTP RJ45</li>
 <li>Modem</li>
 <li>wifi</li><ol>

- Batasan memori
- Operasi-operasi
- Kebutuhan adaptasi

2.2	Spesifikasi Kebutuhan fungsional

- Tabel Kebutuhan Fungsional 

| No | Deskripsi |
| ------ | ------ |
| 1 | Perangkat lunak dapat menampilkan halaman login pada website  |
| 2 | Perangkat lunak dapat menampilkan halaman login pada android |
| 3 | Perangkat lunak dapat menampilkan Halaman daftar akun pada android |
| 4 | Perangkat lunak dapat menginputkan kependudukan, pendidikan ,agama, pekerjaan, anggaran dan laporan pada website admin
| 5 | Perangkat lunak dapat menampilkan grafik pada halaman sistem user |
| 6 | Perangkat lunak dapat mengirimkan notifikasi komentar user kepada admin |
| 7 | Perangkat lunak dapat mengirimkan notifikasi apabila ada user baru yang mendaftar akun |

2.3	Spesifikasi Kebutuhan non-fungsional

- Tabel Kebutuhan Non-Fungsional 

| No | Deskripsi |
| ------ | ------ |
| 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
| 2 | Perangkat Lunak mampu mengirimkan notifikasi kepada admin maksimal dalam waktu 1 menit |
| 3 | Perangkat lunak menolak input pengguna yang akan mendaftarkan diri dengan password kurang dari 8 karakter |
| 4 | Perangkat Lunak dapat dipakai di platofrm Windows ( Admin ) dan Android Os ( User ) 
2.4	Karakteristik pengguna

Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5	Batasan-batasan

- Perangkat lunak web hanya dijalankan di windows (7,8,10). Dan perangkat lunak mobile hanya bisa dijalankan di android (min. API 16/Jelly Bean).
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.

2.6	Asumsi-asumsi

Maksimal penginputan data atau memasukkan nama pada aplikasi ini adalah 9999, lebih dari itu program akan muncul peringatan"Anda telah melebihi batas maksimum".

2.7	Kebutuhan Penyeimbang

3. BAB III Requirement specification
	

