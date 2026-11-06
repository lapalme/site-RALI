---
title: "Les transformations linguistiques utilisées pour tester les constituants syntaxiques constituent-elles un signal utile pour les modèles d'induction grammaticale ?"

summary: " Nous nous intéressons à l’effet des tests de constituants sur l’apprentissage des structures par les modèles d’induction grammaticale."
abstract: "La syntaxe s’intéresse à la structure des phrases, la représentant souvent à l’aide d’arbres de constituants. Les tests de constituants sont utilisés pour justifier les regroupements de mots dans ces structures. Parmi eux, plusieurs tests font appel à du mouvement, c’est-à-dire que les mots ciblés sont déplacés depuis leur position d’origine vers une nouvelle position. L’induction grammaticale suit un objectif similaire, soit d’analyser la structure des phrases. Différents modèles existent, et plusieurs ont recourt à un apprentissage non-supervisé, qui nécessite seulement des phrases sans annotation syntaxique. Nous nous intéressons à l’effet des tests de constituants sur l’apprentissage des structures par les modèles d’induction grammaticale. Pour cela, des phrases sont générées automatiquement. Elles sont par la suite augmentées, en ajoutant des phrases transformées par application de tests de constituants sur chaque constituant valide. Quatre tests sont utilisés : la coordination, l’antéposition Qu-, le clivage et la topicalisation, les trois derniers impliquant du mouvement. Ces données, avec et sans tests, servent à l’entraı̂nement de cinq modèles : URNNG, N-PCFG et C-PCFG, ainsi que C-LCFRS et TN-LCFRS qui permettent des constituants discontinus. En regardant les métriques d’évaluation, il apparait que pour URNNG, seuls la coordination et l’ensemble des tests améliorent légèrement les scores. Pour N-PCFG et C-PCFG, la coordination et l’antéposition Qu- améliorent les performances, contrairement à la topicalisation et au clivage. Avec les modèles LCFRS, le clivage et la topicalisation peuvent avoir, en moyenne, un effet bénéfique. Cependant, différentes erreurs d’analyses syntaxiques apparaissent lorsque les phrases avec les tests sont considérées"

# Dates et horaires (format ISO 8601)
date: 2026-11-25T11:30:00Z
event_start: 2026-11-25T11:30:00Z
# event_end: 2026-11-20T15:30:00Z
all_day: false

# Lieu
location: "OLST, Département de linguistique et traduction / En ligne (ex: Zoom)"
address:
  street: "123 Rue de la Science"
  city: "Montréal"
  region: "QC"
  postcode: "H2X 1Y2"
  country: "Canada"

# Auteurs / Intervenants (doivent correspondre aux profils dans content/authors/)
authors:
  - admin

# Catégories et tags
categories:
  - Conférence
# tags:
#   - HugoBlox
#   - Web

# Liens et ressources (optionnel)
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides intégrées (si vous utilisez le module de slides HugoBlox)
slides: ""

# Image mise en avant (featured.jpg dans le même dossier)
image:
  caption: "Crédit photo : Nom"
  focal_point: Right
---

## À propos de cette intervention

Rédigez ici le contenu principal de votre annonce en Markdown :
* Le plan de la présentation
* Les prérequis pour le public
* Un lien vers l'inscription ou la diffusion en direct

{{% callout note %}}
**Note :** L'entrée est libre sur inscription préalable.
{{% /callout %}}