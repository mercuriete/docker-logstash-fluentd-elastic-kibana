# docker-logstash-fluentd-elastic-kibana
A docker-compose stack that brings up a fluentd log collector, feeds elasticsearch and then uses kibana to show information.

WARNING: If you are using user namespaces it doesn't work because fluentd needs a volume with root permissions. So if you are using user namespaces you can't access this folder. :(

#Windows user with docker-toolbox

just type:

```
export COMPOSE_CONVERT_WINDOWS_PATHS=1
```

# LICENSE
WTF YOU WANT
