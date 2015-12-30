FROM busybox:latest

WORKDIR /app
EXPOSE 18388

COPY ./shadowsocks-server /app/shadowsocks-server
COPY ./config.json /etc/ss.json

CMD /app/shadowsocks-server -c /etc/ss.json