# Dockerfile for PHP-FPM
FROM php:8.2-fpm

# RUN docker-php-ext-install pdo pdo_mysql

WORKDIR /var/www/html

COPY . .

EXPOSE 9000

# Start PHP-FPM
CMD ["php-fpm"]
