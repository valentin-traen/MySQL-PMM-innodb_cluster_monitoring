# Project Title

Custom dasboard for Innodb Cluster monitoring with PERCONA MONITORING AND MANAGEMENT.

## Getting Started

### Prerequisites

* Your Innodb cluster must use hostname and no ip adress (cluster.addInstance("user@hostname:port"))
* You need the wonderful plugin 'Status Dot' : https://grafana.com/plugins/btplc-status-dot-panel

### Installing

* Copy the yaml to /usr/local/percona/pmm-client/queries-mysqld.yml (default path)
* Get the dashboard from https://grafana.com/dashboards/10006

End with an example of getting some data out of the system or using it for a little demo

## Built With

* [Prometheus](https://prometheus.io/)
* [PMM](https://www.percona.com/software/database-tools/percona-monitoring-and-management)
* [Grafana](https://grafana.com/)
* [YAML](https://yaml.org/)
