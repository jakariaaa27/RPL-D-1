
<html>
<body>
<div align="center"><h1> Software Requirements Spesification</h1></div>

<p align="center"><b>Version 1.0 </b><br>
<p align="center">22 Februari 2018</b>
<p align="center">
<img src="https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/POLINDRA.png" width="250" height="250"/>
</p>

<br><p align="center"><b>MONITORING PERKEMBANGAN KEPENDUDUKAN DESA LOHBENER</b><br>
<p align="center">Kelompok 1<br>
 Hilmy Lazuardi 				(1603099)<br>
 Ismatul Mauka		(1603100)<br>
 Jakaria			(1603101)<br><br><br>

<p align="center"><b>Jurusan D3 Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b>
<p align="center"><b>2018</b>
</p>
</body>
</html>


----------
**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Specification (SRS) merupakan dokumen 	spesifikasi perangkat lunak untuk membangun "Aplikasi Monitoring Desa Lohbener". Dokumen ini dibangun untuk memudahkan penduduk desa Lohbener dalam melihat perkembangan yang ada didesa nya dan memudahkan admin untuk menginput data-data kependudukan yang ada di Lohbener. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "MONITORING PERKEMBANGAN KEPENDUDUKAN DESA LOHBENER".

1.2	Lingkup
----------
Monitoiring Perkembangan Kependudukan desa Lohbener merupakan aplikasi yang kami bangun untuk mempermudah penduduk desa Lohbener dalam melihat perkembangan yang ada di desanya khususnya perkembangan Anggaran desa, Kelulusan, piramida, pendidikan, kependudukan, agama, pekerjaan. dan memudahkan admin dalam mnginput data-datanya.

1.3	 Akronim, singkatan, definisi
----------

| Istilah | Definisi |
| ------ | ------ |
| SRS |Software Requirement Specification|
| Login | Digunakan untuk mengakses aplikasi |
| software Requirement Specification | perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna |
| USe Case | ituasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

1.4	Referensi
----------
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :
- https://code18.blogspot.co.id/2016/01/definisi-android-studio.html
- http://hasantarmizi.blogspot.co.id/2017/04/pengertian-sublime-text.html
- IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software 	Requirements Specifications. IEEE Computer Society, 1998. 1.5	Overview	

Dokumen SRS ini dibagi menjadi tiga bagian utama, yaitu :
- bagian pertama berisi penjelasan tentang dokumen SRS yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan oleh perangkat lunak yang dikembangkan, definisi, referensi dan deskripsi umum.
- Bagian kedua berisi penjelasan secara umum mengenai Aplikasi Random Grup yang akan dibangun, meliputi fungsi dari perangkat lunak, karakteristik pengguna, batasan dan asumsi yang diambil dala pembuatan perangkat lunak.
- Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih rinci.

1.4	Overview
----------

Bab selanjutnya yaitu menjelaskan sistem yang di terapkan pada aplikasi. Menjelaskan gambaran umum dari aplikasi, Sistem Interface aplikasi dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat ,salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari - hari .dalam studi kasus Proyek II ini kami menganalisis kebutuhan suatu desa di daerah Indramayu tepatnya di desa Lohbener Kecamatan Lohbener .kasus yang kami peroleh banyak himbauan masyarakat ingin mengatahui langsung perkembangan mengenai kependudukan di daerah desa Lohbener ini .maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan masyarakat dan pemerintah desa dengan menerpakan monitoring perkembangan penduduk desa Lohbener .Sehingga memudahkan masyarakat untuk melakukan pemantauan perkembangan kependudukan .sowftware yang kami buat ini berbasis website dan android dimana website sebagai admin dan android untukk user .sistem yang kami buat di dalamnya terdapat angka kelahiran ,angka kematian ,pekerjaan ,agama ,anggaran desa ,laporan ( untuk admin ) ,kritik dan saran ( untuk user ). Berikut akan kami jelaskan  sistem software kami,  admin fungsi utama yaitu :
   - Input Angka Kelahiran
   - Input Angka Kematian
   - Input Agama
   - Input Pekerjaan
   - Input Anggaran Desa
   - Laporan
   
   Berikut ini fungsi user :
   - View Angka Kelahiran
   - View Angka Kematian
   - View Agama
   - View Pekerjaan
   - View Anggaran
   - Kritik dan Saran

2.1	Perspektif produk
----------
Aplikasi Monitoring pekembangan kependudukan desa Lohboner adalah sebuah sistem monitoring yang di aplikasiskan pada android. Terdapat 2 jenis yaitu admin dan pengguna .Pengolahan data di kelola oleh admin pada website dan user hanya memview data pada android

Pada sistem monitoring ini akan menampilkan grafik kependudukan yang sudah di inputkan oleh admin

**2.1.1 Antarmuka sistem**

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Antarmuka%20sistem.png)

