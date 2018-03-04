<html>
<body>
<div align="center"><h1> Software Requirements Spesification</h1></div>

<p align="center"><b>Version 1.0 </b><br>
<p align="center">22 Februari 2018</b>
<p align="center">
<img src="https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/POLINDRA.png"/>
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
- Akronim dan singkatan :
  - SRS : Software Requirement Specification
- Definisi :
	- software Requirement Specification adalah perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna
	- use case adalah situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda. 

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
**2.1.1 Antarmuka sistem**
**2.1.2 Antarmuka pengguna**
   - **Mockup Admin ( Website )**
    <table>
		<tr align="center">
			<td><b>Welcome</b></td>
			<td><b>Daftar Dosen</b></td>
			<td width="300"><b>Daftar Mahasaiswa</b></td>
		</tr>
		<tr  valign="top" align="center">
				<td><img src="https://4.bp.blogspot.com/-zzgWaZB2bB0/WpJgmjU089I/AAAAAAAAA2U/0KETw2usos0gSGdT0AAbNttPZQAc6cQjACLcBGAs/s1600/1.png" width="180" height="350" /><br><p align="justify">Tampilan Welcome akan muncul ketika device belum terdaftar pada sistem. pada tampilan ini terdapat keterangan bahwa harus mendaftarkan device terlebih dahulu. kemudian ada 2 tombol yakni daftar sebagai dosen atau mahasiswa.</p></td>
				<td><img src="https://2.bp.blogspot.com/-fj4ii9zpBsw/WpJgoZF7XyI/AAAAAAAAA2o/9RdQTPaJv5womKARBrt1OQU4Xj0RjZqdwCLcBGAs/s1600/2.png" width="180" height="350" /><br><p align="justify">Pada tampilan daftar dosen, terdapat 2 inputan yakni masukan NIP dan lalamat MAC device dan 2 tombol yakni tombol daftar dan tombol batal</p></td>
				<td><img src="https://3.bp.blogspot.com/-DmSeKlhuck4/WpJgo8IIQhI/AAAAAAAAA2s/K8PxNOj12yQYs0EOA8KRvHOcMm3W74cbwCLcBGAs/s1600/3.png" width="180" height="350" /><br><p align="justify">Pada daftar mahasiswa sama seperti daftar dosen, hanya saja inputanya berupa NIM</p></td>		
		</tr>
		<tr align="center">
			<td><b>Halaman Mahasiswa </td>
			<td><b>Scan QR Code</td>
			<td><b>Scan Sukses</td>
		</tr>
		<tr valign="top" align="center">
				<td><img src="https://4.bp.blogspot.com/-E6WsXFSeBKY/WpJgpJCujnI/AAAAAAAAA2w/oZaaTQgnRxM2RVHAlpjjXbMA9jy5Qa5XACLcBGAs/s1600/4.png" width="180" height="350" /><br><p align="justify">Pada tampilan halaman mahasiswa terdapat beberapa informasi yang bisa dilihat yakni, absensi, presensi, dan kompensasi. Ada juga 2 tombol yakni tombol jadwal dan tombol scan</p></td>
				<td><img src="https://4.bp.blogspot.com/-p5vpVwLNvXk/WpJgppoj0-I/AAAAAAAAA20/2mWWNUOtSBc-6vQVD31ILMDekuer3EHrQCLcBGAs/s1600/5.png" width="180" height="350" /><br><p align="justify">Pada tampilan scan menggunakan kamera pada device untuk memindai kode QR</p></td>
				<td><img src="https://2.bp.blogspot.com/-S32nItnw8Ag/WpJgqG6bWUI/AAAAAAAAA24/o68LXWmrJE8T5Lg6I6pH-LmrcwSLzFozQCLcBGAs/s1600/6.png" width="180" height="350" /><br><p align="justify">Pada Tampilan sukses akan ada keterangan bahwa sudah berhasil menscan dan ada tombol tutup untuk kembali ke halaman utama</p></td>		
		</tr>
			</tr>
		<tr align="center">
			<td><b>Halaman Dosen</td>
			<td><b>Menu Dosen</td>
			<td><b>Menu Jadwal</td>
		</tr>

    
 **2.1.3 Antarmuka perangkat keras**
Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Monitoring Perkembangan Kependudukan Desa Lohbener antara lain :
	  <ol><li>PC atau Laptop</li>
	  <li>Android</li>
	  <li>Mouse</li>
	  <li>Keyboard</li>
	  <li>Monitor</li>
 **2.1.4 Antarmuka perangkat lunak**
 **2.1.5 Antarmuka komunikasi**
Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak MORSA Lohbener antara lain :
		 <ol><li>Kabel Lan UTP RJ45</li>
		 <li>Modem</li>
		 <li>wifi</li><ol>

**2.1.6 Batasan memori**
Skip
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
	Skip
	
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
	
