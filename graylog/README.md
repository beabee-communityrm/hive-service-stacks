## Apply custom mapping

Force `message.level` to be a keyword instead of a long

```bash
docker exec -it graylog-opensearch-1 bash
$ curl -X PUT -d@/graylog-custom-mapping.json "http://localhost:9200/_template/graylog-custom-mapping
```
