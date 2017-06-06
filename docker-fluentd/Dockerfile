FROM fluent/fluentd

RUN gem install fluent-plugin-elasticsearch && \
    gem install fluent-plugin-record-reformer
ADD fluent.conf /etc/fluent/
EXPOSE 24284

CMD fluentd -c /fluentd/etc/fluent.conf -p /fluentd/plugins
