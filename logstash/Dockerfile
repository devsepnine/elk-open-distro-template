ARG ELK_VERSION

FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

RUN logstash-plugin install logstash-filter-alter
RUN logstash-plugin install logstash-filter-geoip
RUN logstash-plugin install logstash-filter-grok
RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-filter-mutate
RUN logstash-plugin install logstash-filter-date
RUN logstash-plugin install logstash-filter-useragent
RUN logstash-plugin install logstash-filter-json_encode
RUN logstash-plugin install logstash-filter-urldecode
RUN logstash-plugin install logstash-filter-uuid