FROM php:apache
COPY src/* /var/www/html/

# Force php error to stderr
RUN echo 'log_errors = On' >> /usr/local/etc/php/conf.d/php.ini