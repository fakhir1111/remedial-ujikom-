# WEB GALLERY Radhika

## Tentang Website

Simpelnya ini hanyalah Web yang saya buat dengan mengikuti style instagram, facebook dan twitter namun versi low budget yang sangat minim. meskipun tidak terlalu mirip, tapi fungsi yang ditonjolkan dari web ini adalah mampu memuat gallery dan user lain bisa melihat gambar apa yang kita posting.

## Fitur

Untuk Fitur masih minim:
- sign up
- log in
- log out
- multiuser
- add poto
- add album
- edit profile
- add comment
- edit comment
- delete comment
- like
- dll

## ERD, Relasi dan UML Use Case

- ERD

![ERD](https://github.com/fakhir1111/remedial-ujikom-/blob/main/erd.jpeg)

- Relasi

![relasihttps://github.com/fakhir1111/remedial-ujikom-/blob/main/relasi.jpeg)

- UML

![UML](https://github.com/fakhir1111/remedial-ujikom-/blob/main/uml.jpeg)

## Prasyaratan

- PHP 8.2.8 & Web Server (Apache, Lighttpd, atau Nginx)
- Database (MariaDB dengan v11.0.3 atau PostgreSQL)
- Web Browser (Firefox, Safari, Opera, Microsoft Edge dll)

## Instalasi
1. Clone Repository
```
https://github.com/fakhir1111/remedial-ujikom-.git
```

2. Install Composer
```
composer install
```
atau
```
composer update
```

3. Copy .Env
```
copy .env.example .env
```

4. Setting database di .env
```
DB_PORT=3306
DB_DATABASE=laravel_gallery
DB_USERNAME=root
DB_PASSWORD=
```

5. Generate key
```
php artisan key:generate
```

6. Jalankan migrate dan seeder
```
php artisan migrate --seed
```

7. Buat Storage Link
```
php artisan storage:link
```

8. jangan lupa menginstall NPM
```
npm install
```
lalu jalankan
```
npm run dev
```

8. Jalankan Serve
```
php artisan serve
```
