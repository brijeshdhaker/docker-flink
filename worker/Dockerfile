FROM bde2020/flink-base:1.17.2-hadoop3.3.4

LABEL MAINTAINER="Gezim Sejdiu <g.sejdiu@gmail.com>"

ADD worker.sh /

EXPOSE 8081

CMD ["/bin/bash", "/worker.sh"]
