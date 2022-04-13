# Redpanda and Prometheus
docker-compose set up for setting up a redpanda node, grafana, and prometheus with dashboard.


## Setup
```
sudo echo '127.0.0.1 redpanda' >> /etc/hosts
docker-compose up -d
```

Then navigate to `localhost:3001`, default credentials for grafana are admin|admin
