---
title: 'Conversational Image Generation: Towards Multi-Round Personalized Generation with Multi-Modal Language Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haochen Zhang
  - admin
  - Felix Juefei-Xu
  - Haoyu Ma
  - Kunpeng Li
  - Zhipeng Fan
  - Xiaoliang Dai
  - Tingbo Hou
  - Peizhao Zhang
  - Zecheng He

# Author notes (optional)
# author_notes:
 # - 'Equal contribution'
 # - 'Equal contribution'

date: '2025-12-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Winter Conference on Applications of Computer Vision 2026*
publication_short: In *WACV 2026*

abstract: Recent advancements in diffusion models have significantly enhanced personalized image generation, enabling high-fidelity synthesis of human-subject-specific images. However, existing approaches are constrained by the inherent limitations of diffusion models, which lack conversational capabilities, and operate in a single-round setting, restricting user interaction. In this work, we propose a novel framework that integrates multi-modal large language models (MLLMs) for multi-round conversational personalization. To achieve this, we identified a performance bottleneck in the detokenizer of current MLLMs, which struggles to reconstruct fine-grained facial identity details. Thus, we enhance the detokenizer with a personalization-enhaced Diffusion Transformer (DiT). We also introduce a multi-stage instruction fine-tuning strategy to balance face preservation and prompt alignment effectively. To support multi-round generation, we implement a chat-history caching mechanism and construct the first multi-round personalization dataset from video clips. Experimental results demonstrate that our approach achieves state-of-the-art performance among MLLM-based personalization methods. To the best of our knowledge, this is the first work to enable conversational personalization, unlocking new capabilities for MLLMs in personalized image generation.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
 # - name: Blog
  #  url: https://about.fb.com/news/2023/09/introducing-ai-powered-assistants-characters-and-creative-tools/

url_pdf: 'https://openaccess.thecvf.com/content/WACV2026/papers/Zhang_Conversational_Image_Generation_Towards_Multi-Round_Personalized_Generation_with_Multi-Modal_Language_WACV_2026_paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
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
