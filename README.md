# CyberSecurity Learning Blog

Blog over Azure certificeringen (AZ-900, AZ-104, SC-900) en CyberSecurity.  
Live op [security.hvsoftware.nl](https://security.hvsoftware.nl/).

## Tech stack

- **Generator:** [Hugo](https://gohugo.io/) (static site generator)
- **Thema:** [PaperMod](https://github.com/adityatelange/hugo-PaperMod)
- **Hosting:** GitHub Pages
- **CI/CD:** GitHub Actions

## Nieuwe blogpost schrijven

```bash
hugo new content posts/korte-titel.md
```

Dit maakt een nieuw Markdown-bestand aan in `content/posts/`.  
Open het bestand, pas de frontmatter aan en schrijf je post onder `---`.

**Frontmatter voorbeeld:**

```yaml
---
title: 'Titel van je post'
date: 2026-07-01
draft: false
categories: ['Azure']
tags: ['az-900', 'onderwerp']
---
```

## Lokaal testen

```bash
hugo server -D
```

Open http://localhost:1313 in je browser. Wijzigingen worden live herladen.

## Publiceren

```bash
git add -A
git commit -m "Nieuwe post: [titel]"
git push
```

GitHub Actions bouwt en deployt automatisch naar GitHub Pages.

## Projectstructuur

```
blog/
├── content/posts/        # Blogposts in Markdown
├── themes/PaperMod       # Hugo thema (git submodule)
├── static/               # Statische bestanden
├── hugo.toml             # Hugo configuratie
└── .github/workflows/    # CI/CD workflow
```

## Certificatie planning

| Certificatie | Status |
|-------------|--------|
| AZ-900 (Azure Fundamentals) | Voorbereiding |
| SC-900 (Security & Compliance) | Actief |
| AZ-104 (Azure Administrator) | Volgende |
