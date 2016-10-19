Untuk Ubuntu

Bagi anda yang menggunakan sistem operasi ubuntu maka anda cukup masuk ke Terminal dan ketikan perintah berikut ini untuk mengupdate pake lokal yang sudah ada di linux dan menginstall git.

sudo apt-get update
sudo apt-get install git

Cara lain, Anda bisa juga menginstall git di linux ubuntu dari source code nya langsung dengan perintah seperti ini

sudo apt-get update
sudo apt-get install build-essential libssl-dev libcurl4-gnutls-dev libexpat1-dev gettext unzip




Untuk Pengguna Mac

Untuk anda yang menggunakan Mac OSX anda bisa mendownload git disini, setelah file .dmg nya anda dapatkan maka setelah tinggal double click dan itu ikuti proses instalasi nya seperti menginstall aplikasi lain di Mac OSX.

Sekarang git sudah terinstal, setelah itu maka anda perlu melakukan pengaturan pada beberapa hal agar pada saat commit pesan yang disampaikan berisi informasi yang benar.

Pastikan git sudah terinstall dengan mengetik perintah

git --version

Anda perlu untuk memberikan nama dan alamat email dengan menggunakan git config karena git menyertakan informasi ini setiap kali anda melakukan commit. Anda bisa masuk ke terminal atau command prompt dan mengetikan perintah berikut ini, sesuaikan dengan nama dan email anda.

git config --global user.name "Your Name"
git config --global user.email "youremail@domain.com"

Setelah itu anda dapat melihat semua item konfigurasi yang telah ditetapkan dengan mengetikan perintah dibawah ini.

git config --list
Maka anda akan melihat informasi yang kira-kira seperti ini, yaitu data informasi nama dan email yang tadi dimasukan

user.name=Your Name
user.email=youremail@domain.com

Informasi ini disimpan dalam file konfigurasi, yang dapat anda temukan atau bisa dilihat dan bahkan di edit dengan teks editor menggunakan perintah seperti ini.

vim ~/.gitconfig
[user]
name = Your Name
email = youremail@domain.com
