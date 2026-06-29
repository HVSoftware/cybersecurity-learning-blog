---
title: 'Cloud Concepts uitgelegd: IaaS, PaaS, SaaS en het shared responsibility model'
date: 2026-05-20
draft: false
categories: ['Azure']
tags: ['az-900', 'cloud-concepts', 'shared-responsibility']
---

Een van de eerste onderwerpen in AZ-900 is het **shared responsibility model**. Dit concept begrijpen is essentieel, want het bepaalt wie waarvoor verantwoordelijk is in de cloud.

## De drie cloudservicetypes

### IaaS (Infrastructure as a Service)
Je huurt infrastructuur: VMs, storage, netwerken. Jij beheert het OS, de applicaties en de data. Microsoft beheert de fysieke hardware.

- *Jij verantwoordelijk:* patchen van het gast-OS, applicaties, data
- *Microsoft:* fysieke datacenter, netwerk, hypervisor

### PaaS (Platform as a Service)
Je focus op applicaties, Microsoft regelt het platform. Denk aan Azure App Services of Azure SQL Database.

- *Jij:* applicatiecode en data
- *Microsoft:* OS, runtime, middleware, infrastructuur

### SaaS (Software as a Service)
Kant-en-klare software zoals Office 365. Jij levert alleen de gebruikers en data.

- *Jij:* data en identiteiten
- *Microsoft:* de rest

## Belangrijke regel
> Informatie en data zijn **altijd** de verantwoordelijkheid van de klant, ongeacht het servicetype.

Dit is een veelvoorkomende examenvraag. De klant is altijd verantwoordelijk voor:
- Data
- Identiteiten en accounts
- Toegangsbeheer

## CapEx vs OpEx
Cloud draait om **OpEx** (operationele uitgaven) in plaats van CapEx (kapitaaluitgaven). Je betaalt per gebruik, geen grote investering vooraf. Dit geeft flexibiliteit en verlaagt de drempel om te schalen.

In de volgende post duik ik dieper in CapEx vs OpEx en het consumption-based model.
