FROM porchn/php5.6-apache
RUN docker-php-ext-install pdo pdo_mysql mysqli
RUN apt-get update -y && apt-get install -y libpng-dev
RUN a2enmod rewrite
RUN service apache2 restart