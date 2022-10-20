![8](https://user-images.githubusercontent.com/116234001/196832456-c8418758-1829-4b48-bf33-2c4c7c073ed2.png)
# latihan1
Hallo nama saya reza kurniawan. Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan aialah Applikasi git , akun git. Sebelum itu saya akan kasih tutorial cara penginstalan GIT.

Cara penginstalan GIT
Pertama anda harus mendownload Aplikasi Git, buka website resminya Git di git-scm.com .
![1](https://user-images.githubusercontent.com/116234001/196830846-45b0ada1-9229-498c-94ad-762d8134d8b9.png)
 Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal

Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

![2](https://user-images.githubusercontent.com/116234001/196831035-416d6ec6-52db-4df8-8328-717c4b549494.png)


Setelah melakukan penginstalan, buka git cmd untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah git --version. Saya memakai versi 2.38.0.windows.1

![3](https://user-images.githubusercontent.com/116234001/196831201-75bcc0e5-5849-4259-a2d0-d2ed8d6167db.png)


Cara membuat akun git
Disini anda harus membuat akun git terlebih dahulu untuk membuat repository server bukalah link tersebut http://github.com
![4](https://user-images.githubusercontent.com/116234001/196831384-2013d3f5-4f8f-4b13-9715-171264c4566e.png)


Pada langka selanjutnya anda boleh langsung diskip saja.

Membuat repositori baru
Ini adalah tampilan pertama setelah kalian selesai membuat akun git

![5](https://user-images.githubusercontent.com/116234001/196831579-e6343821-1a7b-4c2f-a4ad-c82eca5ca4f6.png)


Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori.
![6](https://user-images.githubusercontent.com/116234001/196831710-432bab3f-d07a-4f29-b240-46f8f3529d75.png)


Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.
![7](https://user-images.githubusercontent.com/116234001/196831856-5f065589-f77a-4775-8679-0a703e6bb71b.png)


Membuat Repository Local
Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih Git Bash here . 

Lalu kita akan menambahkan Config Global Repository pakai user name dan user email yang tadi sudah dibuat, dengan perintah : $ git config --global user.email “email_user” $ git config --global user.name “nama_user”

Screenshot (21)

Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 " LALU " cd lab_pemrograman1Screenshot (22) ".

Cara penggunaan git dengan perintah daasar git init fungsi perintahnya untuk membuat repository local
Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.

Screenshot (23)

Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls

Screenshot (24)

Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status. Screenshot (26)

Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit" 67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3

File berhasil tersimpan
Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat. Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_
Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda  Screenshot (8-)
Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository
Untuk mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub. git_push
Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/reza301201/latihan1.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1" git_push

Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya

FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.
Terimakasih
