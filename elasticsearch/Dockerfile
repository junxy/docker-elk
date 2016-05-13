FROM elasticsearch:latest

#RUN apt-get update && apt-get install -y netcat

# official & charge
# https://www.elastic.co/guide/en/marvel/current/getting-started.html
# https://www.elastic.co/guide/en/marvel/current/installing-marvel.html
RUN /usr/share/elasticsearch/bin/plugin install license
RUN /usr/share/elasticsearch/bin/plugin install marvel-agent
# RUN gosu kibana kibana plugin -i elasticsearch/marvel/latest


#~> https://hub.docker.com/r/openlabs/docker-elasticsearch/~/dockerfile/
# Install the required plugins

# A web front, https://github.com/mobz/elasticsearch-head
#RUN /usr/share/elasticsearch/bin/plugin install mobz/elasticsearch-head


# Monitoring free, https://github.com/royrusso/elasticsearch-HQ
# more: https://qbox.io/blog/tools-for-monitoring-elasticsearch-performance
RUN /usr/share/elasticsearch/bin/plugin install royrusso/elasticsearch-HQ


# query queries, https://github.com/polyfractal/elasticsearch-inquisitor
#RUN /usr/share/elasticsearch/bin/plugin install polyfractal/elasticsearch-inquisitor


# web admin, https://github.com/lmenezes/elasticsearch-kopf
RUN /usr/share/elasticsearch/bin/plugin install lmenezes/elasticsearch-kopf


# official & Security for es
# https://www.elastic.co/downloads/shield
# RUN /usr/share/elasticsearch/bin/plugin install shield


# conf failed ,  https://github.com/floragunncom/search-guard/wiki/Installation
#RUN /usr/share/elasticsearch/bin/plugin install com.floragunn/search-guard-ssl/2.3.1.8.1
#RUN /usr/share/elasticsearch/bin/plugin install com.floragunn/search-guard-2/2.3.1.0-beta1


# http://bigdesk.org/
# RUN /usr/share/elasticsearch/bin/plugin install lukas-vlcek/bigdesk 
RUN /usr/share/elasticsearch/bin/plugin install AIsaac08/bigdesk
