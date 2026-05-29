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