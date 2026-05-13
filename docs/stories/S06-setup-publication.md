# S06 — Setup stack de publication

## Objectif
Décider et configurer la stack pour publier le vault en ligne quand il atteint 20 fiches.

## Options

### Option A — Astro (recommandé)
- Content Collections natif pour le vault markdown
- Génération statique, rapide
- Contrôle total du design
- Déploiement Vercel

### Option B — Obsidian Publish
- Zéro setup
- Design limité, pas personnalisable
- 8$/mois

### Option C — GitHub Pages + Jekyll
- Gratuit
- Moins flexible pour le design

## Critères d'acceptance
- [ ] Décision stack documentée dans un ADR (`docs/adr/`)
- [ ] Repo configuré pour la publication choisie
- [ ] onsaabdesign.com pointé vers le déploiement
- [ ] Disclaimer visible sur toutes les pages

## Condition de déclenchement
Déclencher quand le vault atteint 20 fiches avec statut "published".

## Dépend de
S01 → S05 (vault suffisamment riche)
