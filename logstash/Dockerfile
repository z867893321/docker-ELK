FROM logstash:latest
LABEL MAINTAINER: zmf
ADD logspout.conf /usr/share/logstash/bin/logspout.conf
ENTRYPOINT ["/usr/share/logstash/bin/logstash"]
CMD ["-f","/usr/share/logstash/bin/logspout.conf"]
