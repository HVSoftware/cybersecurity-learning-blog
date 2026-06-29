---
title: 'Azure Management & Governance: hoe houd je controle?'
date: 2026-06-12
draft: false
categories: ['Azure']
tags: ['az-900', 'governance', 'management', 'cost-management']
---

Het derde leerpad van AZ-900 gaat over beheer en governance. Hoe houd je grip op je cloudomgeving?

## Azure Policy
Azure Policy dwingt regels af voor je resources. Voorbeelden:
- Alleen bepaalde VM-groottes toestaan
- Resources moeten in een specifieke regio staan
- Verplichte tagging van resources

Dit is **eenmalig instellen, altijd actief**.

## Role-Based Access Control (RBAC)
RBAC bepaalt wie wat mag doen. Drie onderdelen:
- **Security Principal** — wie? (gebruiker, groep, app)
- **Role Definition** — wat? (lezer, contributor, owner)
- **Scope** — waar? (subscriptie, resource group, resource)

Principe van least privilege: geef nooit meer rechten dan nodig.

## Cost Management
Kosten beheersen in de cloud:
- **Azure Cost Management + Billing** — inzicht in uitgaven
- **Budgets** — waarschuwingen bij overschrijding
- **Reserved Instances** — korting bij vooraf betalen
- **Azure Pricing Calculator** — kosten schatten voor je bouwt

## Tagging
Tags zijn key-value paren die je aan resources hangt:
- `Kostenplaats: ProjectX`
- `Omgeving: Productie`
- `Eigenaar: TeamAlpha`

Zonder tagging is het lastig om kosten toe te wijzen aan afdelingen of projecten.

## Management Groups
Management groups laten je meerdere subscriptions organiseren. Handig voor bedrijven met veel subscriptions. Beleid dat je op een management group instelt, werkt door naar alle subscriptions eronder.
