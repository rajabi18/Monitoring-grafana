# The open-source platform for monitoring and observability

## Installation

``` 
git clone https://github.com/rajabi18/Monitoring-grafana.git
docker compose up -d
```
## custom config
if you want add custom host, follow under text.
1. add hosts in prometheus/hosts
2. add hosts in prometheus/prometheus.yml

------
point:
- make sure under ports is open
   - 8080   ( cadvisor )
   - 3030   ( grafana web ui )
   - 3100   ( http - loki )
   - 9096   ( grpc - loki )
   - 514    ( promtail - syslog )
   - 9080   ( promtail - http )

 - check the firewall to access