Sistem aplikasi Monitoring Perkembangan penduduk desa lohbener memiliki 3 user yaitu masyarakat ,admin dan kepala desa .
masyarakat dan kepala desa mempunyai fungsi yang sama yaitu melakukan view data namun pada kepala desa bissa view laporan dan hal itu tidak ada dalam fungsi masyarakat. Admin bertugas untuk mengelola data ,supaya data bisa di akses oleh masyarakat dan kepala desa

**2.1.2 Antarmuka pengguna**

   - **Mockup Admin ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Halaman%20Login.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Halaman%20Dashboard.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Angka%20Kelahiran.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Angka%20Kematian.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Agama.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Pekerjaan.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Anggaran%20Desa.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Laporan.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Dropdone%20Kependudukan.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Grafik%20Angka%20kelahiran.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Grafik%20Angka%20kematian.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Grafik%20Agama.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Grafik%20Pekerjaan.png) |  |

   - **Mockup User ( Android )**

 
|  |  |
|--|--|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/loading.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/login%20user.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/buat%20akun.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/halaman%20awal.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Halaman%20Pendidikan.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/halaman%20data%20pendidikan.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/halaman%20data%20pendidikan%20copy.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/halaman%20maps.png) |

 
**2.1.3 Antarmuka perangkat keras**

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Monitoring Perkembangan Kependudukan Desa Lohbener antara lain :
1. Smartphone Android

Untuk menggunakan Aplikasi ini smartphone harus minimal memiliki OS Android versi Jelly Beans

3. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .

**2.1.4 Antarmuka perangkat lunak**

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak MORSA Lohbener antara lain :
1.	Kabel Lan UTP RJ45
2.	Modem
3.	wifi

**2.1.6 Batasan memori**



**2.1.7 Operasi-operasi**

| Operasi | Fungsi |
| ------ | ------ |
|Daftar Masyarakat|Digunakan bagi masyarakat untuk mendaftar|
| Login | Digunakan untuk mengakses aplikasi |
| Input Data | Digunakan untuk memasukkan data-data |
| Kembali | Digunakan untuk kembali ke halaman sebelumnya |
| Hapus | Digunakan untuk menghapus data |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |
| Cetak | Digunakan untuk mencetak laporan |
| Kritik dan saran | digunakan bagi masyarakat untuk berkomentar|

**2.1.8 Kebutuhan adaptasi**


	
2.2 Spesifikasi Kebutuhan fungsional
----------
![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/BlankERD.png)

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
	
**2.2.1 Masyarakat Login**

Use Case: Login

Diagram : 

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0089.jpg)

Deskripsi Singkat
Masyarakat melukan login terlebih dahulu sebelum masuk ke tampilan home, apabila tidak dapat mengakses masyarakat dapat mendaftar akun dahulu.
Deskripsi langkah-langkah
1. Masyarakat melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.1, Login masyarakat
	
**2.2.2 Masyarakat melihat data dan grafik**

Use Case: View data dan grafik

Diagram:

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0090.jpg)

Deskripsi Singkat
Masyarakat dapat melihat data dan grafik perkembangan kependudukan desa lohbener.
Deskripsi Langkah-langkah:
1. Sistem menampilkan halaman beranda yang berisi button ikon.
2. Masyarakat dapat mengklik tombol kependudukan terdiri dari pekerjaan, agama, pendidikan, anggaran, dll.
3. Sistem menampilkan data dan grafik

Xref: Bagian 3.2.2, View data dan grafik masyaratkat
	
**2.2.3 Masyarakat mengirim kritik dan saran**

Use Case: Kritik dan Saran

Diagram:	
	![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0088.jpg)

Deskripsi Singkat
Masyarakat dapat memanfaatkan fungsi kritik dan saran untuk menyalurkan aspirasinya
Deskripsi Langkah-langkah
1. Masyarakat mengklik tombol kritik dan saran
2. Sitem akan menampilkan form kritik dan saran
3. Masyrakat mengisi form tersebut dan klik tombol kirim
4. Sistem akan mengirimkan ke admin.

Xref: Bagian 3.2.3, Kritik dan saran

**2.2.4 admin login**

Use Case: Login

Diagram :

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0084.jpg) 

Deskripsi Singkat
Admin melakukan login dengan memasukan username password.
Deskripsi Langkah-langkah
1. admin melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.4, Login admin
		
**2.2.5 Input data dan menampilkan data & grafik**

Use Case: Input data dan menampilkan data & grafik

Diagram:

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0087.jpg)
		![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0083.jpg)
		
Deskripsi Singkat
Admin melakukan input data kependudukan dan sistem menampilkan data & grafik.
Deskripsi Langkah-langkah
1. Admin melakukan input data kependudukan, pekerjaan, agama, pendidikan dan lain-lain
2. Admin mengklik tombol simpan
3. Sistem menampilkan data dan grafik
4. Admin dapat mengedit dan hapus data bila terjadi kesalahan

