FROM nginx:stable

COPY ./default.conf /etc/nginx/conf.d/
COPY ./nginx.conf /etc/nginx/

RUN chown root:root /etc/nginx/conf.d/default.conf
RUN chown root:root /etc/nginx/nginx.conf

EXPOSE 8080
