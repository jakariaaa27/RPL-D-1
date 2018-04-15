<html>
<body>
<div align="center"><h1> Software Design Description</h1></div>

<p align="center"><b>Version 1.7 </b><br>
<p align="center">19 Maret 2018</b>
<p align="center">
<img src="https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/POLINDRA.png" width="250" height="250"/ >
</p>

<p align="center"><b>Manajemen Administrasi Data Kependudukan Desa Lohbener
</b>
<p align="center">Kelompok 1 <br>
 Hilmy Lazuardi 				(1603099)<br>
 Ismatul Maula		(1603100)<br>
 jakaria			(1603101)<br><br><br>

<p align="center"><b>Jurusan Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b>
<p align="center"><b>2018</b>
</p>
</body>
</html>
 


**BAB I PENDAHULUAN**

**1.1** **Tujuan**

Tujuan pembuatan SDD (Software Design Description) ini adalah untuk menjelaskan langkah-langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada Manajemen Administrasi Data Kependudukan Desa Lohbener, dan juga memberi definisi kebutuhan untuk sistem dan spesifikasi kebutuhan fungsional. Fungsi utama dari aplikasi ini yaitu dapat memudahkan admin desa dalam menginput data yang ada di desa Lohbener.

**1.2** **Lingkup Masalah**

Administrasi data ini di desain dengan kebutuhan pihak pemerintahan desa Lohbener desa lohbener. Untuk bidang pemerintahan desa aplikasi ini dirancang untuk menginputkan data seperti angka kelahiran, angka kematian, bidang pendidikan jumlah wanita maupun laki-laki dan lain-lain. Setelah admin menginputkan data tersebut maka data tersebut akan di export kedalam grafik sehingga kepala desa dapat memantau mengenai perkembangan penduduk desa Lohbener. Adanya fungsi laporan surat bulanan untuk pemerintah desa seperti angka kelahiran dan lain sebagainya. Dibidang kepala desa, kepala desa mampu mengetahui grafik perkembangan penduduk serta mengetahui laporan desa lohbener menggunakan aplikasi berbasis website. 

**1.3** **Definisi dan Istilah**

Adapun definisi, istilah dan singkatan yang digunakan dalam dokumen SDD ini adalah :

a. SDD : Software Design Description

b. CDM : Conceptual Data Model

c. PDM : Physicall Data Model

d. Query : Ekspresi yang digunakan dalam pengaksesan basis data


**1.4** **Referensi**
Dokumen yang digunakan sebagai acuan/rujukan dalam penyusunan dokumen SDD ini yaitu :
- IEEE, IEEE Draft Standard for Software Design Descriptions. IEEE P1 01 6/D5.0; 1 2 December 2005
- Eka Ismantohadi & Moh. Yani, Software Design Document (SDD). 2018

**1.5** **Ikhtisar Dokumen**

Bab I Pendahuluan, terdiri dari :

1.1 Tujuan Penulisan Dokumen

1.2 Lingkup Masalah

1.3 Definisi dan Istilah

1.4 Referensi

1.5 Ikhtisar Dokumen

Bab II Deskripsi Perancangan Global

2.1 Rancangan Lingkungan Implementasi

2.2 Deskripsi Data

2.2.1 Definisi Domain/type

2.2.2 Conceptual Data Model

2.2.3 Physical Data Model

2.2.4 Daftar Tabel Aplikasi

2.3 Deskripsi Modul

Bab III Deskripsi Perancangan Rinci

3.1 Diagram Konteks

3.1.1 DFD Level 0

3.1.2 DFD Level 1 Proses M

3.1.3 DFD Level 1 Proses N

3.2 Deskripsi Rinci Tabel

3.2.1 Table A

3.2.2 Table B

3.3 Deskripsi Rinci Modul

3.3.1 D Modul

3.3.1.1 Fungsi Modul

3.3.1.2 Spesifikasi Layar Utama

3.3.1.3 Spesifikasi Query

3.3.1.4 Spesifikasi Field Data Layar

3.3.1.5 Spesifikasi Obyek Pada Layer

3.3.1.6 Spesifikasi Proses/Algoritma

3.4 Matriks Keturunan

**BAB II DESKRIPSI PERANCANGAN GLOBAL**

**2.1 Rancangan Lingkungan Implementasi**

Dalam pengembangan sistem informasi SDD ini, rancangan lingkungan implementasi yang digunakan adalah sebagai berikut :

a. Sistem operasi

Sistem Operasi yang digunakan adalah :

-   Microsoft Windows 7
-   Microsoft Windows 10

b. DBMS

- DBMS yang digunakan adalah Mysql

c. Development tools

- Menggunakan Sublime Text 

d. Bahasa Pemograman

- Pada Admin (Web) menggunakan bahasa pemrograman PHP, HTML, Bootstrap dan CSS.

**2.2 Deskripsi Data**
Deskripsi tabel-tabel basis data yang terlibat dalam aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener adalah sebagai berikut :

