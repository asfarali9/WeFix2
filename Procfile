web: vendor/bin/heroku-php-apache2 public/
release: chmod -R 775 storage bootstrap/cache && chmod -R a+w storage bootstrap/cache && php artisan config:cache && php artisan route:cache && php artisan migrate --force
