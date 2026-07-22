FROM nginx:1.24.0-alpine3.17-slim
RUN rm -rf /usr/share/nginx/html/index.html
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf
COPY static /usr/share/nginx/html/