Xref: Bagian 3.2.5, Input data dan menampilkan data & grafik

**2.2.6 notifikasi kritik dan saran**

Use Case: notifikasi kritik saran

Diagram:

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/admin-notifikasi.jpg)![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/admin-kritik%20saran.jpg)

Deskripsi Singkat
Admin akan mendapat notifikasi di web dan melihat kritik saran
Deskripsi Langkah-langkah
1. Sistem akan menampilkan notifikasi
2. Admin membuka notifikasi
3. Admin memfilter kritik dan saran untuk di tampilkan ke mobile

Xref: Bagian 3.2.6, notifikasi kritik dan saran
	
**2.2.7 Cetak Laporan**

Use Case: Laporan

Diagram:

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0085.jpg)

Deskripsi Singkat
Sistem akan mengirimkan data kependudukan dan yang lainnya ke fungsi laporan
Deskripsi Langkah-langkah
1. Sistem menampilkan laporan kependudukan
2. Admin mencetak laporan 

Xref: Bagian 3.2.7, Cetak Laporan

2.3	Spesifikasi Kebutuhan non-fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

	| No | Deskripsi |
	| ------ | ------ |
	| 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
	| 2 | Perangkat Lunak mampu mengirimkan notifikasi kepada admin maksimal dalam waktu 1 menit |
	| 3 | Perangkat lunak menolak input pengguna yang akan mendaftarkan diri dengan password kurang dari 8 karakter |
	| 4 | Perangkat Lunak dapat dipakai di platofrm Windows ( Admin ) dan Android Os ( User )
 
2.4	Karakteristik pengguna
----------
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5	Batasan-batasan
----------
- Perangkat lunak web hanya dijalankan di windows (7,8,10). Dan perangkat lunak mobile hanya bisa dijalankan di android (min. API 16/Jelly Bean).
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.

2.6	Asumsi-asumsi
----------
Maksimal penginputan data atau memasukkan nama pada aplikasi ini adalah 9999, lebih dari itu program akan muncul peringatan"Anda telah melebihi batas maksimum".

2.7	Kebutuhan Penyeimbang
----------


BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Salah satu cara mengakses aplikasi ini yaitu dengan mendaftar, Pendaftaran secara online melalui aplikasi ini dengan mencantumkan NIK kemudian sistem akan mencocokkan NIK masyarakat lohbener. Setelah login berhasil masyarakat dapat memantau perkembangan kependudukan desa lohbener dan dapat mengirimkan kritik dan saran di aplikasi tersebut.
		
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
		
**3.2.1 Login masyarakat**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login masyarakat |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Halaman utama untuk login |
| Basic Path | 1. Masyarakat mengisi form login dengan username dan password <br> 2.Masyarakat mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | User dapat login dan mengakses aplikasi monitoring |
| Exception Push | Username dan password salah |
	
**3.2.2 masyarakat melihat data dan grafik**

|  |  |
|--|--|
| Nama Fungsi | View data dan grafik |
| Xref | Bagian 2.2.2, View data dan grafik masyaratkat  |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Setelah login dengan usernmae dan password |
| Basic Path | 1. Sistem menampilkan halaman beranda yang berisi button ikon. <br> 2. Masyarakat dapat mengklik tombol kependudukan terdiri dari pekerjaan, agama, pendidikan, anggaran, dll. <br> 3. Sistem menampilkan data dan grafik |
| Alternative | Tidak ada |
| Post Condition | User melihat data dan grafik |
| Exception Push | Tidak ada koneksi |
	
**3.2.3 masyarakat mengirim kritik dan saran**

|  |  |
|--|--|
| Nama Fungsi | Kritik dan Saran |
| Xref | Bagian 22.3, Kritik dan saran |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Membuka halaman data dan grafik kependudukan |
| Basic Path | 1. Masyarakat mengklik tombol kritik dan saran <br> 2. Sitem akan menampilkan form kritik dan saran <br>3. Masyrakat mengisi form tersebut dan klik tombol kirim <br>4. Sistem akan mengirimkan ke admin. |
| Alternative | Tidak ada |
| Post Condition | User Mengisi form kritik dan saran |
| Exception Push | Tidak ada koneksi |
	
**3.2.4 admin login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.4, Login admin |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Halaman utama untuk login |
| Basic Path | 1. admin melakukan login dengan username dan password <br> 2. Sistem melakukan validasi login <br> 3. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 4. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Admin dapat login dan mengakses aplikasi monitoring |
| Exception Push | Username dan password salah |
	
**3.2.5 Input data dan menampilkan data & grafik**

|  |  |
|--|--|
| Nama Fungsi | Input data dan menampilkan data & grafik |
| Xref | 2.5, Input data dan menampilkan data & grafik |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Sesudah login admin |
| Basic Path | 1. Admin melakukan input data kependudukan, pekerjaan, agama, pendidikan dan lain-lain <br> 2. Admin mengklik tombol simpan <br> 3. Sistem menampilkan data dan grafik <br> 4. Admin dapat mengedit dan hapus data bila terjadi kesalahan |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data |
| Exception Push | Tidak ada koneksi |
	
