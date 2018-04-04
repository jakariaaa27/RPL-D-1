<html>
<body>
<div align="center"><h1> Software Design Description</h1></div>

<p align="center"><b>Version 1.5 </b><br>
<p align="center">19 Maret 2018</b>
<p align="center">
<img src="https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/POLINDRA.png" width="250" height="250"/ >
</p>

<p align="center"><b>Monitoring Perkembangan Kependudukan Desa Lohbener
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

Tujuan pembuatan SDD (Software Design Description) ini adalah untuk menjelaskan langkah-langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada Monitoring Perkembangan Penduduk Desa Lohbener (Merdu Saloh), dan juga memberi definisi kebutuhan untuk sistem dan spesifikasi kebutuhan fungsional. Fungsi utama dari aplikasi ini yaitu dapat memudahkan admin desa dalam menginput data yang ada di desa Lohbener.

**1.2** **Lingkup Masalah**

Monitoring ini di desain dengan kebutuhan pihak pemerintahan desa Lohbener dan kebutuhan penduduk desa lohbener .Untuk bidang pemerintahan desa aplikasi ini dirancang untuk menginputkan data seperti angka kelahiran, angka kematian ,bidang pendidikan jumlah wanita maupun laki-laki dan transparasi dana .Setelah admin menginputkan data tersebut maka data tersebut akan di export kedalam grafik sehingga masyarakat dapat memantau mengenai perkembangan desa Lohbener .Adanya fungsi laporan surat bulanan untuk pemerintah desa seperti angka kelahiran dan lain sebagainya. dibidang masyarakat, masyarakat mampu mengetahui perkembangan desa Lohbener serta mengetahui transparasi dana desa lohbener menggunakan aplikasi berbasis android ( mobile ). Masyarakat dapat mengirim kritik dan saran mengenai perkembangan desa Lohbener dengan fungsi yang tersedia saat login.

**1.3** **Definisi dan Istilah**

Adapun definisi, istilah dan singkatan yang digunakan dalam dokumen SDD ini adalah :

a. SDD : Software Design Description

b. CDM : Conceptual Data Model

c. PDM : Physicall Data Model

d. Query : Ekspresi yang digunakan dalam pengaksesan basis data

e. Merdu Saloh : Montoring perkembangan penduduk desa lohbener

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
Sistem operasi yang digunakan untuk pengembangan perangkat lunak adalah :
- Untuk aplikasi server menggunakan Sublime Text untuk membuat web nya.
- Untuk aplikasi client menggunakan Android Studio untuk membuat android nya.
- Untuk aplikasi pembuatan laporan menggunakan Microsoft Word 2010.
b. DBMS
DBMS yang digunakan adalah MySql.
c. Development tools
- Menggunakan Android Studio
- Menggunakan Sublime Text 
d. Filling system
e. Bahasa Pemograman
Bahasa yang digunakan bahasa Java (android)

**2.2 Deskripsi Data**
Deskripsi tabel-tabel basis data yang terlibat dalam aplikasi monitoring perkembangan penduduk desa lohbener adalah sebagai berikut :

**Tabel User**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_user| Integer | 3 | | Primary key |Tidak | Nomer auto increment Id_user|
| Username | varchar | 16 | | Tidak | Tidak | berisikan Nik untuk akses login user dan username untuk akses admin |
| Password | varchar | 15 | | Tidak | Tidak | berisikan password untuk login admin dan user |
| level | varchar | 11 | | Tidak | Tidak | untuk membedakan level saat login antara admin dan user

**Tabel Masyarakat**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_masyarakat| Integer | 3 | | Primary key | Tidak | Nomer auto increment Id_masyarakat|
| Id_user| Integer | 3 | | Primary key | Tabel user | untuk mengambil username dan password peserta pada tabel user|
| NIK | varchar | 16 | | Tidak | Tidak | nomer kependudukan|
| Nama | varchar | 25 | | Tidak |Tidak | nama kependudukan|
|jns_kelamin | Text | | | Tidak | Tidak | jenis kelamin masyarakat|
| Tmp_lahir | varchar | 25 | | Tidak | Tidak | tempat lahir masyarakat |
| Tgl_lahir | date | | | Tidak | Tidak | tanggal lahir masyarakat |
| Alamat | text | | | Tidak | Tidak | alamat lengkap masyarakat |
| Telp | varchar | 13 | | Tidak | Tidak |nomer telepon masyarakat |


