# Prometheus setup

## Task
Install/configure Prometheus and scrape at least one target beyond self-metrics.

## Starter (not finished)
Compose runs Prometheus, but `prometheus.yml` only scrapes itself. Add a job and document how to open the UI.

## Your work
1. Add a scrape job (node exporter, app metrics, or `localhost` test exporter).
2. `docker compose up` and open http://localhost:9090
3. Confirm targets are **UP** in Status → Targets.