**3.2.6 notifikasi kritik dan saran**

|  |  |
|--|--|
| Nama Fungsi | notifikasi kritik saran |
| Xref | Bagian 2.2.6, notifikasi kritik dan saran |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Halaman form input data |
| Basic Path | 1. Sistem akan menampilkan notifikasi <br> 2. Admin membuka notifikasi <br> 3. Admin memfilter kritik dan saran untuk di tampilkan ke mobile|
| Alternative | Tidak ada |
| Post Condition | Halaman kritik dan saran |
| Exception Push | Tidak ada koneksi |
	
**3.2.7 Cetak Laporan**

|  |  |
|--|--|
| Nama Fungsi | Laporan |
| Xref | Bagian 2.2.7, Cetak Laporan |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | halaman awal aplikasi |
| Basic Path | 1. Admin mengklik tombol laporan <br> 2. Sistem menampilkan laporan kependudukan <br> 3. Admin mencetak laporan  |
| Alternative | Tidak ada |
| Post Condition | Halaman Laporan |
| Exception Push | Tidak ada koneksi, data belum diinput |
	
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem Aplikasi presensi menggunakan kehadiran terdapat struktur Database yang dijelaskan menggunakan ERD.
![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Erd3.jpg)

**Tabel User**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_user| varchar | Nomer auto increment Id_user|
| Username | varchar | berisikan Nik untuk akses login user dan username untuk akses admin |
| Password | varchar | berisikan password untuk login admin dan user |
| level | varchar | untuk membedakan level saat login antara admin dan user

**Tabel Peserta**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_peserta| varchar | Nomer auto increment Id_peserta|
| Id_user| varchar | untuk mengambil username dan password peserta pada tabel user|
| NIK | varchar | nomer kependudukan|
| Nama_lengkap | varchar | nomer kependudukan|
| Tmp_lahir | varchar | tempat lahir peserta |
| Tgl_lahir | date | tanggal lahir peserta |
| Alamat | varchar | alamat lengkap peserta |
| Telp | varchar | nomer telepon peserta |


**Tabel Admin**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_admin| varchar | Nomer auto increment Id_admin|
| Id_user| varchar | untuk mengambil username dan password admin pada tabel user|

**Tabel Kepedudukan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_admin| varchar | untuk mengidentifikasi admin|
| Id_peserta| varchar | untuk mengidentifikasi peserta|
| Id_kelahiran| varchar | untuk mengidentifikasi kelahiran|
| Id_kematian| varchar | untuk mengidentifikasi kematian|
| Id_agama| varchar | untuk mengidentifikasi agama|
| Id_pekerjaan| varchar | untuk mengidentifikasi pekerjaan |
| Id_angdes| varchar | untuk mengidentifikasi anggaran desa|
| Id_laporan| varchar | untuk mengidentifikasi laporan|

**Tabel Kelahiran**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kelahiran| varchar | Nomer auto increment Id_kelahiran|
| nama | varchar | nama anak|
| tgl_lahir| date | tanggal lahir anak |
| jns_kelamin| varchar | jenis kelamin anak|
| jml_kelahiran | integer | total kelahiran

**Tabel Kematian**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kematian| varchar | Nomer auto increment Id_kematian|
| nama | varchar | nama orang meninggal |
| tgl_kematian| date | tanggal lahir anak |
| jns_kelamin| varchar | jenis kelamin orang meninggal|
| jml_kematian | integer |  total kematian |

**Tabel Agama**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_agama| varchar | Nomer auto increment Id_agama|
| nama | varchar | nama masyarakat |
| agama| varchar | agama masyarakat  |


**Tabel Pekerjaan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pekerjaan| varchar | Nomer auto increment Id_pekerjaan|
| nama | varchar | nama masyarakat |
| pekerjaan| varchar | jenis pekerjaan  |

**Tabel Anggaran Desa**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_angdes| varchar | Nomer auto increment Id_angdes|
| nama_anggaran | varchar | nama anggaran desa |
| jml_dana| varchar | Banyaknya anggaran Desa|
| tgl_masuk | date | tanggal masuk anggaran |
| alokasi_dana | varchar | keterangan penggunaan dana |

**Tabel Laporan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_laporan| varchar | Nomer auto increment Id_laporan|
| nama_laporan | varchar | nama laporan |
| jns_laporan| varchar | jenis laporan|
| tgl_laporan | date | tanggal laporan |
| link | varchar | link download laporan |
<html>
<body>
<div align="center"><h1> Software Requirements Spesification</h1></div>

<p align="center"><b>Version 1.0 </b><br>
<p align="center">22 Februari 2018</b>
<p align="center">
<img src="https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/POLINDRA.png" width="250" height="250"/>
</p>

