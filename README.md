# product-development
Build an internal use website for CV. Nitah Tirta, aimed at transforming manual record-keeping into a computerized system. The system will cover various financial and inventory operations, including employee payroll, sales, expenses, incoming and outgoing goods, and the generation of balance sheets.

# Tools
1. Microsoft Word
2. Trello
3. Laravel

# Fitur dalam proses Flowchart
1. User Admin :
   a)	Start : proses dimulai 
   b)	Landing page : Ketika admin memasuki halaman utama (landing page) sistem, user dapat memilih untuk melihat profil perusahaan dan jika tidak, admin akan diarahkan ke  
   proses login.
   c)	Login : Admin harus  melakukan login dengan menginput username & password.
   d)	Validasi Data : Sistem akan memvalidasi data login yang dimasukkan oleh admin, jika data tidak valid, maka sistem akan meminta admin untuk mengulangi proses login. 
   Namun, jika data valid admin akan diarahkan ke dashboard utama. Disini, admin dapat memilih untuk melakukan CRUD master data jika diperlukan.
   e)	Menu : Pada menu utama, admin memiliki akses untuk melakukan CRUD terhadap menu-menu yang ada. jika tidak ada menu yang dipilih, admin dapat logout dari sistem. 

3. User Owner :
   a)	Start : Proses dimulai di awal alur sistem.
   b)	Landing Page : Pengguna masuk ke halaman utama sistem. Di sini, pengguna dapat memilih untuk melihat profil perusahaan atau lanjut ke proses login. Jika pengguna 
   memilih untuk melihat profil perusahaan, sistem akan menampilkan profil perusahaan. Jika tidak, pengguna akan diarahkan ke halaman login.
   c)	Login : Pengguna memasukkan username & password untuk mengakses sistem. Jika data login yang dimasukkan tidak valid, sistem akan meminta pengguna untuk mengulangi 
   proses login. Jika data valid, maka sistem akan mengarahkan pengguna ke dashboard utama.
   d)	Dashboard master data : Setelah berhasil login, pengguna diarahkan ke dashboard utama.
   e)	Menu : Pengguna diberikan opsi untuk memilih menu yang diinginkan. Jika pengguna memilih opsi untuk Mengunduh Pelaporan, sistem akan mengunduh laporan yang dibutuhkan. 
   Jika pengguna memilih opsi untuk Menyusun Neraca Saldo, sistem akan menampilkan halaman penyusunan neraca saldo. Jika tidak ada menu yang dipilih, pengguna dapat keluar 
   dari sistem.

5. User Karyawan :
   a)	Start : Proses dimulai.
   b)	Landing Page : Karyawan memasuki halaman utama (landing page) sistem. Karyawan memiliki dua opsi: Jika karyawan memilih untuk melihat profil perusahaan, sistem akan 
   menampilkan informasi profil perusahan. Namun jika tidak, karyawan akan diarahkan ke proses login.
   c)	Login : Karyawan harus melakukan login dengan memasukkan username & password mereka.
   d)	Validasi data : Sistem akan memvalidasi data login yang dimasukkan oleh karyawan. Jika data login tidak valid, sistem akan meminta karyawan untuk memasukkan kembali 
   data login yang benar. Jika data valid, karyawan akan diarahkan ke Menu.
   e)	Menu : Di dalam menu utama, karyawan akan memiliki pilihan untuk melihat atau mengunduh data upah.
   f)	Jika karyawan memilih opsi untuk Melihat dan Mengunduh Upah, sistem akan menampilkan data upah karyawan dan memberi opsi untuk mengunduhnya dengan ekstensi pdf. Jika 
   tidak ada opsi yang dipilih, karyawan dapat memilih untuk keluar dari sistem.
   g)	End : Proses berakhir.

