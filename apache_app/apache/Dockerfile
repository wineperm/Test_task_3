# Используем официальный образ Apache
FROM httpd:2.4

# Включаем необходимые модули
RUN sed -i '/proxy_module/s/^#//g' /usr/local/apache2/conf/httpd.conf && \
    sed -i '/proxy_http_module/s/^#//g' /usr/local/apache2/conf/httpd.conf

# Копируем нашу конфигурацию
COPY my-site.conf /usr/local/apache2/conf/extra/my-site.conf

# Подключаем конфигурацию
RUN echo "Include conf/extra/my-site.conf" >> /usr/local/apache2/conf/httpd.conf