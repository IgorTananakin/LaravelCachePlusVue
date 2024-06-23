## Скачивание пакетов laravel + VUE
## composer create-project laravel/laravel . ##
## composer require laravel/breeze --dev ##
## php artisan breeze:install vue ##
## php artisan migrate ##

## Для npm
## npm install ##
## npm run dev ##

## Создание модели контроллеров и request
## php artisan make:model Post -m ##
## php artisan make:controller PostController ##
## php artisan make:request Post/StoreRequest ##
## php artisan migrate ##
## php artisan make:request Post/StoreCacheRequest ##


## Само взаимодействие
- Развернул проект Laravel + Vue установил зависимости
- Создал Layout и в нём форму
- Навестил событие keyup на input
- Отправляю запрос в контроллер и использую фасад Cache  