FROM nginxinc/nginx-unprivileged:1.16.1-alpine

USER 0

RUN mkdir -p /usr/share/nginx/html/app03
COPY index.html /usr/share/nginx/html/app03/index.html

USER 101

CMD ["nginx", "-g", "daemon off;"]
