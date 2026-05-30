# Cloud Infrastructure Monitoring & Incident Alerting Platform

## Project Overview

This project demonstrates a production-style monitoring and observability platform deployed on Microsoft Azure.

The platform includes:

- Azure Virtual Machines
- Dockerized Applications
- Nginx Reverse Proxy
- PostgreSQL Database
- Zabbix Monitoring
- Grafana Dashboards
- Alerting via Email/Telegram
- Incident Simulation & Recovery

## Project Principles

- **Clarity:** Clear, well-documented design and intent to make onboarding fast and maintenance easy.
- **Reproducibility:** Environments and deployments are reproducible via code and automation.
- **Infrastructure as Code:** Manage infrastructure declaratively (ARM, Terraform, or templates).
- **Automation:** Automate builds, deployments, testing, and alerting to reduce manual work and mistakes.
- **Observability:** Capture metrics, logs, and traces; provide dashboards and actionable alerts.
- **Security & Least Privilege:** Use secure defaults, minimal permissions, and proper secret management.
- **Scalability & Resilience:** Design for load, failover, and graceful degradation.
- **Testing & Validation:** Include automated tests and incident simulations to validate behaviour.
- **Collaboration & Documentation:** Keep documentation and runbooks up-to-date for team collaboration.
- **Continuous Improvement:** Iterate on monitoring, alerting, and runbooks based on incidents and metrics.

## Architecture

```text
Azure

VM1
├── Zabbix Server
├── Grafana

VM2
├── Docker
├── Nginx
├── Sample Application

VM3
├── PostgreSQL
```

## Arc Diagram

![Arc Diagram](diagram%20arc/arc-diagram.png)

## Project Phases

### Phase 1 – Infrastructure Setup

- Azure Resource Group
- Virtual Network
- Linux Virtual Machines
- Networking & Security Rules

### Phase 2 – Application Deployment

- Docker
- Nginx
- Sample Web Application

### Phase 3 – Monitoring Setup

- Zabbix Server
- Zabbix Agent
- Host Monitoring
- Triggers & Templates

### Phase 4 – Dashboard & Alerting

- Grafana Dashboards
- Email Alerts
- Telegram Notifications

### Phase 5 – Incident Response

- Nginx Failure
- High CPU Usage
- Disk Full Simulation
- Docker Container Failure