Latihan1                                                                                                

Tutorial Penggunaan Git

Apa itu Git? 

- Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.
- Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.
- Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja


Menambahkan Global Config

- Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user name dan user email                            
- Konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.                                   
- Apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit                    
- Lakukan "git config --global user.name dan emal " supaya bisa login github ketika push #  
![config](https://user-images.githubusercontent.com/46749350/51788075-b75c4300-212e-11e9-8323-2d41c528e2c2.jpg)

Perintah Dasar Git

- git init, perintah untuk membuat repository local
- git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
- git commit, perintah untuk menyimpan perubahan kedalam database git.
- git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
- git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
- git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)


Membuat Repository Local

- Buka direktory aktif, misal: c:/Latihan
- Buat direktory project praktikum pertama dengan nama Latihan
- Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory)
- Direktory aktif menjadi: c:/Latihan
- Buatlah direktory "Latihan" kemudian masuk ke direktory tersebut

- Lakukan "git init" untuk menjadikan repository lokal

- Buat File Bernama "README.md" (text file), jika file berhasil dibuat, akan tampil seperti dlm gambar

- Kemudian tambahkan file tersebut ke repository dengan " git add README.md, file yang berhasil ditambahkan akan terlihat seperti di gambar, dengan "git status"

- Untuk Menyimpan perubahan sebuah file ke repository local gunakan printah " git commit -m "perubahan yang terjadi"


Membuat Repository Server

- Server reopsitory yang akan kita gunakan adalah http://github.com
- Anda harus membuat akun terlebih dahulu. • Pada laman github, klik tombol start a project, atau
- Dari menu (icon +) klik New Repository


Membuat repository server 

- Isi nama repositorynya, misal: Latihan1.
- lalu klik tombol Create repository

Menambahkan Remote Repository 

- Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
- Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]

Push (Mengirim perubahan ke server) 

- Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
- Perintah ini akan meminta memasukkan username dan password pada akun github.com
- Gunakan printah " git push -u origin master"


Melihat hasilnya pada server repository 

- Buka laman github.com, arahkan pada repositori- nya.
- Maka perubahan akan terlihat pada laman tersebut. #
