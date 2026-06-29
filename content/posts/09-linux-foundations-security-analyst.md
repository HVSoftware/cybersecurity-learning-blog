---
title: 'Linux Foundations voor een Security Analyst'
date: 2026-06-24
draft: false
categories: ['CyberSecurity']
tags: ['linux', 'foundations', 'htb', 'command-line']
---

Linux is onmisbaar voor een security analyst. Hack The Box heeft een goede Linux Foundations module die ik heb doorlopen. Hier zijn de belangrijkste onderwerpen.

## Waarom Linux voor security?
- De meeste servers draaien Linux
- Pentesting tools zijn Linux-native (Kali, Parrot)
- Logbestanden, netwerktools, scripting
- Alles is te automatiseren met de CLI

## Text Processing (de basis)
Command-line text processing is essentieel. Dit heb ik geoefend:
- `cat` — bestanden uitlezen
- `sort` — sorteren op alfabet of numeriek
- `uniq` — dubbele regels verwijderen
- `grep` — zoeken in bestanden
- `cut` — kolommen selecteren
- `wc` — tellen (lines, words, characters)

## Hands-on oefening
Ik gebruikte oefenbestanden zoals `names.txt`, `persons.txt`, en `studenten.txt` om commando's te oefenen:

```bash
# Alle unieke namen vinden
cat names.txt | sort | uniq

# Personen ouder dan 30 vinden
grep "30\|31\|32\|33\|34\|35" persons.txt

# Aantal regels tellen
wc -l studenten.txt
```

## Volgende Linux onderwerpen
- File permissions (chmod, chown, chgrp)
- Processes (ps, top, kill)
- Networking (netstat, ss, curl)
- Shell scripting (bash voor automatisatie)
- Log analyse (journalctl, /var/log/)

Linux Foundations is een van de modules op HTB. Het geeft een solide basis voor verdere security trainingen en is ook handig voor Azure Cloud Shell beheer.
