FROM nginx:alpine
LABEL Maintainer="AlicFeng <a@samego.com>" \
      Description="vue container based on Alpine"

COPY ./default.conf /etc/nginx/conf.d/default.conf

COPY ./index.html /var/www/app

EXPOSE 80