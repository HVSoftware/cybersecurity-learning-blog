---
title: 'Azure Architecture & Services — Een overzicht van de kerncomponenten'
date: 2026-06-01
draft: false
categories: ['Azure']
tags: ['az-900', 'architecture', 'compute', 'storage', 'networking']
---

Het tweede leerpad van AZ-900 gaat over Azure-architectuur en -services. Dit is het hart van het examen.

## Azure-regio's en beschikbaarheidszones
Azure heeft datacenters over de hele wereld, georganiseerd in **regio's**. Elke regio bevat minimaal twee datacenters.

**Beschikbaarheidszones** zijn fysiek gescheiden locaties binnen een regio. Ze beschermen tegen datacenter-uitval.

## Compute
| Service | Wat het doet |
|---------|-------------|
| Virtual Machines | IaaS - volledige VMs in de cloud |
| App Services | PaaS - webapps en API's hosten |
| Azure Functions | Serverless - code draaien op events |
| AKS | Containers - Kubernetes orchestratie |

## Storage
| Service | Wat het doet |
|---------|-------------|
| Blob Storage | Ongestructureerde data (afbeeldingen, backups) |
| Disk Storage | Schijven voor VMs |
| File Storage | Bestandsshares via SMB |
| Queue Storage | Berichtenwachtrijen |

## Networking
| Service | Wat het doet |
|---------|-------------|
| Virtual Network | Eigen netwerk in Azure |
| Load Balancer | Verkeer verdelen |
| VPN Gateway | Verbinding met on-premises |
| Azure DNS | Domeinnaamresolutie |

## Azure-architectuurcomponenten
- **Resource Groups** — logische containers voor resources
- **Azure Resource Manager** — de managementlaag voor resources
- **Azure Advisor** — aanbevelingen voor best practices
- **Azure Monitor** — bewaking en telemetrie

Deze basis moet je kennen voor het examen. Oefen met de gratis Azure Portal en stel zelf wat resources in om het gevoel te krijgen.
