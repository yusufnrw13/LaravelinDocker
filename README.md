# Laravel in Docker
Pada repository github ini akan membuat tutorial melakukan build web laravel dengan database mysql dan webserver nginx yang akan dijalankan dengan docker.
<h2>Langkah 1 : Building App</h2>
Jadi langkah pertama ini kita akan melakukan build aplikasi laravel kita berserta database mysql dan webserver nginx dengan perintah berikut ini :
<b>docker-compose build app</b>
<img src="https://github.com/yusufnrw13/LaravelinDocker/blob/master/Screenshot_1.png" />
<h2>Langkah 2 : Environment File</h2>
Membuat environment file untuk menjalankan container dengan perintah berikut ini :
<b>docker-compose up -d</b>
<img src="https://github.com/yusufnrw13/LaravelinDocker/blob/master/Screenshot_2.png"/>
<h2>Langkah 3 : Melihat container yang sudah di jalankan pada docker desktop</h2>
<img src="https://github.com/yusufnrw13/LaravelinDocker/blob/master/Screenshot_4.png"/>
Jika ingin melihatnya di cmd gunakan perintah berikut ini untuk melihat container yang sedang berjalan :
<b>docker-compose ps</b>
