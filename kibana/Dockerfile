FROM kibana:latest

RUN apt-get update && apt-get install -y netcat
RUN kibana plugin --install elastic/sense
ADD kibana.yml /opt/kibana/config/
CMD kibana
