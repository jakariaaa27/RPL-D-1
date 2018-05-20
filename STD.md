
<html>
<body>
<div align="center"><h1> SOFTWARE TESTING DOCUMENT </h1></div>

<p align="center"><b>Version 1.3 </b><br>
<p align="center">20 Mei 2018</b>
<p align="center">
<img src="https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/POLINDRA.png" width="250" height="250"/ >
</p>

<p align="center"><b>Manajemen Administrasi Data Kependudukan Desa Lohbener <br>
</b>
<p align="center">Kelompok 1 <br>
 Hilmy Lazuardi            (1603099)<br>
 Ismatul Maula    (1603100)<br>
 jakaria       (1603101)<br><br><br>

<p align="center"><b>Jurusan Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b>
<p align="center"><b>2018</b>
</p>
</body>
</html>
 

**BAB I Pendahuluan**
----------
1.1 Tujuan Pembuatan Dokumen
----------

Dokumen ini digunakan sebagai panduan untuk melakukan pengujian terhadap perangkat lunak Manajemen Administrasi Data Kependudukan Desa Lohbener . Dokumen ini dipakai untuk melihat kemampuan dari program yang telah dirancang agar sesuai dengan keinginan dari pengguna. Pembuatan dokumen ini ditujukan untuk menguji perangkat lunak Manajemen Administrasi Data Kependudukan Desa Lohbener yang merupakan bagian dari tugas mata kuliah Rekayasa Perangkat Lunak.


1.2   Deskripsi Umum Sistem
----------

Perangkat lunak yang diuji adalah "Manajemen Administrasi Data Kependudukan Desa Lohbener " perangkat lunak ini adalah perangkat lunak yang digunakan untuk

1.3    Deskripsi Dokumen (Ikhtisar)
----------

Dalam dokumen ini berisi 3 bagian utama yaitu Pendahuluan, Identifikasi dan Rencana Pengujian, Deskripsi dan Uji Hasil.

1.4   Definisi dan Singkatan
----------

-  SKPL adalah Spesifikasi Kebutuhan Perangkat Lunak, atau dalam bahasa Inggris-nya sering juga disebut sebagai Software Requirements Spesification (SRS), dan merupakan spesifikasi dari perangkat lunak yang akan dikembangkan
- SKPL-SK.K-xxxx adalah kode yang digunakan untuk merepresentasikan kebutuhan (requirement) pada SK, dengan SK merupakan kode perangkat lunak, SK.K adalah kode fase, dan xxxx adalah digit/nomor kebutuhan (requirement)
- DFD adalah Data Flow Diagram, diagram dan notasi yang digunakan untuk menunjukkan aliran data pada perangkat lunak.
- ERD adalah Entity Relationship Diagram, diagram dan notasi yang digunakan untuk merepresentasikan struktur data statis pada perangkat lunak.
- DPPL-Akkses.K-xxxx adalah kode yang digunakan untuk mengimplementasikan perancangan pada Akkses, dengan Akkses merupakan kode perangkat lunak, Akkses.Kadalah kode fase, dan xxxx adalahdigit/nomor perancangan.


1.5   Dokumen Referensi
----------

- Ernita H. GL03. Dokumen Uji Perangkat Lunak (DUPL) SDS. Bogor.
- Sistem Pentiketan Elektronik Konser.2013. Spesifikasi Kebutuhan Perangkat Lunak (SKPL)SPEK. Bogor
- Sistem Pentiketan Elektronik Konser.2013. Dokumen Perancangan Perangkat Lunak (DPPL)SPEK. Bogor.


**BAB II Lingkungan Pengujian Perangkat Lunak**
----------

2.1   Perangkat Lunak Pengujian
----------

Perangkat lunak ini Manajemen Administrasi Data Kependudukan Desa Lohbener diujikan dengan beberapa perangkat lunak lain, yaitu :

- Sistem operasi :Windows 10
- Bahasa pemograman : PHP
- Data base : XAMPP
- Framework : CodeIgniter

2.2  Perangkat Keras Pengujian
----------

Perangkat keras yang diperlukan untuk menguji aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener ini adalah satu set laptop dengan spesifikasi :

- Processor : Intel Core i5
- Memory : 4 GB DDR3
- Harddisk : 500 GB


2.3   Material Pengujian
----------




2.4   Sumber Daya Manusia
----------

Persyaratan sumber daya manusia yang akan terlibat dalam proses pengujia perangkat lunak ini adalah :