<br><p align="center"><b>MONITORING PERKEMBANGAN KEPENDUDUKAN DESA LOHBENER</b><br>
<p align="center">Kelompok 1<br>
 Hilmy Lazuardi 				(1603099)<br>
 Ismatul Mauka		(1603100)<br>
 Jakaria			(1603101)<br><br><br>

<p align="center"><b>Jurusan D3 Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b>
<p align="center"><b>2018</b>
</p>
</body>
</html>


----------
**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Specification (SRS) merupakan dokumen 	spesifikasi perangkat lunak untuk membangun "Aplikasi Monitoring Desa Lohbener". Dokumen ini dibangun untuk memudahkan penduduk desa Lohbener dalam melihat perkembangan yang ada didesa nya dan memudahkan admin untuk menginput data-data kependudukan yang ada di Lohbener. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "MONITORING PERKEMBANGAN KEPENDUDUKAN DESA LOHBENER".

1.2	Lingkup
----------
Monitoiring Perkembangan Kependudukan desa Lohbener merupakan aplikasi yang kami bangun untuk mempermudah penduduk desa Lohbener dalam melihat perkembangan yang ada di desanya khususnya perkembangan Anggaran desa, Kelulusan, piramida, pendidikan, kependudukan, agama, pekerjaan. dan memudahkan admin dalam mnginput data-datanya.

1.3	 Akronim, singkatan, definisi
----------

| Istilah | Definisi |
| ------ | ------ |
| SRS |Software Requirement Specification|
| Login | Digunakan untuk mengakses aplikasi |
| software Requirement Specification | perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna |
| USe Case | ituasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

1.4	Referensi
----------
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :
- https://code18.blogspot.co.id/2016/01/definisi-android-studio.html
- http://hasantarmizi.blogspot.co.id/2017/04/pengertian-sublime-text.html
- IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software 	Requirements Specifications. IEEE Computer Society, 1998. 1.5	Overview	

Dokumen SRS ini dibagi menjadi tiga bagian utama, yaitu :
- bagian pertama berisi penjelasan tentang dokumen SRS yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan oleh perangkat lunak yang dikembangkan, definisi, referensi dan deskripsi umum.
- Bagian kedua berisi penjelasan secara umum mengenai Aplikasi Random Grup yang akan dibangun, meliputi fungsi dari perangkat lunak, karakteristik pengguna, batasan dan asumsi yang diambil dala pembuatan perangkat lunak.
- Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih rinci.

1.4	Overview
----------

Bab selanjutnya yaitu menjelaskan sistem yang di terapkan pada aplikasi. Menjelaskan gambaran umum dari aplikasi, Sistem Interface aplikasi dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat ,salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari - hari .dalam studi kasus Proyek II ini kami menganalisis kebutuhan suatu desa di daerah Indramayu tepatnya di desa Lohbener Kecamatan Lohbener .kasus yang kami peroleh banyak himbauan masyarakat ingin mengatahui langsung perkembangan mengenai kependudukan di daerah desa Lohbener ini .maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan masyarakat dan pemerintah desa dengan menerpakan monitoring perkembangan penduduk desa Lohbener .Sehingga memudahkan masyarakat untuk melakukan pemantauan perkembangan kependudukan .sowftware yang kami buat ini berbasis website dan android dimana website sebagai admin dan android untukk user .sistem yang kami buat di dalamnya terdapat angka kelahiran ,angka kematian ,pekerjaan ,agama ,anggaran desa ,laporan ( untuk admin ) ,kritik dan saran ( untuk user ). Berikut akan kami jelaskan  sistem software kami,  admin fungsi utama yaitu :
   - Input Angka Kelahiran
   - Input Angka Kematian
   - Input Agama
   - Input Pekerjaan
   - Input Anggaran Desa
   - Laporan
   
   Berikut ini fungsi user :
   - View Angka Kelahiran
   - View Angka Kematian
   - View Agama
   - View Pekerjaan
   - View Anggaran
   - Kritik dan Saran

2.1	Perspektif produk
----------
Aplikasi Monitoring pekembangan kependudukan desa Lohboner adalah sebuah sistem monitoring yang di aplikasiskan pada android. Terdapat 2 jenis yaitu admin dan pengguna .Pengolahan data di kelola oleh admin pada website dan user hanya memview data pada android

Pada sistem monitoring ini akan menampilkan grafik kependudukan yang sudah di inputkan oleh admin

**2.1.1 Antarmuka sistem**

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Antarmuka%20sistem.png)

Sistem aplikasi Monitoring Perkembangan penduduk desa lohbener memiliki 3 user yaitu masyarakat ,admin dan kepala desa .
masyarakat dan kepala desa mempunyai fungsi yang sama yaitu melakukan view data namun pada kepala desa bissa view laporan dan hal itu tidak ada dalam fungsi masyarakat. Admin bertugas untuk mengelola data ,supaya data bisa di akses oleh masyarakat dan kepala desa

