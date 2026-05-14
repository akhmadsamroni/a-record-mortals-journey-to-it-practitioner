praktek kali ini adalah mempelaajri dasar dari linux, pada awalnya saya aka membagi kedalam 3 sub latihan:
1. File System Hierarchy
2. Piping & Redirection
3. Permissions & Ownership

diwindows sistem partisi/pemyimpanan diberi label denga hufuf A,B,C,D,E, diikuti dengan titik dua dan backslash (:\). untuk penamaanya ada beberapa jenis:
1. A dan B untuk jenis peyimpanan loppy Disk (disket) nasmun sekararag sudah jarang digunakan
2. C Secara standar adalah partisi tempat sistem operasi Windows diinstal.
3. D, E, F, dst: Digunakan untuk CD-ROM, Flashdisk, atau partisi harddisk tambahan.

pada Window bisa diibaratka denga komplek perumahan yag memiliki banyak rumah terpisah, jika saya punya Hardisk 1 itu adalaha rumah C, jika saya mencolokan Flshdisk itu adalah rumah D, jika di ibaratkan saya tidur di kasur rumah C dan ingin tidur si kasur rumah D maka saya harus keluar dahulu dari rumah C kemudia masuk kerumah D, jika saya ingin memindah kasur(file/daata)dari rumah C saya harus masuk kerumah C terlebih dahulu lalu keluar darei rumah C baru masuk kerumah D, karena rumah C dan rumah D buka satu atap, sebenarnya dalam prakteknya didak serumin yng saya tulis cuma saya buat rumit saja hehe
Di Linux, karena konsepnya adalah Satu Pohon Raksasa (/), memindah file terasa lebih "mengalir" karena Anda sebenarnya hanya berpindah dari satu cabang ke cabang lain dalam gedung yang sama, terutama via terminal
Di Windows, untuk memindah file dari C:\Catatan\tugas.txt ke D:\Backup, perintahnya harus menyebutkan kedua huruf drive tersebut.
Di Linux, semua alamat (path) dimulai dari /. Jika Flashdisk Anda ditempel (mount) di /media/usb, maka file tersebut terlihat seolah-olah berada di dalam harddisk utama Anda.
Pemisah Jalur:
Menggunakan backslash (\)	pada Windows
Menggunakan forward slash (/) pada Linux