**Tabel User**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_user| Integer | 3 | Primary key| Iya|Auto_increment | Nomer auto increment Id_user|
| Username | varchar | 25 |Tidak | Tidak | - | berisikan Nik untuk akses login user dan username untuk akses admin |
| Password | varchar | 25 |Tidak | Tidak | - | berisikan password untuk login admin dan user |
| level | varchar | 15 |Tidak | Tidak | - | untuk membedakan level saat login antara admin dan user

**Tabel Warga**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_warga| Integer | 3 |Primary key | Iya | Auto_increment | Nomer auto increment Id_warga|
| nik | varchar | 17 |Tidak | Tidak | - | nomer kependudukan|
| nama | varchar | 50 |Tidak | Tidak |- | nama kependudukan|
| alamat | text | | Tidak| Tidak | - | alamat lengkap masyarakat |
| agama | varchar | 17 |Tidak | Tidak |- | agama kependudukan|

**Tabel Pegawai**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_pegawai| integer | 3 |Primary key | Iya | Auto_increment | Nomer auto increment Id_pegawai|
| Id_user| varchar | 3 |Tidak | Foreign key | id_user pada user | untuk mengambil username dan password admin pada tabel user|
|nik | varchar | 17 | Tidak| Tidak | -| nik kependudukan |
|nama| varchar | 25 |Tidak | Tidak | - | nama pegawai |
|jabatan | varchar | 25 |Tidak | Tidak | -| jabatan pegawai |
|tgl_masuk | date |  |Tidak | Tidak | -| jabatan pegawai |
|tgl_keluar | date |  |Tidak | Tidak | -| jabatan pegawai |
|status | varchar | 9 |Tidak | Tidak | -| status pegawai |

**Tabel Kelahiran**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_kelahiran| integer | 6 | Primary key| Iya | Auto_increment | Nomer auto increment Id_kelahiran|
| id_warga | integer | 3 |Tidak | Foreign key | id_warga pada warga | r lasi untuk menampilkan warga|
| nama | varchar | 50 |Tidak  | Tidak | - | nama anak|
| ayah | varchar | 50 |Tidak  | Tidak | - | nama anak|
| ibu| varchar | 50 |Tidak  | Tidak | - | nama anak|
| tgl_lahir| date | |Tidak  | Tidak | - | tanggal lahir anak |
| tmp_lahir | varchar | 50 |Tidak  | Tidak | - | tempat lahir anak|
| jns_kelamin| varchar |9 | | Tidak | - | jenis kelamin anak|
| alamat | varchar | 50 |Tidak  | Tidak | - | alamat lahit anak|

**Tabel Kematian**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_kematian| integer | 3 |Primary key | Iya | Auto_increment | Nomer auto increment Id_kematian|
| id_warga | integer | 3 |Tidak | Foreign key | id_warga pada warga | r lasi untuk menampilkan warga|
| tgl_kematian| date | |Tidak  | Tidak | - | tanggal lahir anak |
| jns_kelamin| varchar |9 |Tidak | Tidak | -| jenis kelamin orang meninggal|
| tmp_kematian| varchar |50 |Tidak | Tidak | -|tempat orang meninggal|
| rt | integer | 2 |Tidak | Tidak | - | rt warga|
| rw | integer | 2 |Tidak | Tidak | - | rw warga|

**Tabel Agama**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_agama| integer | 3 |primary key | Iya | Auto_increment | Nomer auto increment Id_agama|
| id_warga | integer | 3 |Tidak | Foreign key | id_warga pada warga | r lasi untuk menampilkan warga|
| agama| varchar |25|Tidak | Tidak | - | agama masyarakat  |


**Tabel Pekerjaan**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_pekerjaan| varchar |6 |primary key | iya|auto_increment |Nomer auto increment Id_pekerjaan|
| id_warga | integer | 3 |Tidak | Foreign key | id_warga pada warga | r lasi untuk menampilkan warga|
| pekerjaan| varchar |50|tidak|tidak|-| jenis pekerjaan  |
| tgl_input| date ||tidak|tidak|-| jenis pekerjaan  |

**Tabel Pendidikan**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_pendidikan| integer | 6 | primary key| iya | auto_increment | Nomer auto increment Id_pendidikan|
| id_warga | integer | 3 |Tidak | Foreign key | id_warga pada warga | r lasi untuk menampilkan warga|
| pendidikan| varchar | 25 |tidak | Tidak | - | Banyaknya anggaran Desa|
| tgl_masuk | date | |tidak | Tidak | - |tanggal masuk anggaran |


**Tabel ktp**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_ktp| integer | 3 | primary key| iya | auto_increment | Nomer auto increment Id_ktp|
| id_warga | integer | 3 |Tidak | Foreign key | id_warga pada warga | r lasi untuk menampilkan warga|
| status_ktp| varchar | 15 |tidak | Tidak | - | status dari ktp warga|
| masa_berlaku | date | |tidak | Tidak | - |masa berlaku ktp |


