FROM nginx:1.21-alpine


COPY fabulove.conf /etc/nginx/conf.d
COPY cert/* /etc/nginx/ssl/

CMD ["nginx", "-g", "daemon off;"]