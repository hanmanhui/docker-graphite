# Grafana Docker Image

## Usage

Needs elastic search

- Elastic search
```
docker pull elasticsearch
docker run -d -p 9200:9200 -p 9300:9300 elasticsearch
```

- Grafana
```
docker pull hanmanhui/grafana
docker run -d -p 8001:8000 hanmanhui/grafana
```
