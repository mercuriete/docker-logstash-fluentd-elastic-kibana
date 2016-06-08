FROM fluent/fluentd

USER fluent
WORKDIR /home/fluent

ENV PATH /home/fluent/.gem/ruby/2.2.0/bin:$PATH
RUN gem install fluent-plugin-elasticsearch
RUN gem install fluent-plugin-record-reformer
ADD fluent.conf /etc/fluent/
EXPOSE 24284
USER root
CMD fluentd -c /fluentd/etc/fluent.conf -p /fluentd/plugins
