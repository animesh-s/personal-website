---
title: 'Movie Weaver: Tuning-Free Multi-Concept Video Personalization with Anchored Prompts'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Feng Liang
  - Haoyu Ma
  - Zecheng He
  - Tingbo Hou
  - Ji Hou
  - Kunpeng Li
  - Xiaoliang Dai
  - Felix Juefei-Xu
  - Samaneh Azadi
  - admin
  - Peizhao Zhang
  - Peter Vajda
  - Diana Marculescu

# Author notes (optional)
# author_notes:
 # - 'Equal contribution'
 # - 'Equal contribution'

date: '2025-02-04T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Computer Vision and Pattern Recognition 2025*
publication_short: In *CVPR 2025*

abstract: Video personalization, which generates customized videos using reference images, has gained significant attention. However, prior methods typically focus on single-concept personalization, limiting broader applications that require multi-concept integration. Attempts to extend these models to multiple concepts often lead to identity blending, which results in composite characters with fused attributes from multiple sources. This challenge arises due to the lack of a mechanism to link each concept with its specific reference image. We address this with anchored prompts, which embed image anchors as unique tokens within text prompts, guiding accurate referencing during generation. Additionally, we introduce concept embeddings to encode the order of reference images. Our approach, Movie Weaver, seamlessly weaves multiple concepts-including face, body, and animal images-into one video, allowing flexible combinations in a single model. The evaluation shows that Movie Weaver outperforms existing methods for multi-concept video personalization in identity preservation and overall quality.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
 # - name: Blog
  #  url: https://about.fb.com/news/2023/09/introducing-ai-powered-assistants-characters-and-creative-tools/

url_pdf: 'https://arxiv.org/pdf/2502.07802'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://jeff-liangf.github.io/projects/movieweaver/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
