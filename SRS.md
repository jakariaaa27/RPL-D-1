

**Software Requirements Specification**

**Version 1.0**

22 Februari 2018
![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/POLINDRA.png)

**MONITORING PERKEMBANGAN KEPENDUDUKAN DESA LOHBENER**

kelompok 1 :

 1. Hilmy lazuardi (1603099)
 2. Ismatul maula (1603100)
 3. Jakaria (1603101)

**Jurusan D3 Teknik Informatika**
**Politeknik Negeri Indramayu**
**2018**


1. BAB I Pendahuluan

	1.1 Tujuan

	Dokumen Software Requirement Specification (SRS) merupakan dokumen 	spesifikasi perangkat lunak untuk membangun "Aplikasi Monitoring Desa Lohbener". Dokumen ini dibangun untuk memudahkan penduduk desa Lohbener dalam melihat perkembangan yang ada didesa nya dan memudahkan admin untuk menginput data-data kependudukan yang ada di Lohbener. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "MONITORING PERKEMBANGAN KEPENDUDUKAN DESA LOHBENER".

	1.2	Lingkup

	Monitoiring Perkembangan Kependudukan desa Lohbener merupakan aplikasi yang kami bangun untuk mempermudah penduduk desa Lohbener dalam melihat perkembangan yang ada di desanya khususnya perkembangan Anggaran desa, Kelulusan, piramida, pendidikan, kependudukan, agama, pekerjaan. dan memudahkan admin dalam mnginput data-datanya.

	1.3	 Akronim, singkatan, definisi
	Akronim dan singkatan :
	- SRS : Software Requirement Specification

	Definisi :
	- software Requirement Specification adalah perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna
	- use case adalah situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda. 

	1.4	Referensi
	Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :
	- https://code18.blogspot.co.id/2016/01/definisi-android-studio.html
	- http://hasantarmizi.blogspot.co.id/2017/04/pengertian-sublime-text.html
	- IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software 	Requirements Specifications. IEEE Computer Society, 1998. 1.5	Overview		

	Dokumen SRS ini dibagi menjadi tiga bagian utama, yaitu :
	- bagian pertama berisi penjelasan tentang dokumen SRS yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan oleh perangkat lunak yang dikembangkan, definisi, referensi dan deskripsi umum.
	- Bagian kedua berisi penjelasan secara umum mengenai Aplikasi Random Grup yang akan dibangun, meliputi fungsi dari perangkat lunak, karakteristik pengguna, batasan dan asumsi yang diambil dala pembuatan perangkat lunak.
	- Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih rinci.

2. BAB II Gambaran umum

	2.1	Perspektif produk

	- Antarmuka sistem

	- Antarmuka pengguna

		Antarmuka pengguna yang digunakan untuk mengoperasikan Perangkat Lunak Monitoring Perkembangan Kependudukan Desa Lohbener antara lain :
	   <ol><li> Tampilan awal web </li>
	    <li>Tampilan Input Kependudukan, Pendidikan, Agama, Pekerjaan, Anggaran Desa dan Laporan untuk admin. </li> 
	    <li>Tampilan monitoring pada menu user dan fungsi komentar </li>
	    <li>Tampilan login di website </li> 
	    <li>Tampilan login di Android </li>
	    <li>Tampilan pendaftaran akun user pada android </li></ol>
    
	- Antarmuka perangkat keras

		Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Monitoring Perkembangan Kependudukan Desa Lohbener antara lain :
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
	Skip
- Operasi-operasi
	
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

- Kebutuhan adaptasi
	Skip

	2.2	Spesifikasi Kebutuhan fungsional
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
	Skip

3. BAB III Requirement specification
	
3.1 Persyaratan Antarmuka Eksternal
		Salah satu cara mengakses aplikasi ini yaitu dengan mendaftar, Pendaftaran secara online melalui aplikasi ini dengan mencantumkan NIK kemudian sistem akan mencocokkan NIK masyarakat lohbener. Setelah login berhasil masyarakat dapat memantau perkembangan kependudukan desa lohbener dan dapat mengirimkan kritik dan saran di aplikasi tersebut.
		
3.2 Functional Requirement
		Logika Struktur terdapat pada bagian 3.3.1
		
3.2.1 Login masyarakat
	| . |  |
	|--|--|
	| Nama Fungsi | Login |
	| Xref | Bagian 2.2.1, Login masyarakat |
	| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
	| Precondition | Halaman utama untuk login |
	| Basic Path | 1. Masyarakat mengisi form dengan username dan password 2.Masyarakat mengklik fungsi login |
	| Alternative | Tidak ada |
	| Post Condition | User dapat login dan mengakses aplikasi monitoring |
	| Exception Push | Username dan password salah |
	
3.2.2 masyarakat melihat data dan grafik
	| . |  |
	|--|--|
	| Nama Fungsi | View data dan grafik |
	| Xref | Bagian 2.2.2, View data dan grafik masyaratkat  |
	| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
	| Precondition | Setelah login dengan usernmae dan password |
	| Basic Path | User mengkilik button data dan grafik kependudukan |
	| Alternative | Tidak ada |
	| Post Condition | User melihat data dan grafik |
	| Exception Push | Tidak ada koneksi |
	
3.2.3 masyarakat mengirim kritik dan saran
	| . |  |
	|--|--|
	| Nama Fungsi | Kritik dan Saran |
	| Xref | Bagian 22.3, Kritik dan saran |
	| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
	| Precondition | Membuka halaman data dan grafik kependudukan |
	| Basic Path | User mengklik button kritik dan saran |
	| Alternative | Tidak ada |
	| Post Condition | User Mengisi form kritik dan saran |
	| Exception Push | Tidak ada koneksi |
	
3.2.4 admin login
	| . |  |
	|--|--|
	| Nama Fungsi | Login |
	| Xref | Bagian 2.2.4, Login admin |
	| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
	| Precondition | Halaman utama untuk login |
	| Basic Path | 1. Admin mengisi form dengan username dan password 2. Admin mengklik fungsi login |
	| Alternative | Tidak ada |
	| Post Condition | Admin dapat login dan mengakses aplikasi monitoring |
	| Exception Push | Username dan password salah |
	
3.2.5 Input data dan menampilkan data & grafik
	| . |  |
	|--|--|
	| Nama Fungsi | Input data dan menampilkan data & grafik |
	| Xref | 2.5, Input data dan menampilkan data & grafik |
	| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
	| Precondition | Sesudah login admin |
	| Basic Path | 1. Admin menginputkan data kependudukan 2. Sistem menampilkan data dan grafik |
	| Alternative | Tidak ada |
	| Post Condition | Halaman form input data |
	| Exception Push | Tidak ada koneksi |
	
3.2.6 notifikasi kritik dan saran
	| . |  |
	|--|--|
	| Nama Fungsi | notifikasi kritik saran |
	| Xref | Bagian 2.2.6, notifikasi kritik dan saran |
	| Trigger | Membuka aplikasi Monitoring Perkembangan Kependudukan Desa Lohbener |
	| Precondition | Halaman form input data |
	| Basic Path | 1. Sistem menampilkan notifikasi 2. Admin menyortir kritik dan saran|
	| Alternative | Tidak ada |
	| Post Condition | Halaman kritik dan saran |
	| Exception Push | Tidak ada koneksi |
	
3.2.7 Cetak Laporan
	| . |  |
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
