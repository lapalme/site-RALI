---
# Documentation: https://docs.hugoblox.com/managing-content/

title: Unsupervised multiple-choice question generation for out-of-domain Q&A fine-tuning
subtitle: ''
summary: ''
authors:
- Guillaume Le Berre
- Christophe Cerisara
- Philippe Langlais
- Guy Lapalme
tags: []
categories: []
date: '2022-05-01'
lastmod: 2026-11-05T14:02:25-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2026-11-05T19:02:25.285075Z'
publication_types:
- '1'
abstract: Pre-trained models have shown very good performances on a number of question
  answering benchmarks especially when fine-tuned on multiple question answering datasets
  at once. In this work, we propose an approach for generating a fine-tuning dataset
  thanks to a rule-based algorithm that generates questions and answers from unannotated
  sentences. We show that the state-of-the-art model UnifiedQA can greatly benefit
  from such a system on a multiple-choice benchmark about physics, biology and chemistry
  it has never been trained on. We further show that improved performances may be
  obtained by selecting the most challenging distractors (wrong answers), with a dedicated
  ranker based on a pretrained RoBERTa model.
publication: '*Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)*'
links:
- name: URL
  url: https://aclanthology.org/2022.acl-short.83
---
