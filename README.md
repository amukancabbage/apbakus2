<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Install Composer di MacOS

[Sumber](https://www.dumetschool.com/blog/cara-menginstall-composer-di-mac-os-terbaru)
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === 'e0012edf3e80b6978849f5eff0d4b4e4c79ff1609dd1e613307e16318854d24ae64f26d17af3ef0bf7cfb710ca74755a') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"

- sudo mkdir -p /usr/local/bin
- sudo mv composer.phar /usr/local/bin/composer

## Install Homebrew di MacOS

[Sumber](https://brew.sh/), diperlukan untuk install NodeJS
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
## Install Node di MacOS

[Sumber](https://treehouse.github.io/installation-guides/mac/node-mac.html), diperlukan untuk laravel/ui

- brew update
- brew install node

## Langkah-Langkah

- composer create-project --prefer-dist laravel/laravel apbakus2
- php artisan serve
- php artisan migrate
- make:auth laravel 7 [Sumber](https://www.wahyunanangwidodo.com/2020/04/cara-menggunakan-php-artisan-make-auth-di-laravel-7.html)
- composer require laravel/ui
- php artisan ui vue --auth
- npm install
- npm run dev

## Next

- Role user [Sumber](https://www.wahyunanangwidodo.com/2020/04/membuat-role-users-dengan-laravel.html)
- Verifikasi Email [Sumber](https://www.lab-informatika.com/menambahkan-email-verification-laravel)
- Mastering markdown [Sumber](https://guides.github.com/features/mastering-markdown/)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
