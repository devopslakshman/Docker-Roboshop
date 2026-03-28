FROM nginx:1.24.0
RUN rm -rf  /usr/share/index.html
RUN rm -rf /ect/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html/