2.2.1 Masyarakat Login
		Use Case: Login
		Diagram : ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0089.jpg)
		Deskripsi Singkat
		Masyarakat melukan login terlebih dahulu sebelum masuk ke tampilan home, apabila tidak dapat mengakses masyarakat dapat mendaftar akun dahulu.
		Deskripsi langkah-langkah
		1. Masyarakat melakukan login dengan username dan password
		2. Sistem melakukan validasi login
		3. Bila sukses sistem akan mengarahkan ke halaman beranda
		4. Bila gagal sistem akan menampilkan peringatan
		Xref: Bagian 3.2.1, Login masyarakat
	
2.2.2 Masyarakat melihat data dan grafik
		Use Case: View data dan grafik
		Diagram:![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0090.jpg)
		Deskripsi Singkat
		Masyarakat dapat melihat data dan grafik perkembangan kependudukan desa lohbener.
		Deskripsi Langkah-langkah:
		1. Sistem menampilkan halaman beranda yang berisi button ikon.
		2. Masyarakat dapat mengklik tombol button kependudukan, pekerjaan, agama, pendidikan, anggaran, dll.
		3. Sistem menampilkan data dan grafik
		Xref: Bagian 3.2.2, View data dan grafik masyaratkat
	
2.2.3 Masyarakat mengirim kritik dan saran
		Use Case: Kritik dan Saran
		Diagram:		![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0088.jpg)
		Deskripsi Singkat
		Masyarakat dapat memanfaatkan fungsi kritik dan saran untuk menyalurkan aspirasinya
		Deskripsi Langkah-langkah
		1. Masyarakat mengklik tombol kritik dan saran
		2. Sitem akan menampilkan form kritik dan saran
		3. Masyrakat mengisi form tersebut dan klik tombol kirim
		4. Sistem akan mengirimkan ke admin.
		Xref: Bagian 3.2.3, Kritik dan saran

2.2.4 admin login
		Use Case: Login
		Diagram :![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0084.jpg) 
		Deskripsi Singkat
		Admin melakukan login dengan memasukan username password.
		Deskripsi Langkah-langkah
		1. admin melakukan login dengan username dan password
		2. Sistem melakukan validasi login
		3. Bila sukses sistem akan mengarahkan ke halaman beranda
		4. Bila gagal sistem akan menampilkan peringatan
		Xref: Bagian 3.2.4, Login admin
		
2.2.5 Input data dan menampilkan data & grafik
		Use Case: Input data dan menampilkan data & grafik
		Diagram:![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0087.jpg)
		![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0083.jpg)
		Deskripsi Singkat
		Admin melakukan input data kependudukan dan sistem menampilkan data & grafik.
		Deskripsi Langkah-langkah
		1. Admin melakukan input data kependudukan, pekerjaan, agama, pendidikan dan lain-lain
		2. Admin mengklik tombol simpan
		3. Sistem menampilkan data dan grafik
		4. Admin dapat mengedit dan hapus data bila terjadi kesalahan
		Xref: Bagian 3.2.5, Input data dan menampilkan data & grafik

2.2.6 notifikasi kritik dan saran
		Use Case: notifikasi kritik saran
		Diagram:![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/admin-notifikasi.jpg)![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/admin-kritik%20saran.jpg)
		Deskripsi Singkat
		Admin akan mendapat notifikasi di web dan melihat kritik saran
		Deskripsi Langkah-langkah
		1. Sistem akan menampilkan notifikasi
		2. Admin membuka notifikasi
		3. Admin memfilter kritik dan saran untuk di tampilkan ke mobile
		Xref: Bagian 3.2.6, notifikasi kritik dan saran
	
2.2.7 Cetak Laporan
		Use Case: Laporan
		Diagram:![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/IMG-20180303-WA0085.jpg)
		Deskripsi Singkat
		Sistem akan mengirimkan data kependudukan dan yang lainnya ke fungsi laporan
		Deskripsi Langkah-langkah
		1. Sistem menampilkan laporan kependudukan
		2. Admin mencetak laporan 
		3. Laporan diserahkan ke kuwu atau sekdes
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
Skip

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
| Basic Path | 1. Masyarakat mengisi form dengan username dan password 2.Masyarakat mengklik fungsi login |
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
| Basic Path | User mengkilik button data dan grafik kependudukan |
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
| Basic Path | User mengklik button kritik dan saran |
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
| Basic Path | 1. Admin mengisi form dengan username dan password 2. Admin mengklik fungsi login |
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
| Basic Path | 1. Admin menginputkan data kependudukan 2. Sistem menampilkan data dan grafik |
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
| Basic Path | 1. Sistem menampilkan notifikasi 2. Admin menyortir kritik dan saran|
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
| Basic Path | Tampil laporan kependudukan dan cetak laporan |
| Alternative | Tidak ada |
| Post Condition | Halaman Laporan |
| Exception Push | Tidak ada koneksi, data belum diinput |
	
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------