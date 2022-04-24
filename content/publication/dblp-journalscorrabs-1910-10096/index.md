---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Formalizing Privacy Laws for License Generation and Data Repository Decision
  Automation
subtitle: ''
summary: ''
authors:
- Micah Altman
- Stephen Chong
- Alexandra Wood
tags: []
categories: []
date: '2019-01-01'
lastmod: 2022-04-24T09:33:16-04:00
featured: true
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
publishDate: '2022-04-24T13:33:38.396435Z'
publication_types:
- '0'
abstract: '
In this paper, we summarize work-in-progress on expert system support to automate some data deposit and release decisions within a data repository, and to generate custom license agreements for those data transfers.
Our approach formalizes via a logic programming language the privacy-relevant aspects of laws, regulations, and best practices, supported by legal analysis documented in legal memoranda. This formalization enables automated reasoning about the conditions under which a repository can transfer data, through interrogation of users, and the application of formal rules to the facts obtained from users. The proposed system takes the specific conditions for a given data release and produces a custom data use agreement that accurately captures the relevant restrictions on data use. This enables appropriate decisions and accurate licenses, while removing the bottleneck of lawyer effort per data transfer. The operation of the system aims to be transparent, in the sense that administrators, lawyers, institutional review boards, and other interested parties can evaluate the legal reasoning and interpretation embodied in the formalization, and the specific rationale for a decision to accept or release a particular dataset.
'
publication: '*arXiv*'
links:
- name: URL
  url: http://arxiv.org/abs/1910.10096
---
