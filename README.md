# laravel 10 

> php8.1 8.2


> 这是Laeavel10 和 dcatadmin2 laravel10分支的实例，安装成功，直接可用

issuse to [dongasai/dcat-admin2](https://github.com/dongasai/dcat-admin2)

composer create-project --prefer-dist laravel/laravel laravel-app "10.*"


composer require dongasai/dcat-admin2:dev-laravel10

php artisan admin:publish
php artisan admin:install

echo "# laravel10_dcatadmin2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:dongasai/laravel10_dcatadmin2.git
git push -u origin main

git clone https://github.com/dongasai/laravel11_dcatadmin2.git

docker exec -it laravel10dcat2 bash
composer require dongasai/dcat-admin2