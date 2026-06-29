---
title: 'Beschikbaarheid, schaalbaarheid en disaster recovery in Azure'
date: 2026-06-07
draft: false
categories: ['Azure']
tags: ['az-900', 'availability', 'scalability', 'disaster-recovery']
---

Drie belangrijke concepten in de cloud: beschikbaarheid, schaalbaarheid en disaster recovery.

## Beschikbaarheid (Availability)
Houdt high availability een systeem operationeel tijdens geplande en ongeplande uitval?

**Ja.**

High availability zorgt dat een systeem blijft werken door:
- Overbodige componenten
- Automatische failover
- Load balancing over meerdere servers

Azure biedt **SLA's** (Service Level Agreements) per service — van 99.9% tot 99.99% beschikbaarheid.

## Schaalbaarheid (Scalability)
Cloud kan op twee manieren schalen:
- **Verticaal (scaling up)** — grotere VM (meer CPU/RAM)
- **Horizontaal (scaling out)** — meer VMs toevoegen

Azure Autoscale past resources automatisch aan op basis van vraag.

## Disaster Recovery
Azure biedt meerdere herstelopties:
- **Azure Backup** — back-up van VMs, databases, bestanden
- **Azure Site Recovery** — volledige failover naar andere regio
- **Geo-redundantie** — data repliceren naar andere regio

### RPO en RTO
- **RPO (Recovery Point Objective)** — hoeveel dataverloop is acceptabel?
- **RTO (Recovery Time Objective)** — hoe snel moet het systeem hersteld zijn?

Deze termen komen vaak terug in het examen. Onthoud: RPO = dataverlies, RTO = hersteltijd.
