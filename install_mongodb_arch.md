# Tutorial Insatal Mongodb
## step 1 updet
pastikan sistem di arch linux sudah ter update ke versi terbaru dengan comannd keterminal
'sudo pacman -Syu'
## step 2 mngistal yay
setelah terupdate di arch linux, agar mempermudah kita kita bisa menggunakan yay jika kalian belum mengistal yay kalian dapat menginstal dengan comand
'sudo pakman -S yay'
## step 3 menginstal mongodb
setelah itu karena kita sudah mngistall yay maka kita hanya tinggal mengetik comand
'yay -S mongodb-bin'
## step 4 menjalankan mongodb
Untuk memulai MongoDB, gunakan comand berikut:
'sudo systemctl start mongodb'
setelah itu kalian bisa periksa status mongodb dengan
'sudo systemctl status mongodb'
## step  menggumakan mongo db
setelah mongodb berjalan kalian dapat mengguakan dengan comand 'mongosh' dan setiap ingin membeuka mongodb kalian bisa mengunakan comand 'sudo systemctl start mongodb'
selamat mencoba


