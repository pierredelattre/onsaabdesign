# onsaabdesign — MLP Scope

## Les 5 features du MLP

### 1. Template de fiche vault
**Minimum fonctionnel :** frontmatter YAML standardisé + structure en 3 sections (Contexte / Analyse / Connexions).
**Minimum lovable :** template clair, avec exemples de remplissage, qui rend chaque fiche cohérente et navigable dès le premier coup d'œil.

### 2. Vault initial — 10 fiches fondatrices
**Minimum fonctionnel :** 10 fiches complètes couvrant les catégories clés.
**Minimum lovable :** chaque fiche est un objet de référence en soi — sourcé, analytique, avec des connexions vers d'autres fiches. Pas de fiche à moitié faite.

Fiches prioritaires :
- `philosophy/saab-aviation-dna.md`
- `philosophy/engineers-first.md`
- `ergonomics/cockpit-philosophy.md`
- `ergonomics/ignition-placement.md`
- `people/sixten-saasonson.md`
- `models/saab-900.md`
- `models/saab-99.md`
- `connections/saab-braun-parallel.md`
- `brand/typography.md`
- `engineering/turbo-saab.md`

### 3. Cross-références entre fiches
**Minimum fonctionnel :** wikilinks `[[nom-de-fiche]]` dans le corps de chaque fiche.
**Minimum lovable :** chaque fiche a au minimum 2 connexions vers d'autres fiches. Le graph Obsidian devient lisible et cohérent.

### 4. Index vault
**Minimum fonctionnel :** fichier `vault/INDEX.md` avec liste de toutes les fiches par catégorie.
**Minimum lovable :** index avec tags, statut (draft/published) et description d'une ligne par fiche.

### 5. Manifeste / page "À propos"
**Minimum fonctionnel :** fichier `MANIFESTE.md` à la racine.
**Minimum lovable :** le texte du brief revu et condensé — ce qu'est ce projet, pourquoi il existe, ce qu'il n'est pas. Peut devenir la page d'accueil du futur site.

## Hors scope MLP

- Publication en ligne (vient après les 20 fiches)
- Newsletter
- Design du site
- Réseaux sociaux actifs

## Qualité non négociable

- Toute affirmation est sourcée
- Aucun visuel sans droits clairs
- Disclaimer visible dans chaque fiche publiée
- Pas de fiche publiée en état "draft"

## Plan de lancement

1. Créer le template → valider sur 2-3 fiches test
2. Écrire les 10 fiches fondatrices dans l'ordre de la liste ci-dessus
3. Construire l'index
4. Écrire le manifeste
5. Commit + push à chaque fiche complétée
6. Quand 20 fiches → décision architecture publication