- Memahami konsep pemograman berorientasi objek dalam bahasa PHP
- Memahami proses pengujian perangkat lunak berorientasi objek
- Memahami konsep pemrograman data base XAMPP


 
2.5   Prosedur Umum Pengujian
----------
**2.5.1 Pengenalan dan latihan**

Pengujian aplikasi ini diujikan oleh kita sebagai Developer. Pada dasar nya penguji memiliki kemampuan tentang pemograman PHP, Data base, dan Framework.

**2.5.2 Persiapan awal**

**2.5.2.1 Persiapan prosedural**

Pengujian ini dilakukan di area local (localhost) dimana pengujian ini dilakukan oleh kita sendiri sebagai Developer. alat yang digunakan 1 buah laptop dengan software yang telah diinstalasi.

**2.5.2.2  Persiapan Perangkat Keras**

Perangkat keras yang diperlukan adalah :
Sebuah perangkat komputer yang dilengkapi dengan :

- Processor : Intel Core i5
- Memory : 4 GB DDR3
- Harddisk : 500 GB

**2.5.2.3 Persiapan perangkat lunak**

Persiapan yang harus dilakukan untuk menyiapkan perangkat lunak untuk diuji di lingkungan sistem operasi Microsoft Windows 7 adalah sebagai berikut : 

-  Persiapkan sistem operasi Microsoft Windows. 
-  Perangkat lunak yang akan di uji di copy ke sebuah direktori, misalnya C:\XAMPP\htdocs. 
-  Browser Google Chrome. 
- Database di import ke phpMyAdmin di database db_konser. 
-  Adobe Dreamweaver atau notepad ++ untuk melihat source code

**2.3.5 Pelaksanaan**

Pelaksanaan pengujian dilakukan dengan mengeksekusi perangkat lunak Manajemen Administrasi Data Kependudukan Desa Lohbener dengan mengikuti skenario tertentu yang dibuat berdasarkan skenario yang terdapat pada dokumen SKPL-Manajemen Administrasi Data Kependudukan Desa Lohbener

**2.4.5 Pelaporan Hasil**

Dokumen hasil uji dari aplikasi ini akan diberikan kepada Pemerintahan Desa Lohbener sebagai mitra proyek kami . sehingga aplikasi mendapatkan umpan balik dalam pengembangan perangkat lunak ini selanjutnya.


BAB III Identifikasi dan Rencana Pengujian
----------
**Tabel 1 Identifikasi dan rencana Pengujian**

<table>  
	<thead>  
<tr>
	<td rowspan="2" align="center"><strong>Kelas Uji</td>
	<td rowspan="2" align="center"><strong>Butir Uji </td>
	<td colspan="2" align="center"><strong>Identifikasi</td>
	<td rowspan="2" align="center"><strong>Tingkat Pengujian</td>
	<td rowspan="2" align="center"><strong>Teknik Pengujian</td>
	<td rowspan="2" align="center"><strong>Penguji</td>
</tr>
		<tr>
			<td align="center"><strong>SRS/SDD</td>
			<td align="center"><strong>STD</td>
		</tr>
<tr>
	<td rowspan="3" align="center"><strong>Login Pegawai IT</td>
	<td>Username dan password yang di inputkan sesuai dengan data</td>
	<td>SRS 2.2.3</td>
	<td>STD 1.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Hilmy</td>
<tr>
	<td>Username dan password yang di inputkan tidak sesuai dengan data</td>
	<td>SRS 2.2.3</td>
	<td>STD 1.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Hilmy</td>
</tr>
<tr>
	<td>Username yang di inputkan sesuai dengan data dan password yang di inputkan tidak sesuai dengan data</td>
	<td>SRS 2.2.3</td>
	<td>STD 1.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Hilmy</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Data Kependudukan</td>
	<td>Menambahkan data kependudukan baru</td>
	<td>SRS 2.2.4</td>
	<td>STD 1.3</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Hilmy</td>
<tr>
	<td>Menambahkan data kependudukan yang sudah ada</td>
	<td>SRS 2.2.4</td>
	<td>STD 1.4</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Hilmy</td>
</tr>
<tr>
	<td>Menambahkan data kependudukan dengan satu field tidak diisi</td>
	<td>SRS 2.2.4</td>
	<td>STD 1.5</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Hilmy</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Melihat Data Kependudukan</td>
	<td>Mengedit data kependudukan baru</td>
	<td>SRS 2.2.5</td>
	<td>STD 1.6</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Hilmy</td>
<tr>
	<td>Mengedit data kependudukan yang sudah ada</td>
	<td>SRS 2.2.5</td>
	<td>STD 1.7</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Hilmy</td>
