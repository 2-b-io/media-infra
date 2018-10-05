# media-infra
Dockerize the infrastructure of MediaNetwork for developers

- rabbitmq
- mongo
- elasticsearch

**Note:**  
The `vm.max_map_count` setting should be set permanently in /etc/sysctl.conf:
```
vm.max_map_count=262144
```

Read more: https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-cli-run-prod-mode
