# Rapport scientifique DOCK6

Ce dossier contient la version éditoriale, reformatée pour la lecture et la
publication, du rapport de phase 19.

## Ouvrir le rapport

Ouvrir `index.html` dans un navigateur, ou l'imprimer en PDF
(`Ctrl/Cmd + P`, marges par défaut, graphiques d'arrière-plan activés). Le
fichier est **entièrement autonome** : les 6 figures 1000 Genomes/LD/ROH/âge
sont encodées en base64 et intégrées directement dans le HTML (elles ne
dépendent plus du dossier `images/`). Le fichier peut donc être déplacé,
renommé, envoyé par email ou copié seul sans rien casser.

Structure du document : couverture, sommaire paginé, résumé exécutif,
contexte et méthodes, Résultats 1 à 7, conclusion générale, puis deux
annexes techniques (seuils de filtrage détaillés, configuration complète du
run). Pagination A4 via CSS `@page` + Paged.js.

Le dossier `images/` est conservé à titre de **source/provenance** des
figures (voir `provenance_images.md`) ; il n'est plus requis pour l'affichage
du rapport lui-même.

## Source

- Run : `2026-08-16T154147Z_dock6_reunion_founder_effect_13811a00`
- Rapport historique :
  `data/runs/2026-08-16T154147Z_dock6_reunion_founder_effect_13811a00/stages/19_build_report/report_draft.html`
- Provenance des figures : `provenance_images.md`

Le rapport historique du run reste la source immuable. Les révisions de mise en
page destinées à la lecture et à la publication sont réalisées dans
`index.html` à la racine de ce dépôt.

## Anonymisation et publication

La publication de ce rapport est autorisée uniquement dans une forme ne
permettant pas de relier les résultats à une personne déterminée. La version
publiée ne doit contenir ni nom, ni identifiant clinique ou administratif, ni
identifiant d'échantillon issu des données sources, ni table de correspondance,
ni donnée génétique individuelle brute.

Les identifiants techniques ou familiaux éventuellement présentés doivent être
des pseudonymes propres au rapport, sans clé de réidentification publiée. Les
résultats génétiques et familiaux doivent rester agrégés ou suffisamment
anonymisés pour qu'ils ne puissent pas être recoupés avec un individu
spécifique. Une revue de non-réidentification reste requise avant chaque
nouvelle publication ou diffusion d'une version modifiée.