</tr>
<tr>
	<td>Mengedit data kependudukan dengan satu field tidak diisi</td>
	<td>SRS 2.2.5</td>
	<td>STD 1.8</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Hilmy</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Mengelola User</td>
	<td>Memilih nik baru dan hak akses</td>
	<td>SRS 2.2.7</td>
	<td>STD 1.9</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Jakaria</td>
<tr>
	<td>Memilih nik yang sudah terdapat pada tabel dan hak akses yang sama pada tabel</td>
	<td>SRS 2.2.7</td>
	<td>STD 2.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Jakaria</td>
</tr>
<tr>
	<td>Memilih nik yang sudah terdapat pada tabel dan hak akses yang berbeda dengan tabel</td>
	<td>SRS 2.2.7</td>
	<td>STD 2.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Jakaria</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Login Kepala Desa</td>
	<td>Username dan password yang di inputkan sesuai dengan data</td>
	<td>SRS 2.2.1</td>
	<td>STD 2.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Ismatul</td>
<tr>
	<td>Username dan password yang di inputkan tidak sesuai dengan data</td>
	<td>SRS 2.2.1</td>
	<td>STD 2.3</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Ismatul</td>
</tr>
<tr>
	<td>Username yang di inputkan sesuai dengan data dan password yang di inputkan tidak sesuai dengan data</td>
	<td>SRS 2.2.1</td>
	<td>STD 2.4</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Ismatul</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Generate Laporan</td>
	<td>Memilih menu laporan dan klik button print</td>
	<td>SRS 2.2.6</td>
	<td>STD 2.5</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Jakaria</td>
<tr>
	<td>memilih pilihan default dan klik button print</td>
	<td>SRS 2.2.6</td>
	<td>STD 2.6</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Jakaria</td>
</tr>
<tr>
	<td>memilih pilihan default dan tidak mengklik button print</td>
	<td>SRS 2.2.6</td>
	<td>STD 2.7</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Jakaria</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Melihat Generate Laporan</td>
	<td>Memilih menu laporan dan klik button print</td>
	<td>SRS 2.2.2</td>
	<td>STD 2.8</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Ismatul</td>
<tr>
	<td>memilih pilihan default dan klik button print</td>
	<td>SRS 2.2.2</td>
	<td>STD 2.9</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Ismatul</td>
</tr>
<tr>
	<td>memilih pilihan default dan tidak mengklik button print</td>
	<td>SRS 2.2.2</td>
	<td>STD 3.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Ismatul</td>
</tr>


</thead>  
</table>


