---
title: Current Status of the latest Kaymes Deployment
layout: page
feature_image: "https://picsum.photos/1300/400?greyscale"
feature_text: |
  ## Kaymes
---

# Current Stage of the Kaymes project

**Design Phase:**
- Build DMSS like kit for NSM
- Physical requirements of the build
- Docker Images
  - Portainer (management of docker containers)
  - Kubernetes (docker container Orchestration)
  - Heimdall (Landing page dashboard for analyst)
  - logstash (enrich and format data coming into Elasticsearch)
  - Elasticsearch (main data store for all incoming data)
  - Kibana (visualize the data inside Elasticsearch)
  - Prometheus (metrics of docker containers)
  - Grafana (visualize the Prometheus inputs onto a dashboard)
  - Suricata (IDS - Snort like)
  - OwnCloud (File Server)
  - The Hive (Ticketing System)
- Move hosting of this page off github onto a private server
- Physical Internal Network
