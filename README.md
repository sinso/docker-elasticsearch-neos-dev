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
