FROM nginx
ADD nginx.site.conf /etc/nginx/conf.d/
RUN mkdir /etc/ssl
ADD ssl/ssl.key /etc/ssl
ADD ssl/ssl.crt /etc/ssl


RUN nginx 