**Tabel Admin**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_admin| integer | 3 | | Primary key | Tidak | Nomer auto increment Id_admin|
| Id_user| varchar | 3 | | Primary key | Tabel user | untuk mengambil username dan password admin pada tabel user|
|nik | varchar | 17 | | Tidak | Tidak | nik kependudukan |
|nama| varchar | 25 | | Tidak | Tidak | nama admin |
|jabatan | varchar | 25 | | Tidak | Tidak | jabatan admin |
|email|varchar | 50 | | Tidak | Tidak | email admin |
| telp | varchar | 13 | | Tidak | Tidak | nomer telepon admin |
|foto| text | | | Tidak | Tidak | foto admin |

**Tabel Kepedudukan**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_admin| Integer | 3 | | Primary key | Tabel admin | untuk mengidentifikasi admin|
| Id_masyarakat| Integer | 3 | Primary key | Tabel masyarakat | untuk mengidentifikasi peserta|
| Id_kelahiran| Integer| 3 | | Primary key | Tabel kelahiran | untuk mengidentifikasi kelahiran|
| Id_kematian| Integer | 3 | | Primary key | Tabel kematian | untuk mengidentifikasi kematian|
| Id_agama| Integer | 3 | | Primary key | Tabel agama | untuk mengidentifikasi agama|
| Id_pekerjaan| Integer | 3 | | Primary key | Tabel pekerjaan |untuk mengidentifikasi pekerjaan |
| Id_angdes| Integer | 3 | | Primary key | Tabel angdes | untuk mengidentifikasi anggaran desa|
| Id_laporan|Integer | 3 | | Primary key | Tabel laporan | untuk mengidentifikasi laporan|

**Tabel Kelahiran**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_kelahiran| integer | 3 | | Primary key | Tidak | Nomer auto increment Id_kelahiran|
| nama | varchar | 50 | | Tidak | Tidak | nama anak|
| tgl_lahir| date | | | Tidak | Tidak | tanggal lahir anak |
| jns_kelamin| text | | | Tidak | Tidak | jenis kelamin anak|

**Tabel Kematian**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_kematian| integer | 3 | | Primary key | Tidak | Nomer auto increment Id_kematian|
| nama | varchar | 50 | | Tidak | Tidak | nama orang meninggal |
| tgl_kematian| date | | | Tidak | Tidak | tanggal lahir anak |
| jns_kelamin| text | | | Tidak | Tidak | jenis kelamin orang meninggal|

**Tabel Agama**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_agama| integer | 3 | | primary key | Tidak | Nomer auto increment Id_agama|
| nama | varchar | 3 | | Tidak | Tidak | nama masyarakat |
|jns_kelamin | text | | Tidak |Tidak |jenis kelamin masyarakat |
| agama| text || | Tidak | Tidak | agama masyarakat  |
|tgl_input| date | | |Tidak | Tidak | tanggal inputan |

**Tabel Pekerjaan**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_pekerjaan| varchar | Nomer auto increment Id_pekerjaan|
| nama | varchar | nama masyarakat |
| pekerjaan| varchar | jenis pekerjaan  |

**Tabel Anggaran Desa**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_angdes| integer | 3 | | Primary key | Tidak | Nomer auto increment Id_angdes|
| nama_anggaran | varchar | 50 | | Tidak | Tidak | nama anggaran desa |
| jml_dana| varchar | 20 | | Tidak | Tidak | Banyaknya anggaran Desa|
| tgl_masuk | date | | | Tidak | Tidak |tanggal masuk anggaran |
| alokasi_dana | text | | | tidak |tidak | keterangan penggunaan dana |

