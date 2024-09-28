---
title: 'Imagine yourself: Tuning-Free Personalized Image Generation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zecheng He
  - Bo Sun
  - Felix Juefei-Xu
  - Haoyu Ma
  - Ankit Ramchandani
  - Vincent Cheung
  - Siddharth Shah
  - Anmol Kalia
  - Harihar Subramanyam
  - Alireza Zareian
  - Li Chen
  - Ankit Jain
  - Ning Zhang
  - Peizhao Zhang
  - Roshan Sumbaly
  - Peter Vajda
  - admin

# Author notes (optional)
# author_notes:
 # - 'Equal contribution'
 # - 'Equal contribution'

date: '2024-09-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *Arxiv:2409.13346*
publication_short: In *arxiv:2409.13346*

abstract: Diffusion models have demonstrated remarkable efficacy across various image-to-image tasks. In this research, we introduce Imagine yourself, a state-of-the-art model designed for personalized image generation. Unlike conventional tuning-based personalization techniques, Imagine yourself operates as a tuning-free model, enabling all users to leverage a shared framework without individualized adjustments. Moreover, previous work met challenges balancing identity preservation, following complex prompts and preserving good visual quality, resulting in models having strong copy-paste effect of the reference images. Thus, they can hardly generate images following prompts that require significant changes to the reference image, e.g., changing facial expression, head and body poses, and the diversity of the generated images is low. To address these limitations, our proposed method introduces 1) a new synthetic paired data generation mechanism to encourage image diversity, 2) a fully parallel attention architecture with three text encoders and a fully trainable vision encoder to improve the text faithfulness, and 3) a novel coarse-to-fine multi-stage finetuning methodology that gradually pushes the boundary of visual quality. Our study demonstrates that Imagine yourself surpasses the state-of-the-art personalization model, exhibiting superior capabilities in identity preservation, visual quality, and text alignment. This model establishes a robust foundation for various personalization applications. Human evaluation results validate the model’s SOTA superiority across all aspects (identity preservation, text faithfulness, and visual appeal) compared to the previous personalization models.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
 # - name: Blog
  #  url: https://about.fb.com/news/2023/09/introducing-ai-powered-assistants-characters-and-creative-tools/

url_pdf: 'https://arxiv.org/pdf/2409.13346'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://ai.meta.com/research/publications/imagine-yourself-tuning-free-personalized-image-generation/'
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
