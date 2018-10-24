cp .env.example .env
composer update
php artisan migrate

npm install cross-env --save-dev

package.json scripts
"clear": "rm -rf build&& mkdir build",
"start": "npm run clear&& NODE_ENV=development webpack-dev-server --host 0.0.0.0 --devtool eval --progress --color --profile",
"deploy": "npm run pre&& npm run clear&& NODE_ENV=production webpack -p --progress",
"dev": "npm run development",

npm install

npm run production


执行:database admin.sql

帐号:admin
密码:admin