FROM nginx:alpine
RUN mkdir -p /etc/nginx/ssl
COPY conf/nginx.conf /etc/nginx/conf.d/default.conf
COPY ssl/confluence.pem /etc/nginx/ssl/confluence.pem
