# laravel_auth
Giriş Ekranlı Laravel Sayfası

## Adım 1 - Laravel UI paketinin kurulması
composer require laravel/ui

## Adım 2 - Kimlik Doğrulamasının Oluşturulması
php artisan ui bootstrap --auth

## Adım 3 - Kurulumun tamamlanması
npm i && npm run dev

## Adım 4 - Projenin çalıştırılması
php artisan serve

- Eğer projeyi farklı bir portta çalıştırmak isterseniz php artisan serve --port=8001 gibi port numarasını değiştirerek
çalıştırabilirsiniz.