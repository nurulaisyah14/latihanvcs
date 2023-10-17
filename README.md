langkah yang pertama kita mendownload Git, dan membuka website resminya Git(git.scm.com)
kemudian kita unduh Git sesuai dengan arsitektur komputer kita menggunakan 64bit
lalu open git bash lalu start configure
untuk masuk ke folder ketik cd "nama folder yang dibuat dan melakukan konfigurasi user.name dan user.email
dan buat direktory project menggunakan commmand mkdir mkdir latihan vcs cd latihan vcs
jalankan perintah git init untuk membuat repository
disini kita akan mencoba buat satu file bernama README.md (text file) $ echo "#latihan 1">>README.md 
lalu ketik git add README.md untuk menambahkan file yang baru saja dibuat tersebut  
untuk menyimpan perubahan yang ada perubahan yang ada kedalam database repository local, gunakan perintah git commit -m"komentar commit"
buatlah repository server di github apabila belum membuat akun silahkan daftar terlebih dahulu git remote add origin url
untuk mengirim perubahan pada local repository ke server gunakan perintah git push -u origin master
untuk perintah memasukan username dan password pada akun github.com 
yang terakhir jika ingin meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory)
