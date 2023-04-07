---
title: "FengWu: Pushing the Skillful Global Medium-range Weather Forecast beyond 10 Days Lead"
authors:
- Kang Chen*
- Tao Han*
- Junchao Gong*
- Lei Bai*
- Fenghua Ling
- Jing-Jia Luo
- Xi Chen
- Leiming Ma
- Tianning Zhang
- Rui Su
- Yuanzheng Ci
- Bin Li
- Xiaokang Yang
- Wanli Ouyang
date: "2023-04-07T00:00:00Z"


# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Preprint
publication_short: Preprint

abstract: We present FengWu, an advanced data-driven global medium-range weather forecast system based on Artificial Intelligence (AI). Different from existing data-driven weather forecast methods, FengWu solves the medium-range forecast problem from a multi-modal and multi-task perspective. Specifically, a deep learning architecture equipped with model-specific encoder-decoders and cross-modal fusion Transformer is elaborately designed, which is learned under the supervision of an uncertainty loss to balance the optimization of different predictors in a region-adaptive manner. Besides this, a replay buffer mechanism is introduced to improve medium-range forecast performance. With 39-year data training based on the ERA5 reanalysis, FengWu is able to accurately reproduce the atmospheric dynamics and predict the future land and atmosphere states at 37 vertical levels on a 0.25° latitude-longitude resolution. Hindcasts of 6-hourly weather in 2018 based on ERA5 demonstrate that FengWu performs better than GraphCast in predicting 80% of the 880 reported predictands, e.g., reducing the root mean square error (RMSE) of 10-day lead global z500 prediction from 733 to 651 m2/s2 . In addition, the inference cost of each iteration is merely 600ms on NVIDIA Tesla A100 hardware. The results suggest that FengWu can significantly improve the forecast skill and extend the skillful global medium-range weather forecast out to 10.75 days lead (with ACC of z500 > 0.6) for the first time.

# Summary. An optional shortened abstract.
summary:  


tags:
- AI for Science
featured: false

links:
url_pdf:  'https://arxiv.org/pdf/2304.02948'
#url_video: ''
#url_code: 'https://github.com/orashi/Fast-MoCo'
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
  #caption: '(a): Comparison with state-of-the-arts on ImageNet. All methods uses ResNet-50 encoders and are measured with Top-1 linear evaluation accuracy. (b): Overview of Fast-MoCo that includes the Split-Encode-Combine pipeline.'
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

