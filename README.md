# docker-logstash-fluentd-elastic-kibana
A docker-compose stack that brings up a fluentd log collector, feeds elasticsearch and then uses kibana to show information.

WARNING: If you are using user namespaces it doesn't work because fluentd needs a volume with root permissions. So if you are using user namespaces you can't access this folder. :(

#Windows user with docker-toolbox

I don't know how to get working the volumes.
fluentd is not working on windows.

# LICENSE
WTF YOU WANT
