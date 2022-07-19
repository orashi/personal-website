---
title: "User-Guided Deep Anime Line Art Colorization with Conditional Adversarial Networks"
authors:
- orashi
- Xinzhu Ma
- Zhihui Wang
- Haojie Li
- Zhongxuan Luo
date: "2018-10-22T00:00:00Z"
doi: "10.1145/3240508.3240661"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Multimedia 2018*
publication_short: In *ACMMM 2018*

abstract: Scribble colors based line art colorization is a challenging computer vision problem since neither greyscale values nor semantic information is presented in line arts, and the lack of authentic illustration-line art training pairs also increases difficulty of model generalization. Recently, several Generative Adversarial Nets (GANs) based methods have achieved great success. They can generate colorized illustrations conditioned on given line art and color hints. However, these methods fail to capture the authentic illustration distributions and are hence perceptually unsatisfying in the sense that they are often lack of accurate shading. To address these challenges, we propose a novel deep conditional adversarial architecture for scribble based anime line art colorization. Specifically, we integrate the conditional framework with WGAN-GP criteria as well as the perceptual loss to enable us to robustly train a deep network that makes the synthesized images more natural and real. We also introduce a local features network that is independent of synthetic data. With GANs conditioned on features from such network, we notably increase the generalization capability over "in the wild" line arts. Furthermore, we collect two datasets that provide high-quality colorful illustrations and authentic line arts for training and benchmarking. With the proposed model trained on our illustration dataset, we demonstrate that images synthesized by the presented approach are considerably more realistic and precise than alternative approaches. 


# Summary. An optional shortened abstract.
summary:  We proposed a model and a dataset for accurate anime line art colorization. This model improved the visual result over the previously proposed methods.


tags:
- GAN
- Anime
featured: false

links:
url_pdf: https://arxiv.org/pdf/1808.03240
url_code: 'https://github.com/orashi/AlacGAN'
url_dataset: 'https://pan.baidu.com/s/1oHBqdo2cdM8jOmAaix9xpw'
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
  #caption: 'Our proposed method colorizes a line art composed by artist (left) based on guided stroke colors.'
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

