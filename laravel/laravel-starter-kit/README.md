## Proyek Laravel Starter Kit
Proyek ini dibuat untuk dijadikan sebagai `Starter Kit` untuk keperluan develop sistem yang lebih luas

## 1st Setup Config
```.env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=db_perpustakaan
DB_USERNAME=root
DB_PASSWORD=!!&21adi
```

## 2nd Migrate Database
```.sh
php artisan migrate
```

## 3rd Running Project Laravel

```.sh
php artisan serve
```

## Additional, Create file .gitignore
```.gitignore
/.phpunit.cache
/node_modules
/public/build
/public/hot
/public/storage
/storage/*.key
/storage/pail
/vendor
.env
.env.backup
.env.production
.phpactor.json
.phpunit.result.cache
Homestead.json
Homestead.yaml
npm-debug.log
yarn-error.log
/auth.json
/.fleet
/.idea
/.nova
/.vscode
/.zed
```