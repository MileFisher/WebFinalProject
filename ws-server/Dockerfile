FROM php:8.2-apache 
RUN docker-php-ext-install mysqli pdo pdo_mysql && docker-php-ext-enable mysqli
CMD ["php", "ws-server.php"]