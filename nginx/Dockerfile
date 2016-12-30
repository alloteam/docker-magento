FROM nginx

COPY	./default.conf	/etc/nginx/conf.d/default.conf
COPY	./https.conf	/etc/nginx/conf.d/https.conf

RUN mkdir -p /var/www && chown www-data:www-data /var/www

CMD ["nginx", "-g", "daemon off;"]