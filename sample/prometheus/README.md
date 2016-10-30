prometheus
==================================

Docker compose file which starts
[Prometheus](https://prometheus.io/)
and [CAdvisor](https://github.com/google/cadvisor).

Usage
----------------------------------

```
sudo docker-compose up -d
```

Browse [http://localhost:9090](http://localhost:9090)
from the Docker host.
Or use Grafana and set its datasource `http://localhost:9090`.