BAB IV Deskripsi dan Hasil Uji
----------
**Tabel 2 Deskripsi dan Hasil Uji**

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 1.0</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Petugas IT dengan username dan password yang di inputkan sesuai dengan data</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek apakah login user sudah berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">19/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Hilmy Lazuardi</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Menginputkan username dan password yang sesuai dengan data</li>
					<li>Klik tombol login</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : 8888</li>
					<li>Password : 8888</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Petugas IT berhasil login dengan akun yang benar</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol login dapat diklik jika username dan password sudah terisi</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 1.1</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Petugas IT dengan username dan password yang di inputkan tidak sesuai dengan data</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek apakah login user sudah sesuai</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">19/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Hilmy Lazuardi</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Menginputkan username dan password yang tidak sesuai dengan data</li>
					<li>Klik tombol login</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : 3231</li>
					<li>Password : 3231</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Petugas IT tidak berhasil login dengan akun yang salah</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol login dapat diklik jika username dan password sudah terisi</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 1.2</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Petugas IT dengan username yang sesuai dengan data dan password yang di inputkan tidak sesuai dengan data</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek apakah login user sudah sesuai</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">19/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Hilmy Lazuardi</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Menginputkan username yang sesuai dengan data dan password yang tidak sesuai dengan data</li>
					<li>Klik tombol login</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : 8888</li>
					<li>Password : 3231</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Petugas IT tidak berhasil login dengan username yang benar dan password yang salah</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol login dapat diklik jika username dan password sudah terisi</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 1.3</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Menambahkan data kependudukan baru</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek apakah penambahan data berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Dashboard Petugas IT<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Hilmy Lazuardi</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Mengimputkan data baru contoh agama, pendidikan, dan lain lain</li>
					<li>Klik tombol simpan</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Agama : Islam</li>
					<li>Pendidikan : SD / MI</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Data baru berhasil ditambahkan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol simpan dapat diklik jika data agama, pendidikan  dan lain-lain sudah terisi</li>
					<li> Jika data kosong maka sistem akan menampilkan peringatan "Kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 1.4</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Menambahkan data kependudukan yang sudah ada</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek penambahan data yang sudah ada berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Kependudukan<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Hilmy Lazuardi</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Mengimputkan data yang sudah ada contoh agama, pendidikan, dan lain lain</li>
					<li>Klik tombol simpan</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Agama : Islam</li>
					<li>Pendidikan : SD / MI</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Menambahkan data yang sudah ada maka muncul peringatan gagal</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol simpan dapat diklik jika data agama, pendidikan  dan lain-lain sudah terisi</li>
					<li> Jika data kosong maka sistem akan menampilkan peringatan "Kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 1.5</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Menambahkan data kependudukan dengan satu field tidak diisi</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek penambahan data dengan salah satu field tidak diisi berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Kependudukan<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Hilmy Lazuardi</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Mengimputkan data dengan salah satu filed tidak diisi contoh agama, pendidikan, dan lain lain</li>
					<li>Klik tombol simpan</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Agama : </li>
					<li>Pendidikan : </li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Menambahkan data dengan salah satu filed tidak diisimaka muncul peringatan Kolom tidak boleh kosong dan gagal menyimpan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol simpan dapat diklik jika data agama, pendidikan  dan lain-lain sudah terisi</li>
					<li> Jika data kosong maka sistem akan menampilkan peringatan "Kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 1.6</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Mengedit data kependudukan baru</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek apakah mengedit data sudah berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Kependudukan<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Hilmy Lazuardi</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Mengedit data baru contoh pekerjaan, rt/rw, dan lain lain</li>
					<li>Klik tombol simpan</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Pekerjaan : Programmer</li>
					<li>Rt/Rw : 01/04</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Mengedit data baru berhasil ditambahkan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol edit dapat diklik jika data pekerjaan, rt/rw  dan lain-lain sudah terisi</li>
					<li> Jika data kosong maka sistem akan menampilkan peringatan "Kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 1.7</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Mengedit data kependudukan yang sudah ada</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek apakah mengedit data sudah yang sudah ada berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Kependudukan<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Hilmy Lazuardi</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Mengedit data yang sudah ada contoh pekerjaan, rt/rw, dan lain lain</li>
					<li>Klik tombol simpan</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Pekerjaan : Programmer</li>
					<li>Rt/Rw : 01/04</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Mengedit data yang sudah ada gagal ditambahkan dan sistem menampilkan peringatan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol edit dapat diklik jika data pekerjaan, rt/rw  dan lain-lain sudah terisi</li>
					<li> Jika data kosong maka sistem akan menampilkan peringatan "Kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 1.8</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Mengedit data kependudukan dengan satu field tidak diisi</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek edit data dengan salah satu field tidak diisi berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Kependudukan<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Hilmy Lazuardi</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Mengedit data dengan salah satu filed tidak diisi contoh pekerjaan, rt/rw, dan lain lain</li>
					<li>Klik tombol simpan</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Pekerjaan : </li>
					<li>Rt/Rw : </li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Mengedit data dengan salah satu filed tidak diisimaka muncul peringatan Kolom tidak boleh kosong dan gagal menyimpan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol simpan dapat diklik jika data agama, pendidikan  dan lain-lain sudah terisi</li>
					<li> Jika data kosong maka sistem akan menampilkan peringatan "Kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 1.9</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Memilih NIK baru dan hak akses</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Menambahkan hak akses user</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Dashboard Petugas IT<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jakaria</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Memilih nik dan memilih hak akses</li>
					<li>Klik tombol tambah</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>NIK : 3209121902061095</li>
					<li>Hak akses : Sekertaris Desa</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Hak akses berhasil ditambahkan dengan nik baru</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol tambah dapat diklik jika nik dan hak akses sudah terisi</li>
					<li>Jika nik dan hak akses kosong maka akan muncul peringatan "Kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 2.0</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Memilih nik yang sudah terdapat pada tabel dan hak akses yang sama pada tabel</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Menambahkan hak akses user yang sudah ada</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Menejemen user<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jakaria</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Memilih nik dan memilih hak akses</li>
					<li>Klik tombol tambah</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>NIK : 3209121902061095</li>
					<li>Hak akses : Sekertaris Desa</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Hak akses gagal ditambahkan dengan nik dan hak akses yang sudah ada</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol tambah dapat diklik jika nik dan hak akses sudah terisi</li>
					<li>Jika nik dan hak akses kosong maka akan muncul peringatan "Kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 2.1</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Memilih nik yang sudah terdapat pada tabel dan hak akses yang berbeda dengan tabel</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Menambahkan hak akses user yang sudah ada</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Menejemen User<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jakaria</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Memilih nik dan memilih hak akses</li>
					<li>Klik tombol tambah</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>NIK : 3209121902061095</li>
					<li>Hak akses : Kepala Desa</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Hak akses gagal ditambahkan dengan nik dan hak akses yang sudah ada</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol tambah dapat diklik jika nik dan hak akses sudah terisi</li>
					<li>Jika nik dan hak akses kosong maka akan muncul peringatan "Kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 2.2</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Kepala Desa dengan username dan password yang di inputkan sesuai dengan data</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek apakah login user sudah berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Ismatul Maula</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Menginputkan username dan password yang sesuai dengan data</li>
					<li>Klik tombol login</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : 3209121902061095</li>
					<li>Password : 3209121902061095</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Kepala desa berhasil login dengan akun yang benar</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol login dapat diklik jika username dan password sudah terisi</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 2.3</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Kepala Desa dengan username dan password yang di inputkan tidak sesuai dengan data</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek apakah login user sudah sesuai</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Ismatul Maula</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Menginputkan username dan password yang tidak sesuai dengan data</li>
					<li>Klik tombol login</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : 3209121902061095</li>
					<li>Password : 3209121902061095</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Kepala desa tidak berhasil login dengan akun yang salah</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol login dapat diklik jika username dan password sudah terisi</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 2.4</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Kepala Desa dengan username yang sesuai dengan data dan password yang di inputkan tidak sesuai dengan data</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek apakah login user sudah sesuai</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Login<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Ismatul Maula</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Menginputkan username yang sesuai dengan data dan password yang tidak sesuai dengan data</li>
					<li>Klik tombol login</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Username : 3209121902061095</li>
					<li>Password : 3209120802</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Kepala desa tidak berhasil login dengan username yang benar dan password yang salah</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol login dapat diklik jika username dan password sudah terisi</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 2.5</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Memilih menu laporan dan klik tombol cetak</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek fungsi laporan sudah berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Laporan<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jakaria</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Admin memilih laporan</li>
					<li>Klik tombol cetak</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Laporan agama : Islam</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Sistem menampilkan data agama islam dan admin mencetak laporan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol cetak dapat diklik jika laporan telah dipilih</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 2.6</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Memilih pilihan default dan klik tombol cetak</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek fungsi laporan sudah berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Laporan<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jakaria</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Admin tidak memilih laporan</li>
					<li>Klik tombol cetak</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>--</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Sistem Menampilkan peringatan "Harap pilih laporan"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol cetak dapat diklik jika laporan telah dipilih</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 2.7</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Memilih pilihan default dan tidak mengklik tombol cetak</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek fungsi laporan sudah berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Laporan<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Jakaria</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Admin tidak memilih laporan</li>
					<li>Klik tombol cetak</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>--</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Data tidak muncul</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol cetak dapat diklik jika laporan telah dipilih</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 2.8</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Memilih menu laporan dan klik tombol cetak laporan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek fungsi cetak laporan sudah berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Laporan Kepela Desa<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Ismatul Maula</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Admin memilih laporan</li>
					<li>Klik tombol cetak</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Laporan agama : Islam</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Sistem menampilkan data agama hindu</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol cetak dapat diklik jika laporan telah dipilih</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 2.9</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Memilih pilihan default dan klik tombol cetak laporan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek fungsi cetak laporan sudah berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Laporan<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Ismatul Maula</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Admin tidak memilih laporan</li>
					<li>Klik tombol cetak</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>--</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Sistem Menampilkan peringatan "Harap pilih laporan"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol cetak dapat diklik jika laporan telah dipilih</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD 3.0</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Memilih pilihan default dan tidak mengklik tombol cetak laporan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Mengecek fungsi cetak laporan sudah berhasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Halaman Laporan<br>
			</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20/5/2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Ismatul Maula</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ol>
					<li>Admin tidak memilih laporan</li>
					<li>Klik tombol cetak</li>
				</ol>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>--</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Data tidak muncul</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Tombol cetak dapat diklik jika laporan telah dipilih</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>OK</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li></li>
					<li></li>
				</ul>
			</td>
		</tr>
	</thead>
</table>



