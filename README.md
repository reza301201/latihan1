
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
![666](https://user-images.githubusercontent.com/116234001/196832945-9e1104ef-9f0c-4cc8-b586-9c16755a7a51.png)



Membuat Repository Local
Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih Git Bash here . ![8](https://user-images.githubusercontent.com/116234001/196833116-4fc73f15-6f25-4f64-ac6b-8594226010ef.png)


Lalu kita akan menambahkan Config Global Repository pakai user name dan user email yang tadi sudah dibuat, dengan perintah : $ git config --global user.email ???email_user??? $ git config --global user.name ???nama_user???

![9](https://user-images.githubusercontent.com/116234001/196833287-4efd2d6d-afd0-4686-a5eb-4d7f57817550.png)


Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 " LALU " cd lab_pemrograman1![10](https://user-images.githubusercontent.com/116234001/196833388-ce4fa7e1-0a83-419a-a1f5-74014b0f2401.png)


Cara penggunaan git dengan perintah daasar git init fungsi perintahnya untuk membuat repository local
Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.

![11](https://user-images.githubusercontent.com/116234001/196833493-f82c262d-04c2-4676-935e-78094460d8d3.png)


Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo ???#latihan1??? >> README.md. Lalu untuk melihat file ketik perintah ???ls

![12](https://user-images.githubusercontent.com/116234001/196833580-e9c00650-2faf-428d-9c48-c91177609808.png)


Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status.![13](https://user-images.githubusercontent.com/116234001/196833760-3d73bf7f-788c-4213-9407-ee4c13287b03.png)


Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m ???komentar commit" ![14](https://user-images.githubusercontent.com/116234001/196834064-fdc9ebe1-196b-4993-a7f7-5f99cc195c05.png)


File berhasil tersimpan
Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat. Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ ???git remote add origin [url] ??? DAN PERINTAH GIT CLONE ??? git clone [ url ] ???_
Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda ![15](https://user-images.githubusercontent.com/116234001/196834265-b57a769e-29c3-42ee-90e4-e66c6403e8d4.png)

Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository
Untuk mengirim perubahan pada local repository ke server gunakan perintah ???git push -u origin master???. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub. ![16](https://user-images.githubusercontent.com/116234001/196834585-5f1241b7-ac57-4f52-b4a9-ac8370aff50a.png)
git_push
Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/reza301201/latihan1.git . Jika ingin masuk kedirektorti gunakan perintah ???cd [nama direktori anda]???, dan jika ingin melihat semua isi direektori gunakan perintah ???ls -1" git_push![17](https://user-images.githubusercontent.com/116234001/196834705-4250c525-7446-40bc-a5f7-7d634de25d6e.png)


Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya

FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.
Terimakasih
