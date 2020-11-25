---
title: "Evolving Search Space for Neural Architecture Search"
authors:
- orashi
- Chen Lin
- Ming Sun
- Boyu Chen
- Hongwen Zhang
- Wanli Ouyang
date: "2020-11-22T00:00:00Z"


# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv:2011.10904*
publication_short: In *arXiv*

abstract: The automation of neural architecture design has been a coveted alternative to human experts. Recent works have small search space, which is easier to optimize but has a limited upper bound of the optimal solution. Extra human design is needed for those methods to propose a more suitable space with respect to the specific task and algorithm capacity. To further enhance the degree of automation for neural architecture search, we present a Neural Search-space Evolution (NSE) scheme that iteratively amplifies the results from the previous effort by maintaining an optimized search space subset. This design minimizes the necessity of a well-designed search space. We further extend the flexibility of obtainable architectures by introducing a learnable multi-branch setting. By employing the proposed method, a consistent performance gain is achieved during a progressive search over upcoming search spaces. We achieve 77.3% top-1 retrain accuracy on ImageNet with 333M FLOPs, which yielded a state-of-the-art performance among previous auto-generated architectures that do not involve knowledge distillation or weight pruning. When the latency constraint is adopted, our result also performs better than the previous best-performing mobile models with a 77.9% Top-1 retrain accuracy.


# Summary. An optional shortened abstract.
summary:  We proposed a model and a dataset for accurate anime line art colorization. This model improved the visual result over the previously proposed methods.


tags:
- NAS
- AutoML
featured: true

links:
url_pdf: https://arxiv.org/pdf/2011.10904
#url_code: 'https://github.com/orashi/AlacGAN'
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
  caption: 'Comparison of search schemes. (a) Traditional pipeline. (b) Our proposed search space evolving pipeline.'
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

