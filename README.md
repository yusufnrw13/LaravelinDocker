# Laravel in Docker
Pada repository github ini akan membuat tutorial melakukan build web laravel dengan database mysql dan webserver nginx yang akan dijalankan dengan docker.
<h2>Langkah 1 : Membuat file Dockerfile</h2>
Berikut adalah script dari Dockerfile pada web laravel kita
<img src="https://github.com/yusufnrw13/LaravelinDocker/blob/master/Screenshot_8.png"/>
<h2>Langkah 2: Membuat file Docker-compose.yml</h2>
Berikut adalah script dari Docker-compose.yml pada web laravel kita
<img src="https://github.com/yusufnrw13/LaravelinDocker/blob/master/Screenshot_9.png"/>
<h2>Langkah 3 : Building App</h2>
Jadi langkah ketiga ini kita akan melakukan build aplikasi laravel kita berserta database mysql dan webserver nginx dengan perintah berikut ini :
<b>docker-compose build app</b>
<img src="https://github.com/yusufnrw13/LaravelinDocker/blob/master/Screenshot_1.png" />
<h2>Langkah 4 : Environment File</h2>
Membuat environment file untuk menjalankan container dengan perintah berikut ini :
<b>docker-compose up -d</b>
<img src="https://github.com/yusufnrw13/LaravelinDocker/blob/master/Screenshot_2.png"/>
<h2>Langkah 4 : Melihat container yang sudah di jalankan pada docker desktop</h2>
<img src="https://github.com/yusufnrw13/LaravelinDocker/blob/master/Screenshot_4.png"/>
Jika ingin melihatnya di cmd gunakan perintah berikut ini untuk melihat container yang sedang berjalan :
<b>docker-compose ps</b>
<h2>Langkah 5 : Melakukan instal composer</h2>
Kita akan melakukan instalasi composer yang akan digunakan untuk melakukan eksekusi aplikasi laravel dengan composer. Untuk melakukan instalasi ketikkan perintah berikut ini :
<b>docker-compose exec app composer install</b>
<img src="https://github.com/yusufnrw13/LaravelinDocker/blob/master/Screenshot_6.png"/>
<h2>Langkah 6 : Key generate</h2>
Membuat key generate untuk enkripsi. Untuk melakukan key generate gunakan perintah berikut ini :
<b>docker-compose exec app php artisan key:generate</b>
<img src="https://github.com/yusufnrw13/LaravelinDocker/blob/master/Screenshot_7.png"/>
