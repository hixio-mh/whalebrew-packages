FROM python:3.11.0a2-alpine
ADD https://raw.githubusercontent.com/sivel/speedtest-cli/master/speedtest.py /usr/bin/speedtest
RUN chmod 755 /usr/bin/speedtest
ENTRYPOINT ["/usr/bin/speedtest"]
