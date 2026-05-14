# onsaabdesign — CLAUDE.md

## Contexte
Projet éditorial indépendant. Archive / second cerveau centré sur Saab comme objet d'étude design industriel, ergonomie et philosophie de marque. Angle : UX, ingénieurs, designers, héritage scandinave — pas un fan site.

**Disclaimer permanent** : "Independent editorial project. Not affiliated with Saab AB or NEVS."

## Ce projet n'est PAS
- Un fan site ou forum
- Un site e-commerce

## Périmètre Claude

**Claude s'occupe de :**
- Architecture projet (structure vault, conventions, templates)
- Config technique du site (Astro, Vercel, scripts, CI)
- Setup et déploiement

**Pierre s'occupe de :**
- Design et intégration visuelle
- Contenu éditorial (fiches, textes, pages)
- Choix graphiques

## Structure vault
- `vault/brand/` — identité visuelle, typographie, logos, chartes
- `vault/ergonomics/` — cockpit, interfaces bord, sièges, Human Factors
- `vault/engineering/` — turbo, traction avant, carrosserie, aéro
- `vault/philosophy/` — ADN de marque, manifestes, discours fondateurs
- `vault/people/` — fiches designers et ingénieurs clés
- `vault/models/` — fiches par modèle (900, 9000, 99...)
- `vault/connections/` — ponts avec Braun, Dieter Rams, B&O, Citroën DS, Volvo...

## Format des fiches vault
Chaque note vault = fichier markdown avec :
- frontmatter YAML (titre, catégorie, tags, sources, date)
- corps structuré : contexte → analyse → liens

## Règles éditoriales
- Tout texte narratif passe par `/humanizer`
- Sources citées systématiquement
- Pas de reproduction directe de visuels protégés Saab
- Crédit explicite pour toute photo ou document tiers

## Stack actuel
Markdown pur. Pas de framework. Obsidian-compatible.
