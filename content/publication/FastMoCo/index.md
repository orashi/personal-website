---
title: "Evolving Search Space for Neural Architecture Search"
authors:
- orashi
- Chen Lin
- Lei Bai
- Wanli Ouyang
date: "2022-07-18T00:00:00Z"


# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision 2022*
publication_short: In *ECCV 2022*

abstract: Contrastive-based self-supervised learning methods achieved great success in recent years. However, self-supervision requires extremely long training epochs (e.g., 800 epochs for MoCo v3) to achieve promising results, which is unacceptable for the general academic community and hinders the development of this topic. This work revisits the momentum-based contrastive learning frameworks and identifies the inefficiency in which two augmented views generate only one positive pair. We propose Fast-MoCo - a novel framework that utilizes combinatorial patches to construct multiple positive pairs from two augmented views, which provides abundant supervision signals that bring significant acceleration with neglectable extra computational cost. Fast-MoCo trained with 100 epochs achieves 73.5% linear evaluation accuracy, similar to MoCo v3 (ResNet-50 backbone) trained with 800 epochs. Extra training (200 epochs) further improves the result to 75.1%, which is on par with state-of-the-art methods. Experiments on several downstream tasks also confirm the effectiveness of Fast-MoCo.


# Summary. An optional shortened abstract.
summary:  We introduce Fast-MoCo, a simple yet effective self-supervised learning method that boosts the training speed of the momentum-based contrastive learning with combinatorial patches.


tags:
- Self-Supervised Learning
featured: true

links:
#url_pdf: https://arxiv.org/pdf/2011.10904
#url_video: 'https://www.youtube.com/watch?v=fq21WBaumRc'
url_code: 'https://github.com/orashi/Fast-MoCo'
#url_dataset: 'https://pan.baidu.com/s/1oHBqdo2cdM8jOmAaix9xpw'
#- name: Custom Link
#  url: http://example.org
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '(a): Comparison with state-of-the-arts on ImageNet. All methods uses ResNet-50 encoders and are measured with Top-1 linear evaluation accuracy. (b): Overview of Fast-MoCo that includes the Split-Encode-Combine pipeline.'
  focal_point: ""
  preview_only: false

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

