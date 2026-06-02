# Network Monitoring with Prometheus

![Network Infrastructure Overview Dashboard](https://raw.githubusercontent.com/scarolan/grafana-cloud-networking-demo/main/dashboards/networking_screenshot.png)

Reference materials for monitoring network infrastructure (routers, switches, firewalls, load balancers) using Grafana Cloud and Prometheus.

## What's Here

- **[guide.md](guide.md)** — A comprehensive reference guide for network engineers migrating from SolarWinds, ThousandEyes, or PRTG to Grafana Cloud. Covers concept mapping, Alloy configuration, PromQL for network metrics, cost modeling, alerting, and a phased migration checklist.

## Who This Is For

Network admins and infrastructure engineers who know their way around an NMS but are new to Grafana Cloud and the Prometheus ecosystem. The guide assumes you understand SNMP, interface counters, and network monitoring concepts — it focuses on translating what you already know into the new tooling.

## Related Resources

| Resource | Description |
|----------|-------------|
| [Grafana Cloud SNMP Integration](https://grafana.com/docs/grafana-cloud/monitor-infrastructure/integrations/integration-reference/integration-snmp/) | Official integration with pre-built dashboards and alert rules |
| [Grafana Alloy Documentation](https://grafana.com/docs/alloy/latest/) | Alloy collector reference |
| [Prometheus SNMP Exporter](https://github.com/prometheus/snmp_exporter) | Upstream SNMP exporter that Alloy embeds |
