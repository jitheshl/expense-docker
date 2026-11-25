FROM nginx:alpine3.20-perl
RUN rm -rf /usr/share/nginx/html/index.html
COPY code /usr/share/nginx/html/
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf