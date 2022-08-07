# Flux CD
Repo to bootstrap a Kubernetes Cluster with all tools needed.
Flux will be responsible of all releases.

To test with Minikube in your local machine follow the next steps:
1. Fork this repo
2. Create a cluster with Minikube.  Example -> minikube start -p flux-test
3. Export as Environment Variable your GitHub Token.

In this repo there are some third party helm charts that are installed.

# GitOps
- Flux v2

## Secrets
- Sealed Secrets

## Message Broker
- RabbitMQ

## Tools
- Selenium Grid
- Cert Manager (pending)
- NGINX Ingress Controller
- Metrics Server

## Monitoring
- Kube Prometheus Stack
- Grafana Loki (loki-distributed and Promtail)
- Grafana Mimir (pending)
- Grafana Tempo (pending)
