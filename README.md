# grafana-dashboards

My grafana dashboards, used with data from prometheus and its various
exporters.

## Metric labels

Many of these dashboards expect a label "environment" and "role". I
usually set these with Puppet, reusing the environment and server
roles as metrics and alert labels.

If you do not use these labels, leave them set to "All", or remove
them from the dashboard variables.