**2.1.2 Antarmuka pengguna**

   - **Mockup Admin ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Halaman%20Login.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Halaman%20Dashboard.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Angka%20Kelahiran.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Angka%20Kematian.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Agama.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Pekerjaan.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Anggaran%20Desa.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Input%20Laporan.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Dropdone%20Kependudukan.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Grafik%20Angka%20kelahiran.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Grafik%20Angka%20kematian.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Grafik%20Agama.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Grafik%20Pekerjaan.png) |  |

   - **Mockup User ( Android )**

 
|  |  |
|--|--|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/loading.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/login%20user.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/buat%20akun.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/halaman%20awal.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Halaman%20Pendidikan.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/halaman%20data%20pendidikan.png) |
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/halaman%20data%20pendidikan%20copy.png) | ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/halaman%20maps.png) |

 
**2.1.3 Antarmuka perangkat keras**

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Monitoring Perkembangan Kependudukan Desa Lohbener antara lain :
1. Smartphone Android

Untuk menggunakan Aplikasi ini smartphone harus minimal memiliki OS Android versi Jelly Beans

3. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .
![enter image description here](https://camo.githubusercontent.com/e211b448d2ea1f5765c4077649cdaa731735b53c/68747470733a2f2f332e62702e626c6f6773706f742e636f6d2f2d4f5974546f6d386a6b54772f5770712d39556a413076492f41414141414141414134772f2d55444373567541716e41785247506167526f7134536b7a7634465170766d7067434c63424741732f73313630302f616e7461726d756b612b73697374656d2e706e67)

**2.1.4 Antarmuka perangkat lunak**

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak MORSA Lohbener antara lain :
1.	Kabel Lan UTP RJ45
2.	Modem
3.	wifi

**2.1.6 Batasan memori**



**2.1.7 Operasi-operasi**

| Operasi | Fungsi |
| ------ | ------ |
|Daftar Masyarakat|Digunakan bagi masyarakat untuk mendaftar|
| Login | Digunakan untuk mengakses aplikasi |
| Input Data | Digunakan untuk memasukkan data-data |
| Kembali | Digunakan untuk kembali ke halaman sebelumnya |
| Hapus | Digunakan untuk menghapus data |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |
| Cetak | Digunakan untuk mencetak laporan |
| Kritik dan saran | digunakan bagi masyarakat untuk berkomentar|

**2.1.8 Kebutuhan adaptasi**


	
2.2 Spesifikasi Kebutuhan fungsional
----------
![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/$R4LLASQ.jpeg)

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
	
**2.2.1 Masyarakat Login**

Use Case: Login

Diagram : 

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0089.jpg)

Deskripsi Singkat
Masyarakat melukan login terlebih dahulu sebelum masuk ke tampilan home, apabila tidak dapat mengakses masyarakat dapat mendaftar akun dahulu.
Deskripsi langkah-langkah
1. Masyarakat melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.1, Login masyarakat
	
**2.2.2 Masyarakat melihat data dan grafik**

Use Case: View data dan grafik

Diagram:

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0090.jpg)

Deskripsi Singkat
Masyarakat dapat melihat data dan grafik perkembangan kependudukan desa lohbener.
Deskripsi Langkah-langkah:
1. Sistem menampilkan halaman beranda yang berisi button ikon.
2. Masyarakat dapat mengklik tombol kependudukan terdiri dari pekerjaan, agama, pendidikan, anggaran, dll.
3. Sistem menampilkan data dan grafik

Xref: Bagian 3.2.2, View data dan grafik masyaratkat
	
**2.2.3 Masyarakat mengirim kritik dan saran**

Use Case: Kritik dan Saran

Diagram:	
	![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0088.jpg)

Deskripsi Singkat
Masyarakat dapat memanfaatkan fungsi kritik dan saran untuk menyalurkan aspirasinya
Deskripsi Langkah-langkah
1. Masyarakat mengklik tombol kritik dan saran
2. Sitem akan menampilkan form kritik dan saran
3. Masyrakat mengisi form tersebut dan klik tombol kirim
4. Sistem akan mengirimkan ke admin.

Xref: Bagian 3.2.3, Kritik dan saran

**2.2.4 admin login**

Use Case: Login

Diagram :

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0084.jpg) 

Deskripsi Singkat
Admin melakukan login dengan memasukan username password.
Deskripsi Langkah-langkah
1. admin melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.4, Login admin
		
**2.2.5 Input data dan menampilkan data & grafik**

Use Case: Input data dan menampilkan data & grafik

Diagram:

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0087.jpg)
		![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0083.jpg)
		
