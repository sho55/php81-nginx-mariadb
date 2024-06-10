FROM alpine:3.6

# nginxのインストール
RUN apk update && \
    apk add --no-cache nginx
RUN mkdir -p /run/nginx
# RUN apk add openssl
# ADD ssl /etc/nginx/ssl

# フォアグラウンドでnginx実行
CMD nginx -g "daemon off;"