**Tabel kk**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_kk| integer | 3 | primary key| iya | auto_increment | Nomer auto increment Id_kk|
| id_warga | integer | 3 |Tidak | Foreign key | id_warga pada warga | r lasi untuk menampilkan warga|
| kepala_keluarga| varchar | 50 |tidak | Tidak | - | nama kepala keluarga|
| no_kk | varchar | 17|tidak | Tidak | - |nomor kk |

**Tabel pindah**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_pindah| integer | 3 | primary key| iya | auto_increment | Nomer auto increment Id_pindah|
| id_warga | integer | 3 |Tidak | Foreign key | id_warga pada warga | r lasi untuk menampilkan warga|
| tgl_pindah| date |  |tidak | Tidak | - | tanggal pindah warga|
| ket | varchar | 50|tidak | Tidak | - |keterangan alamat pindah |

**Tabel datang**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_datang| integer | 3 | primary key| iya | auto_increment | Nomer auto increment Id_datang|
| id_warga | integer | 3 |Tidak | Foreign key | id_warga pada warga | r lasi untuk menampilkan warga|
| tgl_datang| date |  |tidak | Tidak | - | tanggal datang warga|
| ket | varchar | 50|tidak | Tidak | - |keterangan alamat datang |

**Tabel pilih**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_pilih| integer | 3 | primary key| iya | auto_increment | Nomer auto increment Id_pilih|
| id_warga | integer | 3 |Tidak | Foreign key | id_warga pada warga | r lasi untuk menampilkan warga|
| status_pilih| varchar | 25 |tidak | Tidak | - | status pilih warga|

**Tabel pernikahan**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_nikah| integer | 3 | primary key| iya | auto_increment | Nomer auto increment Id_pilih|
| id_warga | integer | 3 |Tidak | Foreign key | id_warga pada warga | r lasi untuk menampilkan warga|
| status_nikah| varchar | 25 |tidak | Tidak | - | status nikah warga|


**Tabel Laporan**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_laporan| integer | 3 | | Primary key | tidak | Nomer auto increment Id_laporan|
| nama_laporan | varchar | 50 | | Tidak | tidak | nama laporan |
| jns_laporan| text | | | tidak | tidak | jenis laporan|
| tgl_laporan | date | | | tidak | tidak | tanggal laporan |
| link | text || | tidak | tidak | link download laporan |

**2.2.1 Definisi Domain/Type**

**Tabel User**

| Domain name | Keterangan |
| ------ | ------ |
| Id_user| integer | 
| Username | varchar | 
| Password | varchar | 
| level | varchar | 

**Tabel Warga**

| Domain name | Keterangan |
| ------ | ------ | 
| NIK | varchar | 
| Nama | varchar | 
|jns_kelamin| varchar |
| Tgl_lahir | date | 
| Agama | varchar |  

**Tabel Pegawai**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_pegawai| integer | 
| Id_warga| integer | 
|nik | varchar |
|jabatan | varchar |
|tgl_masuk | date |
|tgl_keluar | date|

**Tabel Kelahiran**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_kelahiran| integer | 
| Id_warga| integer | 
| Tgl_lahir | date | 
|jns_kelamin| varchar |
|ayah| varchar |
|ibu| varchar |
| tmp_lahir| varchat | 
| rt| integer |
| rw| integer | 

**Tabel Kematian**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_kematian| integer | 
| Id_warga| integer | 
| tmp_kematian | varchar | 
| tgl_kematian| date | 
| rt| integer |
| rw| integer | 

**Tabel Agama**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_agama| varchar | 
| Id_warga| integer | 
| agama| varchar | 

**Tabel Pekerjaan**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_pekerjaan|integer | 
| Id_warga| integer | 
| pekerjaan| varchar | 
|tgl_input | date |

**Tabel Pendidikan**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_pendidikan|integer | 
| Id_warga| integer | 
|pendidikan|varchar|
| tgl_masuk | date |
 
**Tabel Ktp**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_ktp|integer | 
| Id_warga| integer | 
|status_ktp|varchar|
| masa_berlaku| varchar| 

**Tabel Kk**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_kk|integer | 
| Id_warga| integer | 
|kepala_keluarga|varchar|
| no_kk| varchar| 

**Tabel Pindah**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_pindah|integer | 
| Id_warga| integer | 
|tgl_pindah|date|
| ket| varchar| 

**Tabel Datang**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_datang|integer | 
| Id_warga| integer | 
|tgl_datang|date|
| ket| varchar| 

**Tabel Pilih**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_pilih|integer | 
| Id_warga| integer |
| satus_pilih| varchar| 

**Tabel Kawin**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_kawin|integer | 
| Id_warga| integer |
| satus_kawin| varchar| 

**Tabel Laporan**

| Domain name | Keterangan |
| ------ | ------ | 
| Id_laporan| integer | 
| Id_warga| integer | 
| laporan| varchar |

**2.2.2 Conceptual Data Model**


**2.2.3 Physical Data Mode**


**2.2.4 Daftar Tabel Aplikasi**


**Tabel User**

| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ |
| Id_user| Primary Key | D7 | Auto increment | Nomer auto increment Id_user|
| Username | tidak | D7 | Tidak ada | berisikan Nik untuk akses login user dan username untuk akses admin |
| Password | tidak|  D7 | Tidak ada | berisikan password untuk login admin dan user |
| level | tidak | D7 | Tidak ada | untuk membedakan level saat login antara admin dan user |


**Tabel Masyarakat**

| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ | 
| Id_masyarakat| Primary key | D7 | Auto increment | Nomer auto increment Id_masyarakat|
| Id_user| Foreign key | D7 | Tabel user | untuk mengambil username dan password peserta pada tabel user|
| NIK | tidak | D7 | Tidak ada | nomer kependudukan|
| Nama_lengkap | tidak | D7 | Tidak ada | nomer kependudukan|
| Tmp_lahir | tidak| D7 | Tidak ada | tempat lahir peserta |
| Tgl_lahir |tidak| D7 | Tidak ada | tanggal lahir peserta |
| Alamat | tidak | D7 | Tidak ada | alamat lengkap peserta |
| Telp | tidak | D7 | Tidak ada | nomer telepon peserta |


**Tabel Admin**

| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ | 
| Id_admin| Primary key | D7 | Auto increment | Nomer auto increment Id_admin|
| Id_user| Foreign key | D7 | Tabel user | untuk mengambil username dan password admin pada tabel user|
|nik | tidak | D7 | tidak ada | nik kependudukan |
|nama|tidak | D7 | tidak ada  | nama admin |
|jabatan |tidak | D7 | tidak ada  | jabatan admin |
|email|tidak | D7 | tidak ada  | email admin |
| telp |tidak | D7 | tidak ada  | nomer telepon admin |
|foto| tidak | D7 | tidak ada  | foto admin |


**Tabel Kependudukan**

| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ | 
| Id_admin| Foreign key |- | Tabel admin | untuk mengidentifikasi admin|
| Id_masyarakat| Foreign key | - | Tabel masyarakat | untuk mengidentifikasi peserta|
| Id_kelahiran| Foreign key | - | Tabel kelahiran | untuk mengidentifikasi kelahiran|
| Id_kematian| Foreign key | - | Tabel kematian | untuk mengidentifikasi kematian|
| Id_agama| Foreign key | - | Tabel agama | untuk mengidentifikasi agama|
| Id_pekerjaan| Foreign key | - | Tabel pekerjaan | untuk mengidentifikasi pekerjaan |
| Id_angdes| Foreign key | - | Tabel angdes | untuk mengidentifikasi anggaran desa|
| Id_laporan| Foreign key | - | Tabel laporan | untuk mengidentifikasi laporan|

**Tabel Kelahiran**

| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ | 
| Id_kelahiran| primary key | D1 | Auto increment | Nomer auto increment Id_kelahiran|
| nama | tidak | D1 | Tidak ada | nama anak|
| tgl_lahir| tidak | D1 | Tidak ada | tanggal lahir anak |
| jns_kelamin|tidak | D1 | Tidak ada | jenis kelamin anak|

**Tabel Kematian**

| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ | 
| Id_kematian| Primary key | D2 | Auto increment | Nomer auto increment Id_kematian|
| nama | tidak | D2 | Tidak ada | nama orang meninggal |
| tgl_kematian|tidak | D2 | Tidak ada | tanggal lahir anak |
| jns_kelamin| tidak | D2 | Tidak ada | jenis kelamin orang meninggal|


**Tabel Agama**

| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ | 
| Id_agama| Primary key | D3 | Auto increment | Nomer auto increment Id_agama|
| nama | tidak | D3 | Tidak ada | nama masyarakat |
|jns_kelamin | tidak| D3 | tidak ada |jenis kelamin masyarakat |
| agama| tidak | D3 tidak ada|| agama masyarakat  |
|tgl_input| tidak | D3 | tidak ada tanggal inputan |

**Tabel Pekerjaan**

| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ | 
| Id_pekerjaan| Primary key | D4 |Auto increment | Nomer auto increment Id_pekerjaan|
| nama | tidak | D4 | Tidak ada | nama masyarakat |
| pekerjaan|  tidak | D4 | Tidak ada | jenis pekerjaan  |

**Tabel Anggaran Desa**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_angdes| Primary key | D5 | Auto increment | Nomer auto increment Id_angdes|
| nama_anggaran |  tidak | D5 | Tidak ada |  nama anggaran desa |
| jml_dana|  tidak | D5 | Tidak ada | Banyaknya anggaran Desa|
| tgl_masuk | tidak | D5 | Tidak ada | tanggal masuk anggaran |
| alokasi_dana |  tidak | D5 | Tidak ada | keterangan penggunaan dana |

**Tabel Laporan**

| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ | 
| Id_laporan| primary key |- | Auto increment | Nomer auto increment Id_laporan|
| nama_laporan |  tidak | - | Tidak ada | nama laporan |
| jns_laporan| tidak | - | Tidak ada | jenis laporan|
| tgl_laporan |  tidak | - | Tidak ada | tanggal laporan |
| link | tidak | - | Tidak ada | link download laporan |

