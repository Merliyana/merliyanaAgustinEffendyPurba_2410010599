# Gunakan base image PHP dengan Apache
FROM php:8.2-apache

# Set working directory
WORKDIR /var/www/html

# Copy semua file dari folder src ke dalam container
COPY src/ /var/www/html/

# Aktifkan modul Apache yang dibutuhkan
RUN a2enmod rewrite

# Set permission
RUN chown -R www-data:www-data /var/www/html \
    && chmod -R 755 /var/www/html

# Expose port 80
EXPOSE 80