**Tabel Laporan**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_laporan| integer | 3 | | Primary key | tidak | Nomer auto increment Id_laporan|
| nama_laporan | varchar | 50 | | Tidak | tidak | nama laporan |
| jns_laporan| text | | | tidak | tidak | jenis laporan|
| tgl_laporan | date | | | tidak | tidak | tanggal laporan |
| link | text || | tidak | tidak | link download laporan |

**Tabel Krisan (kritik dan saran)**

| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Id_krisan| integer | 3 | | primary key| tidak | Nomer auto increment Id_krisan|
| krisan | text | | | tidak | tidak |  memasukan kritik dan saran |
| status| varchar | 10 | | tidak | tidak | Untuk mengirim sebuah kritik dan saran tentang perkembangan |

**Tabel Akun**
| Nama tabel | Jenis | Volume | Laju | Primary key | Constraint integrity |  Deskripsi | 
| ------ | ------ | ------ | ------ | ------ | ------ | ------ | ---- | ---- |
| Id_akun| integer | 3 | | primary key| tidak | Nomer auto increment Id_akun|
| status| varchar | 10 | | tidak | tidak |  status akun |


**2.2.1 Definisi Domain/Type**
**Tabel User**

| Domain name | Power Designer Type |
| ------ | ------ |
| Id_user| integer | 
| Username | varchar | 
| Password | varchar | 
| level | varchar | 

**Tabel Masyarakat**

| Domain name | Power Designer Type |
| ------ | ------ | 
| Id_masyarakat| integer | 
| Id_user| integer | 
| NIK | varchar | 
| Nama_lengkap | varchar | 
|jns_kelamin| text |
| Tmp_lahir | varchar | 
| Tgl_lahir | date | 
| Alamat | text | 
| Telp | varchar | 


**Tabel Admin**

| Domain name | Power Designer Type |
| ------ | ------ | 
| Id_admin| integer | 
| Id_user| integer | 
|nik | varchar |
|nama | varchar |
|jabatan | varchar |
|email | varchar |
|foto | text |

**Tabel Kepedudukan**

| Domain name | Power Designer Type |
| ------ | ------ | 
| Id_admin| integer | 
| Id_masyarakat|integer| 
| Id_kelahiran| integer | 
| Id_kematian|integer | 
| Id_agama|integer | 
| Id_pekerjaan| integer | 
| Id_angdes| integer | 
| Id_laporan| integer | 

**Tabel Kelahiran**

| Domain name | Power Designer Type |
| ------ | ------ | 
| Id_kelahiran| integer | 
| nama | varchar | 
| tgl_lahir| date | 
| jns_kelamin| text | 

**Tabel Kematian**

| Domain name | Power Designer Type |
| ------ | ------ | 
| Id_kematian| integer | 
| nama | varchar | 
| tgl_kematian| date | 
| jns_kelamin| varchar |  

**Tabel Agama**

| Domain name | Power Designer Type |
| ------ | ------ | 
| Id_agama| varchar | 
| nama | varchar | 
|jns_kelamin | text |
| agama| varchar | 

**Tabel Pekerjaan**

| Domain name | Power Designer Type |
| ------ | ------ | 
| Id_pekerjaan|integer | 
| nama | varchar | 
|jns_kelamin | text |
| pekerjaan| varchar | 
|tgl_input | date |

**Tabel Anggaran Desa**

| Domain name | Power Designer Type |
| ------ | ------ | 
| Id_angdes|integer | 
| nama_anggaran | varchar | 
| jml_dana| varchar | 
| tgl_masuk | date | 
| alokasi_dana | text | 

**Tabel Laporan**

| Domain name | Power Designer Type |
| ------ | ------ | 
| Id_laporan| integer | 
| nama_laporan | varchar | 
| jns_laporan| text | 
| tgl_laporan | date | 
| link | text | 

**Tabel Krisan (kritik dan saran)**

