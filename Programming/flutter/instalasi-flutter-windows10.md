time | author
-|-
2019-Agustus-04 02:05:34 | [Alfiyanm](https://github.com/Alfiyanm)

# Instalasi Flutter pada Windows 10

#### 1. Spesifikasi

sebelum melangkah lebih jauh, saya ingin katakan sesuatu, sebenarnya dalam laman resminya sendiri sudah dijelaskan secara rinci bagaimana instalasi flutter, akan tetapi dalam bahasa inggris. oke.. maka saya akan mencoba menuliskannya dalam bahasa indonesia. agar lebih mudah untuk dipahami.

selanjutnya, sebelum kita memulai download atau instalasi flutter pada komputer atau laptop kita, yang paling penting dan mendasar adalah spesifikasi mesin yang kita gunakan. apakah sudah mencukupi untuk mengembangkan aplikasi dengan flutter? dalam laman resminya dicantumkan spesifikasi seperti dibawah ini:

1. Sistem Operasi: Windows 7 SP1 atau yang terbaru ( dengan prossesor 64-bit).
2. Ruang Disk: 400 MB (belum termasuk ruang untuk menyimpan IDE atau tools).

3. Tools: Flutter sangat membutuhkan alat-alat ini tersedia pada lingkungan pengembangan yang akan kita gunakan. yaitu:
    * [Windows PowerShell versi 5.0](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-windows-powershell?view=powershell-6) atau yang terbaru (biasanya ini sudah tersedia pada Windows 10)
    * [Git untuk Windows versi 2.x](https://git-scm.com/download/win)


#### 2. Download Flutter SDK

langkah selanjutnya adalah mendownload Flutter sdk yang sudah disediakan oleh pengembang dari framework flutter itu sendiri pada halaman [resminya](https://flutter.dev/).

1. Pilih Get started
![Pilih Get started](https://raw.githubusercontent.com/Alfiyanm/mnote/master/flutter/src/common/images/getstarted.png "pilih Get started")

2. kemudian pilih Windows
![Pilih Windows](https://raw.githubusercontent.com/Alfiyanm/mnote/master/flutter/src/common/images/pilih-windows.png "pilih Windows")

3. scroll ke bawah, lalu download flutter sdk yang berektensi .zip
![Download Flutter SDK](https://raw.githubusercontent.com/Alfiyanm/mnote/master/flutter/src/common/images/download-flutter-sdk.png "Download Flutter SDK")

4. setelah itu letakkan didirektori manapun itu terserah Anda, sebagai contoh, saya letakkan di Direktori D:\Development, kemudian ekstrak file zip sehingga terdapat folder bernama flutter.

5. masuk kedalam direktori flutter tersebut, kemudian jalankan flutter_console.bat, maka akan terbuka jendela command prompt disertai munculnya baris deskripsi dan beberapa bantuan pada perintah flutter. Maka sampai disini, sebenarnya flutter sudah dapat dijalankan di powershell.![Pilih User Account](https://raw.githubusercontent.com/Alfiyanm/mnote/master/flutter/src/common/images/flutter.png "pilih User Account")
akan tetapi, agar dapat dijalankan pada direktorim manapun pada powershell, maka ikuti langkah selanjutnya pada setting environment variable. 

#### 3. Setting Environment Variable

agar flutter command dapat dijalankan melalui powershell dalam kondisi apapun. maka harus diupdate pada environment variable. 

1. Masuk ke Control Panel
2. Pilih User Account
![Pilih User Account](https://raw.githubusercontent.com/Alfiyanm/mnote/master/flutter/src/common/images/user-account.png "pilih User Account")
3. Pilih lagi User Account 
![Pilih User Account](https://raw.githubusercontent.com/Alfiyanm/mnote/master/flutter/src/common/images/user-account2.png "pilih lagi User Account")
4. pilih Change my environment variables, lalu akan muncul jendela Environment Variables, dalam kotak User variables arahkan ke Variable Path, kemudian klik Edit
![Pilih Change my environment variables](https://raw.githubusercontent.com/Alfiyanm/mnote/master/flutter/src/common/images/environment-variable.png "pilih User Account")
5. maka akan muncul jendela baru yaitu edit environment variable, klik new, kemudian masukkan alamat direktori \bin yang ada di direktori flutter, sebagai contoh, saya tuliskan D:\Development\flutter\bin.
![Pilih User Account](https://raw.githubusercontent.com/Alfiyanm/mnote/master/flutter/src/common/images/environment-variable2.png "pilih User Account")

6. klik ok, lalu ok. setelah itu jalankan command flutter di powershell. maka akan muncul list perintah flutter.
![Pilih User Account](https://raw.githubusercontent.com/Alfiyanm/mnote/master/flutter/src/common/images/flutter2.png "pilih User Account")jika belum mendapatkan baris perintah tersebut. maka restart windows kemudian jalankan kembali.

7. selanjutnya kita masih membutuhkan sdk android yang terdapat dalam android studio. yang disediakan oleh google untuk membangun aplikasi android. maka kita akan menginstall android studio.

#### 4. Menginstall Android Studio

1. setelah terdownload, klik dua kali android studio untuk mulai menginstall, maka akan muncul jendela 