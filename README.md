# proposal-envoy-grpc

## Run

```bash
docker-compose up -d
docker-compose logs -f envoy
```

```
go get -u github.com/nokamoto/example-ping-service-client
example-ping-service-client -h localhost -p 10000
```

| url | module |
| --- | --- |
| http://localhost:9901/ | [envoy Administration interface](https://www.envoyproxy.io/docs/envoy/latest/operations/admin.html) |
| http://localhost:9090 | [Prometheus](https://prometheus.io/) |
| http://localhost:3000/d/xqMCATKik/envoy-service-by-fangdd-com | [grafana](https://grafana.com/dashboards/7250) |
