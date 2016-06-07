# docker-logstash-fluentd-elastic-kibana
A docker-compose stack that brings up a fluentd log collector, feeds elasticsearch and then uses kibana to show information.

WARNING: If you are using user namespaces it doesn't work because fluentd needs a volume with root permissions. So if you are using user namespaces you can't access this folder. :(

# LICENSE
WTF YOU WANT
