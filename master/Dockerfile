FROM bde2020/flink-base:1.17.2-hadoop3.3.4

LABEL MAINTAINER="Gezim Sejdiu <g.sejdiu@gmail.com>"

#config files (template)
#ADD /usr/local/flink/conf/flink-conf.yaml /usr/local/flink/conf/

COPY master.sh /
#RUN chmod +x /usr/local/flink/bin/jobmanager.sh
ENV FLINK_MASTER_LOG /usr/local/flink/log

EXPOSE 6123 22 8080

CMD ["/bin/bash", "/master.sh"]
