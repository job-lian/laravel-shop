cp .env.example .env
php composer.phar config -g repo.packagist composer https://packagist.phpcomposer.com
php composer.phar update
php artisan migrate

npm install
npm run production


执行:database admin.sql

帐号:admin
密码:admin


php artisan storage:link