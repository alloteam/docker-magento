FROM nginx

COPY	./magento.template	/etc/nginx/conf.d/default.conf

RUN mkdir -p /var/www && chown www-data:www-data /var/www

CMD ["nginx", "-g", "daemon off;"]