FROM nginx:alpine
RUN mkdir -p /etc/nginx/ssl && rm -f /etc/nginx/conf.d/default.conf
COPY conf/nginx.conf /etc/nginx/conf.d/default.conf
COPY ssl/confluence.crt /etc/nginx/ssl/confluence.crt
COPY ssl/confluence.key /etc/nginx/ssl/confluence.key
