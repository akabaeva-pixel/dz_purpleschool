FROM nginx:1.30-alpine
RUN apk add --no-cache curl
COPY index.html /usr/share/nginx/html/
COPY default.conf /etc/nginx/conf.d/
EXPOSE 80