**2.3 Deskripsi Modul**

| No | Nama Modul | Deskripsi |
|--|--|--|
| 1 | Agama | Modul yang mencakup input, edit, delete dan update semua data agama |
| 2 | Pekerjaan | Modul yang mencakup input, edit, delete dan update semua data pekerjaan |
| 3 | Pendidikan | Modul yang mencakup input, edit, delete dan update semua data pendidikan |
| 4 | Kelahiran | Modul yang mencakup input, edit, delete dan update semua data kelahiran |
| 5 | Datang | Modul yang mencakup input, edit, delete dan update semua data datang |
| 6 | Warga | Modul yang mencakup input, edit, delete dan update semua data warga |
| 7 | Pernikahan | Modul yang mencakup input, edit, delete dan update semua data pernikahan |
| 8 | Kematian | Modul yang mencakup input, edit, delete dan update semua data kematian |
| 9 | Pegawai | Modul yang mencakup input, edit, delete dan update semua data pegawai |
| 10 | KK | Modul yang mencakup input, edit, delete dan update semua data kk |
| 11 | KTP | Modul yang mencakup input, edit, delete dan update semua data ktp |
| 12 | User | Modul yang mencakup input, edit, delete dan update semua data user |
| 13 | Login | Modul yang di gunakan untuk vailidasi akses masuk ke sistem Manajemen Adminstrasi Data di web |
| 14 | Laporan Kematian | Modul yang digunakan untuk mendata semua hasil kematian |
| 15 | Laporan Kelahiran | Modul yang digunakan untuk mendata semua hasil kelahiran |
| 16 | Laporan Datang | Modul yang digunakan untuk mendata semua hasil datang |
| 17 | Laporan Warga | Modul yang digunakan untuk mendata semua hasil warga |
| 18 | Laporan Penikahan | Modul yang digunakan untuk mendata semua hasil pernikahan |
| 19 | Laporan KTP | Modul yang digunakan untuk mendata semua hasil ktp |
| 20 | Laporan KK | Modul yang digunakan untuk mendata semua hasil kk |


**BAB 3 DESKRIPSI PERANCANGAN RINCI**

**3.1 Diagram konteks**

Diagram konteks adalah diagram yang terdiri dari suatu proses dan menggambarkan ruang lingkup suatu sistem. Diagram konteks merupakan level tertinggi dari DFD yang menggambarkan seluruh input ke dalam sistem atau output dari sistem yang memberi gambaran tentang keseluruhan sistem. Sistem dibatasi oleh boundary (digambarkan dengan garis putus - putus). Dalam diagram konteks hanya ada satu proses, tidak boleh ada store dalam diagram konteks. Berikut ini adalah gambar diagram konteks dari sistem Aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener.

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/Diagram%20context.PNG)

**3.1.1 DFD Level 0**
Data Flow Diagram atau biasa disingkat dengan DFD adalah salah satu cara untuk memodelkan proses dalam analisis dan perancangan perangkat lunak, khususnya dengan pendekatan terstruktur. Berikut DFD Level 0 Manajemen Administrasi Data Kependudukan Desa Lohbener.

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/diagram%20levell%200.png)

**3.1.2 DFD Level 1 Proses **

DFD Level 1 ini penjelasan dari DFD Level 0 yang sebelumnya, berikut DFD level 1 
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/diagram%20level%201.png)



**3.1.3 DFD Level 2 Proses**

DFD Level 2 ini penjelasan dari DFD Level 0 yang sebelumnya, berikut DFD level 2 
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/diagram%20level%202.png)

**3.1.3 DFD Level 3 Proses**

DFD Level 3 ini penjelasan dari DFD Level 0 yang sebelumnya, berikut DFD level 3 

![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/diagram%20level%203.png)


**3.1.3 DFD Level 4Proses**

DFD Level 4 ini penjelasan dari DFD Level 0 yang sebelumnya, berikut DFD level 4 

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/diagram%20level%204.png)



**3.2 Deskripsi Rinci Tabel**

**3.2.1 Data User Masyarakat, Admin Desa, Kepala Desa**

| Data | Keterangan |
| ------ | ------ | 
| NIK|digunakan untuk login | 


**3.3 Modul**

**3.3.1 Modul Agama**

**3.3.1.1 Fungsi Modul**

| No| Fungsi | jenis | Tabel terkait | Kategori |
| ------ | ------ | ------ | ------ | ------ | 
| 1 | Input Data Agama | Import File | Admin  |Web |
| 2 | Delete Data Agama| Import File atau Form Modal | Admin |Web|
| 3 | Update Data Agama | Button Warning | Admin |Web |
| 4 | Menampilkan Data Agama | Tabel| Admin |Web |


**3.3.1.2 Spesifikasi Layar Utama**

![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/Screenshot%20%28505%29.png)

**3.3.1.3 Spesifikasi Query**

