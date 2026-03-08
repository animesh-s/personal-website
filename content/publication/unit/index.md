---
title: 'UniT: Unified Multimodal Chain-of-Thought Test-time Scaling'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Leon Liangyu Chen
  - Haoyu Ma
  - Zhipeng Fan
  - Ziqi Huang
  - admin
  - Xiaoliang Dai
  - Jialiang Wang
  - Zecheng He
  - Jianwei Yang
  - Chunyuan Li
  - Junzhe Sun
  - Chu Wang
  - Serena Yeung-Levy
  - Felix Juefei-Xu
  
# Author notes (optional)
# author_notes:
 # - 'Equal contribution'
 # - 'Equal contribution'

date: '2026-02-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-02-12T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *ArXiv:2602.12279*
publication_short: In *arXiv:2602.12279*

abstract: Unified models can handle both multimodal understanding and generation within a single architecture, yet they typically operate in a single pass without iteratively refining their outputs. Many multimodal tasks, especially those involving complex spatial compositions, multiple interacting objects, or evolving instructions, require decomposing instructions, verifying intermediate results, and making iterative corrections. While test-time scaling has demonstrated that allocating additional inference compute for iterative reasoning substantially improves language model performance, extending this paradigm to unified multimodal models remains an open challenge. We introduce UniT, a framework for multimodal chain-of-thought test-time scaling that enables a single unified model to reason, verify, and refine across multiple rounds. UniT combines agentic data synthesis, unified model training, and flexible test-time inference to elicit cognitive behaviors including verification, subgoal decomposition, and content memory. Our key findings are: unified models trained on short reasoning trajectories generalize to longer inference chains at test time; sequential chain-of-thought reasoning provides a more scalable and compute-efficient TTS strategy than parallel sampling; training on generation and editing trajectories improves out-of-distribution visual reasoning. These results establish multimodal test-time scaling as an effective paradigm for advancing both generation and understanding in unified models.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
 # - name: Blog
  #  url: https://about.fb.com/news/2023/09/introducing-ai-powered-assistants-characters-and-creative-tools/

url_pdf: 'https://arxiv.org/pdf/2602.12279'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://ai.meta.com/research/publications/unit-unified-multimodal-chain-of-thought-test-time-scaling/'
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
