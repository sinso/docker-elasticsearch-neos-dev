# docker-elasticsearch-neos-dev

For docker-compose:
```
elasticsearch:
  image: sinso/elasticsearch-neos:latest
  ports:
    - 9200:9200
  volumes:
    - .docker/elasticsearch:/elasticsearch

```

Should be available here:
* http://localhost:9200/_plugin/head/
* http://localhost:9200/_plugin/kopf/
* http://localhost:9200/_plugin/bigdesk/
* http://localhost:9200/_plugin/HQ/
