---
title: "Fast-MoCo: Boost Momentum-based Contrastive Learning with Combinatorial Patches"
authors:
- orashi*
- Yizhou Wang*
- Meilin Chen
- Shixiang Tang
- Lei Bai
- Feng Zhu
- Rui Zhao
- Fengwei Yu
- Donglian Qi
- Wanli Ouyang
date: "2022-11-18T00:00:00Z"


# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Under Review
publication_short: Under Review

abstract: Human-centric perceptions (e.g., pose estimation, human parsing, pedestrian detection, person reidentification, 
etc.) play a key role in industrial applications of visual models. While specific human-centric tasks have their own relevant 
semantic aspect to focus on, they also share the same underlying semantic structure of the human body. However, few works have attempted 
to exploit such homogeneity and design a general-propose model for human-centric tasks. In this work, we revisit a broad range of 
human-centric tasks and unify them in a minimalist manner. We propose UniHCP, a Unified Model for Human-Centric Perceptions, which 
unifies a wide range of human-centric tasks in a simplified end-to-end manner with the plain vision transformer architecture. With 
large-scale joint training on 33 human-centric datasets, UniHCP can outperform strong baselines on several in-domain and downstream 
tasks by direct evaluation. When adapted to a specific task, UniHCP achieves new SOTAs on a wide range of human-centric tasks, e.g., 
69.8 mIoU on CIHP for human parsing, 86.18 ma on PA-100K for attribute prediction, 90.3 mAP on Market1501 for ReID, and 85.8 JI on CrowdHuman 
for pedestrian detection, performing better than specialized models tailored for each task.


# Summary. An optional shortened abstract.
summary:  We introduce a Unified Model for Human-Centric Perceptions (UniHCP), which can easily handle multiple distinctly 
defined human-centric tasks simultaneously, be trained at scale and obtains a series of SOTA performances over
a wide spectrum of human-centric benchmarks.


tags:
featured: false

links:
# url_pdf: https://arxiv.org/pdf/2207.08220
# url_video: 'https://youtu.be/nKEb6YWm8xc'
# url_code: 'https://github.com/orashi/Fast-MoCo'
# #url_dataset: 'https://pan.baidu.com/s/1oHBqdo2cdM8jOmAaix9xpw'
#- name: Custom Link
#  url: http://example.org
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: '(a): Comparison with state-of-the-arts on ImageNet. All methods uses ResNet-50 encoders and are measured with Top-1 linear evaluation accuracy. (b): Overview of Fast-MoCo that includes the Split-Encode-Combine pipeline.'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