| ID Query | Deskripsi | Ekspresi Query |
| ------ | ------ | ------ |
| QRY-01 | Input Data Agama | INSERT INTO agama SET agama="$agama"; |
| QRY-02 | Delete Data Agama |DELETE FROM agama WHERE id_agama="$id_agama";|
| QRY-03 | Update Data Agama |UPDATE agama SET agama="$agama";|
| QRY-04 | Menampilkan Data Agama |SELECT * FROM agama;|


**3.3.1.4 Spesifikasi Field Data Layar**

| Label | Field | Tabel/Query | Validasi | Keterangan |
| ------ | ------ | ------ | ------ | ------ |
|Id_agama | Id_agama | agama | - | primary key dan diinputkan otomatis oleh sistem |
| id_warga | id_warga | warga | - | forigen key yang di ambil dari warga menandakan id ini dimiliki warga tersebut dan ini dipilih oleh admin |
|agama | agama | agama | required, regex:/^[a-zA-Z]+$/u, string, max:255 | nama pendidikan diinputkan manual oleh admin |


**3.3.1.5 Spesifikasi Objek-Objek pada Layar**

| id_users | jenis | keterangan | Kategori|
|------|------|------|------|
|agama | input type text | masukkan nama agama |WEB|
|btnTambah | Button tambah | untuk menambahkan agama |WEB|
|btnSimpan | Button Submit| untuk menyimpan data yang di inputkan |WEB|
|btnEdit | Button Primary | Tombol untuk memunculkan Modal edit agama |WEB|


**3.3.1.6 Spesifikasi Proses/Algoritma**

OP01 : Tambah Agama
Objek Terkait : agama
Event : Tambah agama

|Inisial State (IS)|
|--|
| Form agama kosong |

|Final State (FS)|
|--|
| Tabel agama di update dengan data yang baru |

|Spesifikasi Proses/Algoritma|
|--|
| IF data agama sudah ada |
| THEN data tidak di masukan dan ulang input |
| ELSE masukan data ke database dan update data agama yang lama |

#### 3.3.2 Modul Pendidikan

**3.3.2.1 Fungsi Modul**

| No| Fungsi | jenis | Tabel terkait | Kategori |
| ------ | ------ | ------ | ------ | ------ | 
| 1 | Input Data Pendidikan | Import File | Admin  |Web |
| 2 | Delete Data Pendidikan| Import File atau Form Modal | Admin |Web|
| 3 | Update Data Pendidikan | Button Warning | Admin |Web |
| 4 | Menampilkan Data Pendidikan | Tabel| Admin |Web |

**3.3.2.2 Spesifikasi Layar Utama**

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/Screenshot%20%28506%29.png)

**3.3.2.3 Spesifikasi Query**

| ID Query | Deskripsi | Ekspresi Query |
| ------ | ------ | ------ |
| QRY-01 | Input Data Pendidikan | INSERT INTO pendidikan SET pendidikan="$pendidikan"; |
| QRY-02 | Delete Data Pendidikan |DELETE FROM pendidikan WHERE id_pendidikan="$id_pendidikan";|
| QRY-03 | Update Data Pendidikan |UPDATE pendidikan SET pendidikan="$pendidikan";|
| QRY-04 | Menampilkan Data Pendidikan |SELECT * FROM pendidikan;|

**3.3.2.4 Spesifikasi Field Data Layar**

| Label | Field | Tabel/Query | Validasi | Keterangan |
| ------ | ------ | ------ | ------ | ------ |
|Id_pendidikan | Id_pendidikan | pendidikan | - | primary key dan diinputkan otomatis oleh sistem |
| id_warga | id_warga | warga | - | forigen key yang di ambil dari warga menandakan id ini dimiliki warga tersebut dan ini dipilih oleh admin |
|pendidikan| pendidikan | pendidikan | required, regex:/^[a-zA-Z]+$/u, string, max:255 | nama pendidikan diinputkan manual oleh admin |
| tgl_masuk | tgl-masuk | date | - | tanggal masuk pendidikan |

**3.3.2.5 Spesifikasi Objek-Objek pada Layar**

| id_users | jenis | keterangan | Kategori|
|------|------|------|------|
|pendidikan | input type text | masukkan nama pendidikan |WEB|
|btnTambah | Button tambah | untuk menambahkan pendidikan |WEB|
|btnSimpan | Button Submit| untuk menyimpan data yang di inputkan |WEB|
|btnEdit | Button Primary | Tombol untuk memunculkan Modal edit pendidikan |WEB|

**3.3.2.6 Spesifikasi Proses/Algoritma**

OP02 : Tambah Pendidikan
Objek Terkait : pendidikan
Event : Tambah pendidikan

|Inisial State (IS)|
|--|
| Form pendidikan kosong |

|Final State (FS)|
|--|
| Tabel pendidikan di update dengan data yang baru |

|Spesifikasi Proses/Algoritma|
|--|
| IF data pendidikan sudah ada |
| THEN data tidak di masukan dan ulang input |
| ELSE masukan data ke database dan update data pendidikan yang lama |

