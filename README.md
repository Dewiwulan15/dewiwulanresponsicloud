# dewiwulanresponsicloud
Tutorial
1.	Membuat isi file yang akan di push terlebih dahulu seperti dockerfile, docker-compose dan yang lainnya.
2.	Buat repository baru untuk github, kemudian copy link.
3.	Kemudian beralih pada cmd, dengan menggunakan git bash here pada desktop
4.	Kita clone link yang telah di copy, kemudian pindahkan file yang dibuat tadi kedalam file yang telah di clone lalu, perintah cd dengan nama github untuk mengetahui letak filenya. Setelah itu lanjutkan dengan perintah git init, kemudian git add * untuk menambahkan file kedalam repo github, tambahkan perintah git commit –m dan juga git push –u origin master untuk mengupload file kedalam repo github.
5.	Setelah semua file terpush atau terupload kita beralih pada docker hub.
6.	Pada docker hub kita akan membuat repo baru dan dihubungkan pada github setelah itu pada Build Details kita akan mentrigger  hingga status pada build image berubah menjadi “SUCCESS” maka build image telah selesai.
7.	Lalu buka katacoda, di dalam katacoda kita akan menyinkronkan perintah untuk clone github pada katacoda, kemudian pull image dockerhub ke katacoda setelah itu kita akan masuk pada file direktori yang terdapat pada github dengan menggunakan perintah cd. Ketika telah selesai kita akan menjalankan perintah docker-compose up –d digunakan apabila ada pembaruan code aplikasi setelah selesai klik tanda “+” pada terminal kemudian pilih  “Select port to view on Host 1” dan menyambungkan koneksi pada port 80 untuk menuju web, lalu ulangi pada klik dan masuk pada port 8080 untuk menuju database, untuk membuat web kitaakan melakukan crud pada pengaturan database. Ketika crud telah selesai dijalankan makan akan muncul perubahan pada webnya.
