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

setelah itu letakkan didirektori manapun itu terserah Anda, sebagai contoh, saya letakkan di Direktori D:\Development, kemudian ekstrak file zip sehingga terdapat folder bernama flutter.

#### 3. Setting Environment Variable

agar flutter command dapat dijalankan melalui powershell. maka harus diupdate pada environment variable. 

1. Masuk ke Control Panel
2. Pilih User Account
![Pilih User Account](https://raw.githubusercontent.com/Alfiyanm/mnote/master/flutter/src/common/images/user-account.png "pilih User Account")