#### 3.3.3 Modul Pekerjaan

**3.3.3.1 Fungsi Modul**

| No| Fungsi | jenis | Tabel terkait | Kategori |
| ------ | ------ | ------ | ------ | ------ | 
| 1 | Input Data Pekerjaan | Import File | Admin  |Web |
| 2 | Delete Data Pekerjaan| Import File atau Form Modal | Admin |Web|
| 3 | Update Data Pekerjaan | Button Warning | Admin |Web |
| 4 | Menampilkan Data Pekerjaan | Tabel| Admin |Web |

**3.3.3.2 Spesifikasi Layar Utama**

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/Screenshot%20%28507%29.png)

**3.3.3.3 Spesifikasi Query**

| ID Query | Deskripsi | Ekspresi Query |
| ------ | ------ | ------ |
| QRY-01 | Input Data Pekerjaan | INSERT INTO pekerjaan SET pekerjaan="$pekerjaan"; |
| QRY-02 | Delete Data Pekerjaan |DELETE FROM pekerjaan WHERE id_pekerjaan="$id_pekerjaan";|
| QRY-03 | Update Data Pekerjaan |UPDATE pekerjaan SET pekerjaan="$pekerjaan";|
| QRY-04 | Menampilkan Data Pekerjaan |SELECT * FROM pekerjaan;|

**3.3.3.4 Spesifikasi Field Data Layar**

| Label | Field | Tabel/Query | Validasi | Keterangan |
| ------ | ------ | ------ | ------ | ------ |
|Id_pekerjaan | Id_pekerjaan | pekerjaan | - | primary key dan diinputkan otomatis oleh sistem |
| id_warga | id_warga | warga | - | forigen key yang di ambil dari warga menandakan id ini dimiliki warga tersebut dan ini dipilih oleh admin |
|pekerjaan| pekerjaan | pekerjaan | required, regex:/^[a-zA-Z]+$/u, string, max:255 | nama pekerjaan diinputkan manual oleh admin |
| tgl_input | tgl_input | date | - | tanggal input pekerjaan |

**3.3.3.5 Spesifikasi Objek-Objek pada Layar**

| id_users | jenis | keterangan | Kategori|
|------|------|------|------|
|pekerjaan | input type text | masukkan nama pekerjaan |WEB|
|btnTambah | Button tambah | untuk menambahkan pekerjaan |WEB|
|btnSimpan | Button Submit| untuk menyimpan data yang di inputkan |WEB|
|btnEdit | Button Primary | Tombol untuk memunculkan Modal edit pekerjaan |WEB|

**3.3.3.6 Spesifikasi Proses/Algoritma**

OP03 : Tambah Pekerjaan
Objek Terkait : pekerjaan
Event : Tambah pekerjaan

|Inisial State (IS)|
|--|
| Form pekerjaan kosong |

|Final State (FS)|
|--|
| Tabel pekerjaan di update dengan data yang baru |

|Spesifikasi Proses/Algoritma|
|--|
| IF data pekerjaan sudah ada |
| THEN data tidak di masukan dan ulang input |
| ELSE masukan data ke database dan update data pekerjaan yang lama |

#### 3.3.4 Modul Kelahiran

**3.3.4.1 Fungsi Modul**

| No| Fungsi | jenis | Tabel terkait | Kategori |
| ------ | ------ | ------ | ------ | ------ | 
| 1 | Input Data Kelahiran| Import File | Admin  |Web |
| 2 | Delete Data Kelahiran| Import File atau Form Modal | Admin |Web|
| 3 | Update Data Kelahiran | Button Warning | Admin |Web |
| 4 | Menampilkan Kelahiran | Tabel| Admin |Web |

**3.3.4.2 Spesifikasi Layar Utama**

![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/Screenshot%20%28511%29.png)

**3.3.4.3 Spesifikasi Query**

| ID Query | Deskripsi | Ekspresi Query |
| ------ | ------ | ------ |
| QRY-01 | Input Data Kelahiran | INSERT INTO kelahiran SET kelahiran="$kelahiran"; |
| QRY-02 | Delete Data Kelahiran |DELETE FROM kelahiran WHERE id_kelahiran="$id_kelahiran";|
| QRY-03 | Update Data Kelahiran |UPDATE kelahiran SET kelahiran="$kelahiran";|
| QRY-04 | Menampilkan Data Kelahiran |SELECT * FROM kelahiran;|

**3.3.4.4 Spesifikasi Field Data Layar**

