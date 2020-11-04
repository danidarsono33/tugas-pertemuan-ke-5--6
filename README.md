README.md
02_Latihan-Tugas 5 & 6
BAHASA PEMROGRAMAN

TEHNIK INFORMATIKA

UNIVERSITAS PELITA BANGSA

NAMA : GUNAWAN

NIM : 312010191

KELAS : TI.20.B1

DOSEN : Agung Nugroho,S.Kom.,M.Kom

Tugas : Membuat program Python Latihan1_input Biodata , Lab1 Penggunaan end,separator & String format Dan Lab2 konversi nilai variable

Membuat Program Dengan IDLE Python
Pengertian IDLE Python IDLE adalah singkatan dari Integrated Development and Learning Environment. Dalam pengertian sederhana, IDLE Python tidak lain adalah teks editor bawaan Python. Ketika kita menginstall Python, IDLE sudah langsung terinstall secara otomatis.

Untuk membukanya, silahkan pilih menu Python di start menu, lalu cari IDLE (Python 3.9 64-bit).Sesuaikan Spec PC/Laptop kita.

01_Program Python IDLE

Menjalankan File Python dari IDLE (script mode)

Keunggulan IDLE Python adalah kita bisa membuat sebuah file kode python dan langsung menjalankannya (script mode).

Caranya, buat file teks baru dari menu File -> New File. Sesaat kemudian akan tampil teks editor yang mirip seperti Notepad:

02_New File_Save as_Nama file.py

Lalu simpan file dengan cara pilih menu File -> Save As atau bisa juga dengan menekan tombol CTRL+S. Kita bisa menyimpan file ini sesuai lokasi directory tugas kita contoh E:\labs_pemrograman1\ 02_Latihan-Tugas 5 & 6\ nama file 01_Latihan1.py.

03_Nama file python.py

01_Latihan1_input Biodata
Tugas Latihan :

00_Tugas Latihan1

Kita ketik perintah python :

01_Program Python_Menginput Biodata

Untuk menjalankan kode python, pilih menu Run -> Run Module, atau bisa juga tekan tombol F5

03_Run program

Hasil dari file python ini akan tampil di jendela awal IDLE Python.

Tampilan setelah di Run module :

04_Tampilan Output

Untuk Program mengisi nilai variabel tipe data teks (string) maka harus diapit dengan tanda petik ("..."). Sedangkan untuk angka (integer) tidak perlu diapit dengan tanda petik.Disini saya tambahkan code : int( )

npm=int(input()) dan umur=int(input())

ini bertujuan agar tidak terjadi kesalahan.Karena NPM dan umur harus di tulis dengan angka.Untuk Alamat kadang masih menggunakan teks dan angka,sedangkan No Hp juga masih menggunakan tipe string,karena kadang kita menulis nomor telfon dengan code wilayah/tanda + contoh : +62-08111928091.

02_Menampah code Int inputan

02_Lab1_Penggunaan end,separator & String format
Tugas Lab1 :

00_Tugas Latihan Lab1

Kita buat New file > Simpan sesuai nama file ( Seperti tutorial diatas ), lalu Kita ketik kode perintah python :

01_Program Python_Penggunaan end,separator & string format 02_Program Python_Penggunaan end,separator & string format

Tampilan setelah di Run module :

03_Output

-Untuk mengambil Input menggunakan fungsi input()

input()->untuk mengambil nilai sesuai variablenya.

-Untuk Output program di atas Python menggunakan fungsi print().

Secara default,kita dapat menambahakan spasi di antara variable.Akan tetapi kita juga bisa mengubahnya dengan menambahan code end,separator.

print(*objects, sep=' ', end='\n')

*objek->variable, sep ->separatornya, end ->akhir dari perintah

-Untuk Output Formating menggunakan fungsi str.format()

-Kurung kurawal { } di gunakan sebagai placeholder. -Kita bisa menentukan urutan yang di cetak dengan menggunakan angka (tuple index)

03_Lab2_Konversi Nilai Variable
Tugas Lab2 :

00_Latihan tugas Lab2

Kita buat New file > Simpan sesuai nama file ( Seperti tutorial diatas ), lalu Kita ketik kode perintah python :

01_Program Lab2

Tampilan setelah di Run module :

02_Program Error

Untuk program di atas setelah di run terjadi masalah : TypeError : %d format a number is required, not str.

Karena Nilai a dan b yang kita inputkan bukan angka desimal,maka untuk code %d kita ganti tanda %s.

Catatan : Tanda %s untuk tipe data teks, %d untuk angka (desimal), dan %f untuk bilangan pecahan.

Berikut kode program yang kita sudah rubah :

03_Program Python_Konversi variable string

Tampilan setelah di Run module :

untuk Nilai variabel a =4 dan b=6

04_Output _Run Program Python_Konversi variable

Program yang kita buat setelah di Run Outputnya sudah benar.

Cukup sekian Penjelasan dari saya.

Terimakasih


