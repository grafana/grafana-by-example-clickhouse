# grafana-by-example-clickhouse
Demonstration of Grafana with the ClickHouse datasource and database

Example deploys a full stack including: Grafana, Clickhouse, Mimir, Loki, Grafana Agent and Syslog-ng using docker-compose.

![Deployment Architecture](https://github.com/grafana/grafana-by-example-clickhouse/blob/main/images/architecture1.png)

## Getting Started

### Clone this repository using
```
git clione https://github.com/grafana/grafana-by-example-clickhouse.git
cd grafana-by-example-clickhouse
```

### Build the docker containers
```
./ctl.sh build all
```

### Start the containers
```
./ctl.sh local up
```

### Navigate to Grafana 
[Navigate to Grafana]([https://github.com/grafana/grafana-by-example-clickhouse/blob/main/images/architecture1.png](http://localhost:3000/))

Login into Grafana using:
- user: admin
- password: welcome1

### Explore the Dashboards in the Clickhouse folder [Clickhouse Dashboard Folder](http://localhost:3000/dashboards/f/-LbHjanVk/clickhouse-demo)
