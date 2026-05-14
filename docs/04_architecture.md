# onsaabdesign — Architecture

## Format produit

Phase actuelle : **second cerveau en markdown pur**, Obsidian-compatible.
Phase suivante (publication) : **site statique Astro**, déployé sur Vercel ou GitHub Pages.

## Stack actuel (second cerveau)

| Couche | Choix | Raison |
|--------|-------|--------|
| Format | Markdown + frontmatter YAML | Portable, pérenne, Obsidian-compatible |
| Éditeur local | Obsidian | Graph view, wikilinks, backlinks natifs |
| Versioning | Git + GitHub | Historique, backup, collaboration future |
| Publication future | Astro | Markdown-first, rapide, flexible, beau |

## Structure vault (actuelle)

```
vault/
├── brand/           → identité visuelle, typographie, chartes
├── ergonomics/      → cockpit, interfaces bord, sièges, Human Factors
├── engineering/     → turbo, traction avant, carrosserie, aérodynamique
├── philosophy/      → ADN de marque, manifestes, discours fondateurs
├── people/          → fiches designers et ingénieurs clés
├── models/          → fiches par modèle (900, 9000, 99, Sonett...)
└── connections/     → Braun, Dieter Rams, B&O, Citroën DS, Volvo...
```

## Format de fiche vault (standard)

```yaml
---
title: ""
category: ergonomics | philosophy | people | brand | engineering | models | connections
tags: []
sources: []
related: []
date_created: YYYY-MM-DD
status: draft | review | published
---

## Contexte

## Analyse

## Connexions
```

## Décisions techniques

**Pourquoi Obsidian et pas Notion :** Markdown pur, pas de lock-in propriétaire. Les fichiers restent des fichiers.

**Pourquoi Astro pour la publication :** Framework markdown-first, génération statique, excellent support des collections de contenu. Parfait pour un vault de fiches. Pas de Next.js pour un projet sans interactivité client-side réelle.

**Pourquoi pas Obsidian Publish :** Trop limité visuellement pour un projet où le design de la publication compte.

## Phase de publication (future)

Quand le vault atteint 20 fiches complètes :
1. Setup Astro avec content collections
2. Page index par catégorie + système de tags
3. Déploiement Vercel (preview automatique par PR)
4. Pointer onsaabdesign.com

Aucun backend, aucune base de données. Site 100% statique.