| Label | Field | Tabel/Query | Validasi | Keterangan |
| ------ | ------ | ------ | ------ | ------ |
|Id_kelahiran | Id_kelahiran | kelahiran | - | primary key dan diinputkan otomatis oleh sistem |
| id_warga | id_warga | warga | - | forigen key yang di ambil dari warga menandakan id ini dimiliki warga tersebut dan ini dipilih oleh admin |
|nama| nama | kelahiran | required, regex:/^[a-zA-Z]+$/u, string, max:255 | nama kelahiran diinputkan manual oleh admin |
| tgl_lahir | tgl_lahir | kelahiran | - | tanggal lahir diinputkan manual oleh admin  |
| ayah | ayah | kelahiran | - | nama ayah diinputkan manual oleh admin |
| ibu | ibu | kelahiran | - | nama ibu diinputkan manual oleh admin |
| tmp_lahir | tmp_lahir | kelahiran | - | tempat lahir diinputkan manual oleh admin |
| alamat | alamat | kelahiran | - |alamat lahir diinputkan manual oleh admin |
| jns_kelamin| jns_kelamin| kelahiran | - |jenis kelamin diinputkan manual oleh admin |

**3.3.4.5 Spesifikasi Objek-Objek pada Layar**

| id_users | jenis | keterangan | Kategori|
|------|------|------|------|
|kelahiran | input type text | masukkan nama kelahiran |WEB|
|btnTambah | Button tambah | untuk menambahkan kelahiran |WEB|
|btnSimpan | Button Submit| untuk menyimpan data yang di inputkan |WEB|
|btnEdit | Button Primary | Tombol untuk memunculkan Modal edit kelahiran |WEB|

**3.3.4.6 Spesifikasi Proses/Algoritma**

OP04 : Tambah Kelahiran
Objek Terkait : kelahiran
Event : Tambah kelahiran

|Inisial State (IS)|
|--|
| Form kelahiran kosong |

|Final State (FS)|
|--|
| Tabel kelahiran di update dengan data yang baru |

|Spesifikasi Proses/Algoritma|
|--|
| IF data kelahiran sudah ada |
| THEN data tidak di masukan dan ulang input |
| ELSE masukan data ke database dan update data kelahiran yang lama |

#### 3.3.5 Modul Pegawai

**3.3.5.1 Fungsi Modul**

| No| Fungsi | jenis | Tabel terkait | Kategori |
| ------ | ------ | ------ | ------ | ------ | 
| 1 | Input Data Pegawai| Import File | Admin  |Web |
| 2 | Delete Data Pegawai| Import File atau Form Modal | Admin |Web|
| 3 | Update Data Pegawai | Button Warning | Admin |Web |
| 4 | Menampilkan Pegawai | Tabel| Admin |Web |

**3.3.5.2 Spesifikasi Layar Utama**

![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/Screenshot%20%28512%29.png)

**3.3.5.3 Spesifikasi Query**

| ID Query | Deskripsi | Ekspresi Query |
| ------ | ------ | ------ |
| QRY-01 | Input Data Pegawai | INSERT INTO pegawai SET pegawai="$pegawai"; |
| QRY-02 | Delete Data Pegawai |DELETE FROM pegawai WHERE id_pegawai="$id_pegawai";|
| QRY-03 | Update Data Pegawai |UPDATE pegawai SET pegawai="$pegawai";|
| QRY-04 | Menampilkan Data Pegawai |SELECT * FROM pegawai;|

**3.3.5.4 Spesifikasi Field Data Layar**

| Label | Field | Tabel/Query | Validasi | Keterangan |
| ------ | ------ | ------ | ------ | ------ |
|Id_pegawai | Id_kelahiran | kelahiran | - | primary key dan diinputkan otomatis oleh sistem |
| id_user | id_user | user | - | forigen key yang di ambil dari user menandakan id ini dimiliki user tersebut dan ini dipilih oleh admin |
|nik| nik| warga | required, regex:/^[a-zA-Z]+$/u, string, max:255 | nik diambil dari tabel warga |
|nama| nama | pegawai | required, regex:/^[a-zA-Z]+$/u, string, max:255 | nama pegawai diinputkan manual oleh admin |
| tgl_masuk | tgl_masuk | pegawai | - | tanggal masuk diinputkan manual oleh admin  |
| tgl_keluar | tgl_keluar| pegawai | - | tanggal kealuar diinputkan manual oleh admin  |
| status| status | pegawai | - |status user diinputkan manual oleh admin |

**3.3.5.5 Spesifikasi Objek-Objek pada Layar**

| id_users | jenis | keterangan | Kategori|
|------|------|------|------|
|pegawai | input type text | masukkan nama pegawai |WEB|
|btnTambah | Button tambah | untuk menambahkan pegawai |WEB|
|btnSimpan | Button Submit| untuk menyimpan data yang di inputkan |WEB|
|btnEdit | Button Primary | Tombol untuk memunculkan Modal edit pegawai |WEB|

**3.3.5.6 Spesifikasi Proses/Algoritma**

OP05 : Tambah Pegawai
Objek Terkait : pegawai
Event : Tambah pegawai

|Inisial State (IS)|
|--|
| Form pegawai kosong |

|Final State (FS)|
|--|
| Tabel pegawai di update dengan data yang baru |

|Spesifikasi Proses/Algoritma|
|--|
| IF data pegawai sudah ada |
| THEN data tidak di masukan dan ulang input |
| ELSE masukan data ke database dan update data pegawai yang lama |

**3.4 Matriks Kerunutan**
