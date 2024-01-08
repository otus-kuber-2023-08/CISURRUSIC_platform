# syntax=docker/dockerfile:1

FROM nginxinc/nginx-unprivileged
WORKDIR /app
USER 1001
COPY config.cfg /etc/nginx/conf.d
CMD ["nginx", "-g", "daemon off;"]