FROM nginx
RUN apt update
RUN apt install nano -y
COPY ./build /usr/share/nginx/html
COPY custom_nginx.conf /etc/nginx/conf.d/default.conf
EXPOSE 80:80
