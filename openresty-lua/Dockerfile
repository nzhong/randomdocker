From openresty/openresty:1.15.8.2-alpine-fat-nosse42

ARG OPENRESTY_NGINX_DIR="/usr/local/openresty/nginx"
COPY nginx.conf  ${OPENRESTY_NGINX_DIR}/conf/
COPY app.lua  ${OPENRESTY_NGINX_DIR}/

EXPOSE 8080