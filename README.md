# rascaloid-docker-compose

## Requirement

- Docker 1.8+
- Docker Compose

## Usage

```
cd prometheus
docker-compose up -d

cd ../fluentd
docker-compose up -d

cd ../rascaloid
docker-compose up -d
```

Access to rascaloid-ri -> http://localhost:3030  
Access to Prometheus -> http://localhost:9090  
Access to Grafana -> http://localhost:3000  
Access to Kibana -> http://localhost:5601  