| Domain name | Power Designer Type |
| ------ | ------ | 
| Id_krisan| primary key |
| krisan |text | 
| status| varchar | 

**Tabel Akun**

| Domain name | Power Designer Type |
| ------ | ------ | 
| Id_akun| primary key |
| status| varchar | 

**2.2.2 Conceptual Data Model**
**2.2.3 Physical Data Mode**
**2.2.4 Daftar Tabel Aplikasi**

** Tabel User **
| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ | 
| Id_user| Primary Key | D7 | Auto increment | Nomer auto increment Id_user|
| Username | tidak | D7 | Tidak ada | berisikan Nik untuk akses login user dan username untuk akses admin |
| Password | tidak|  D7 | Tidak ada | berisikan password untuk login admin dan user |
| level | tidak | D7 | Tidak ada | untuk membedakan level saat login antara admin dan user

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

**Tabel Krisan (kritik dan saran)**

| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ | 
| Id_krisan| primary key |- | Auto increment | Nomer auto increment Id_krisan|
| krisan |  tidak | - | Tidak ada | memasukan kritik dan saran |
| status| tidak | - | Tidak ada | Untuk mengirim sebuah kritik dan saran tentang perkembangan |

** Tabel Akun**

| Nama Tabel  | Primary Key | Data Store | E/R | Deskripsi isi |
| ------ | ------ | ------ | ------ | ------ | 
| Id_akun| Primary eky |-| tidak ada | Nomer auto increment Id_akun|
| status| tidak | - | tidak ada | status akun |


**2.3 Deskripsi Modul**


**BAB 3 DESKRIPSI PERANCANGAN RINCI**
** 3.1 Diagram konteks**
Diagram konteks adalah diagram yang terdiri dari suatu proses dan menggambarkan ruang lingkup suatu sistem. Diagram konteks merupakan level tertinggi dari DFD yang menggambarkan seluruh input ke dalam sistem atau output dari sistem yang memberi gambaran tentang keseluruhan sistem. Sistem dibatasi oleh boundary (Digambarkan dengan garis putus - putus). Dalam diagram konteks hanya ada satu proses, tidak boleh ada store dalam diagram konteks. Berikut ini adalah gambar diagram konteks dari sistem Aplikasi Monitoring Perkembangan Penduduk Desa Lohbener.

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/diagram%20konteks.jpg)


**3.1.1 DFD Level 0**
Data Flow Diagram atau biasa disingkat dengan DFD adalah salah satu cara untuk memodelkan proses dalam analisis dan perancangan perangkat lunak, khususnya dengan pendekatan terstruktur. Berikut DFD Level 0 Monitoring Perkembangan Kependudukan Desa Lohbener.


![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/dfd%20level%200%20revisi.jpg)

**3.1.2 DFD Level 1 Proses M**

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/dfd%20level%201.jpg)

**3.1.3 DFD Level 1 Proses N**
DFD ini menjelaskan tentang proses pada tabel kelahiran dimana pada tabel ini admin dapat menambahkan data kelahiran, menghapus data kelahiran, menampilakan ata kelahiran pada user

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/dfd%20level%201.6.1.jpg)


![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/dfd%20level%201.2.1.jpg)

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/dfd%20level%201.3.1.jpg)

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/dfd%20level%201.4.1.jpg)

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/dfd%20level%201.5.1.jpg)

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SDD/dfd%20%20level%201.1.1.jpg)

**3.2 Deskripsi Rinci Tabel**

**3.2.1 Data User Masyarakat, Admin Desa, Kepala Desa**
| Data | Keterangan |
| ------ | ------ | 
| NIK|digunakan untuk login | 


**3.3 Modul**

**3.3.1.1 Fungsi Modul**

**3.3.1.2 Spesifikasi Layar Utama**

**3.3.1.3 Spesifikasi Query**

**3.3.1.4 Spesifikasi Field Data Layar**

**3.3.1.5 Spesifikasi Objek-Objek pada Layar**

**3.3.1.6 Spesifikasi Proses/Algoritma**

**3.4 Matriks Kerunutan**