Deskripsi Singkat
Admin melakukan input data kependudukan dan sistem menampilkan data & grafik.
Deskripsi Langkah-langkah
1. Admin melakukan input data kependudukan, pekerjaan, agama, pendidikan dan lain-lain
2. Admin mengklik tombol simpan
3. Sistem menampilkan data dan grafik
4. Admin dapat mengedit dan hapus data bila terjadi kesalahan

Xref: Bagian 3.2.5, Input data dan menampilkan data & grafik

**2.2.6 notifikasi kritik dan saran**

Use Case: notifikasi kritik saran

Diagram:

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/admin-notifikasi.jpg)![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/admin-kritik%20saran.jpg)

Deskripsi Singkat
Admin akan mendapat notifikasi di web dan melihat kritik saran
Deskripsi Langkah-langkah
1. Sistem akan menampilkan notifikasi
2. Admin membuka notifikasi
3. Admin memfilter kritik dan saran untuk di tampilkan ke mobile

Xref: Bagian 3.2.6, notifikasi kritik dan saran
	
**2.2.7 Cetak Laporan**

Use Case: Laporan

Diagram:

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0085.jpg)

Deskripsi Singkat
Sistem akan mengirimkan data kependudukan dan yang lainnya ke fungsi laporan
Deskripsi Langkah-langkah
1. Sistem menampilkan laporan kependudukan
2. Admin mencetak laporan 

Xref: Bagian 3.2.7, Cetak Laporan

2.3	Spesifikasi Kebutuhan non-fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

	| No | Deskripsi |
	| ------ | ------ |
	| 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
	| 2 | Perangkat Lunak mampu mengirimkan notifikasi kepada admin maksimal dalam waktu 1 menit |
	| 3 | Perangkat lunak menolak input pengguna yang akan mendaftarkan diri dengan password kurang dari 8 karakter |
	| 4 | Perangkat Lunak dapat dipakai di platofrm Windows ( Admin ) dan Android Os ( User )
 
2.4	Karakteristik pengguna
----------
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5	Batasan-batasan
----------
- Perangkat lunak web hanya dijalankan di windows (7,8,10). Dan perangkat lunak mobile hanya bisa dijalankan di android (min. API 16/Jelly Bean).
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.

2.6	Asumsi-asumsi
----------
Maksimal penginputan data atau memasukkan nama pada aplikasi ini adalah 9999, lebih dari itu program akan muncul peringatan"Anda telah melebihi batas maksimum".

2.7	Kebutuhan Penyeimbang
----------


BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Salah satu cara mengakses aplikasi ini yaitu dengan mendaftar, Pendaftaran secara online melalui aplikasi ini dengan mencantumkan NIK kemudian sistem akan mencocokkan NIK masyarakat lohbener. Setelah login berhasil masyarakat dapat memantau perkembangan kependudukan desa lohbener dan dapat mengirimkan kritik dan saran di aplikasi tersebut.
		
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
		
**3.2.1 Login masyarakat**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login masyarakat |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Halaman utama untuk login |
| Basic Path | 1. Masyarakat mengisi form login dengan username dan password <br> 2.Masyarakat mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | User dapat login dan mengakses aplikasi monitoring |
| Exception Push | Username dan password salah |
	
**3.2.2 masyarakat melihat data dan grafik**

|  |  |
|--|--|
| Nama Fungsi | View data dan grafik |
| Xref | Bagian 2.2.2, View data dan grafik masyaratkat  |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Setelah login dengan usernmae dan password |
| Basic Path | 1. Sistem menampilkan halaman beranda yang berisi button ikon. <br> 2. Masyarakat dapat mengklik tombol kependudukan terdiri dari pekerjaan, agama, pendidikan, anggaran, dll. <br> 3. Sistem menampilkan data dan grafik |
| Alternative | Tidak ada |
| Post Condition | User melihat data dan grafik |
| Exception Push | Tidak ada koneksi |
	
**3.2.3 masyarakat mengirim kritik dan saran**

|  |  |
|--|--|
| Nama Fungsi | Kritik dan Saran |
| Xref | Bagian 22.3, Kritik dan saran |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Membuka halaman data dan grafik kependudukan |
| Basic Path | 1. Masyarakat mengklik tombol kritik dan saran <br> 2. Sitem akan menampilkan form kritik dan saran <br>3. Masyrakat mengisi form tersebut dan klik tombol kirim <br>4. Sistem akan mengirimkan ke admin. |
| Alternative | Tidak ada |
| Post Condition | User Mengisi form kritik dan saran |
| Exception Push | Tidak ada koneksi |
	
**3.2.4 admin login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.4, Login admin |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Halaman utama untuk login |
| Basic Path | 1. admin melakukan login dengan username dan password <br> 2. Sistem melakukan validasi login <br> 3. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 4. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Admin dapat login dan mengakses aplikasi monitoring |
| Exception Push | Username dan password salah |
	
**3.2.5 Input data dan menampilkan data & grafik**

