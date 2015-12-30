FROM busybox:latest

WORKDIR /app
EXPOSE 18388

COPY ./shadowsocks-server /app/shadowsocks-server

CMD /app/shadowsocks-server -c /etc/ss.json