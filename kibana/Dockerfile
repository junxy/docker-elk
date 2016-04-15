FROM kibana:latest

RUN apt-get update && apt-get install -y netcat

RUN gosu kibana kibana plugin --install elastic/sense

RUN gosu kibana kibana plugin -i kibana/timelion

RUN gosu kibana kibana plugin -i elasticsearch/marvel/latest
