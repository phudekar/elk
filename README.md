Basic implementation of ELK stack
==

This stack includes Elastic search, Logstash and Kibana for application log analysis.

Mount your application log folder to /var/application/logs of host machine in order for it to be collected by Logstash.

## Pre-requisites:
- docker
- docker-compose

## Start the stack:

```
$ docker-compose up
```

Access the kibana dashboard from ```http://{docker-host}:5601/```
