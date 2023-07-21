# Prometheus-Simple-Component

- Prometheus, Grafana, Node_exporter, Alertmanager を組み合わせた Docker-compose.
- 手っ取り早く Prometheus や Grafana に触れたい時に使用.


## Usage

### CUI

```
git clone https://github.com/yyoosshh/pro-prometheus.git
cd Prometheus-Simple-Component
docker-compose up -d
```

### GUI（ブラウザ）

#### Case：Prometheus

> http://localhost/prometheus/

#### Case:Grafana

> http://localhost/grafana/

#### Case:node_exporter

> http://localhost:9100/metrics

#### Case:Alertmanager

> http://localhost/alertmanager/


## Structure

![structure](https://github.com/yyoosshh/pro-prometheus/blob/main/Prometheus-Simple-Component/structure.png)