|  |  |
|--|--|
| Nama Fungsi | Input data dan menampilkan data & grafik |
| Xref | 2.5, Input data dan menampilkan data & grafik |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Sesudah login admin |
| Basic Path | 1. Admin melakukan input data kependudukan, pekerjaan, agama, pendidikan dan lain-lain <br> 2. Admin mengklik tombol simpan <br> 3. Sistem menampilkan data dan grafik <br> 4. Admin dapat mengedit dan hapus data bila terjadi kesalahan |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data |
| Exception Push | Tidak ada koneksi |
	
**3.2.6 notifikasi kritik dan saran**

|  |  |
|--|--|
| Nama Fungsi | notifikasi kritik saran |
| Xref | Bagian 2.2.6, notifikasi kritik dan saran |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | Halaman form input data |
| Basic Path | 1. Sistem akan menampilkan notifikasi <br> 2. Admin membuka notifikasi <br> 3. Admin memfilter kritik dan saran untuk di tampilkan ke mobile|
| Alternative | Tidak ada |
| Post Condition | Halaman kritik dan saran |
| Exception Push | Tidak ada koneksi |
	
**3.2.7 Cetak Laporan**

|  |  |
|--|--|
| Nama Fungsi | Laporan |
| Xref | Bagian 2.2.7, Cetak Laporan |
| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
| Precondition | halaman awal aplikasi |
| Basic Path | 1. Admin mengklik tombol laporan <br> 2. Sistem menampilkan laporan kependudukan <br> 3. Admin mencetak laporan  |
| Alternative | Tidak ada |
| Post Condition | Halaman Laporan |
| Exception Push | Tidak ada koneksi, data belum diinput |
	
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem Aplikasi presensi menggunakan kehadiran terdapat struktur Database yang dijelaskan menggunakan ERD.
![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/Erd3.jpg)

**Tabel User**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_user| varchar | Nomer auto increment Id_user|
| Username | varchar | berisikan Nik untuk akses login user dan username untuk akses admin |
| Password | varchar | berisikan password untuk login admin dan user |
| level | varchar | untuk membedakan level saat login antara admin dan user

**Tabel Peserta**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_peserta| varchar | Nomer auto increment Id_peserta|
| Id_user| varchar | untuk mengambil username dan password peserta pada tabel user|
| NIK | varchar | nomer kependudukan|
| Nama_lengkap | varchar | nomer kependudukan|
| Tmp_lahir | varchar | tempat lahir peserta |
| Tgl_lahir | date | tanggal lahir peserta |
| Alamat | varchar | alamat lengkap peserta |
| Telp | varchar | nomer telepon peserta |


**Tabel Admin**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_admin| varchar | Nomer auto increment Id_admin|
| Id_user| varchar | untuk mengambil username dan password admin pada tabel user|

**Tabel Kepedudukan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_admin| varchar | untuk mengidentifikasi admin|
| Id_peserta| varchar | untuk mengidentifikasi peserta|
| Id_kelahiran| varchar | untuk mengidentifikasi kelahiran|
| Id_kematian| varchar | untuk mengidentifikasi kematian|
| Id_agama| varchar | untuk mengidentifikasi agama|
| Id_pekerjaan| varchar | untuk mengidentifikasi pekerjaan |
| Id_angdes| varchar | untuk mengidentifikasi anggaran desa|
| Id_laporan| varchar | untuk mengidentifikasi laporan|

**Tabel Kelahiran**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kelahiran| varchar | Nomer auto increment Id_kelahiran|
| nama | varchar | nama anak|
| tgl_lahir| date | tanggal lahir anak |
| jns_kelamin| varchar | jenis kelamin anak|
| jml_kelahiran | integer | total kelahiran

**Tabel Kematian**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kematian| varchar | Nomer auto increment Id_kematian|
| nama | varchar | nama orang meninggal |
| tgl_kematian| date | tanggal lahir anak |
| jns_kelamin| varchar | jenis kelamin orang meninggal|
| jml_kematian | integer |  total kematian |

**Tabel Agama**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_agama| varchar | Nomer auto increment Id_agama|
| nama | varchar | nama masyarakat |
| agama| varchar | agama masyarakat  |


**Tabel Pekerjaan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pekerjaan| varchar | Nomer auto increment Id_pekerjaan|
| nama | varchar | nama masyarakat |
| pekerjaan| varchar | jenis pekerjaan  |

**Tabel Anggaran Desa**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_angdes| varchar | Nomer auto increment Id_angdes|
| nama_anggaran | varchar | nama anggaran desa |
| jml_dana| varchar | Banyaknya anggaran Desa|
| tgl_masuk | date | tanggal masuk anggaran |
| alokasi_dana | varchar | keterangan penggunaan dana |

**Tabel Laporan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_laporan| varchar | Nomer auto increment Id_laporan|
| nama_laporan | varchar | nama laporan |
| jns_laporan| varchar | jenis laporan|
| tgl_laporan | date | tanggal laporan |
| link | varchar | link download laporan |


