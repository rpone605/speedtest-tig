FROM python:alpine

RUN apk add --no-cache curl
RUN pip install speedtest-cli influxdb

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
