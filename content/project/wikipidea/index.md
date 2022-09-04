---
title: Wikipedia Vandalism Detection
summary: Vandalism detection in Wikipedia page edits
tags:
  - Other
date: '2016-12-04T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart

# links:
#  - name: Github
#    url: https://github.com/animesh-s/Neural-Style-Transfer
url_code: 'https://github.com/animesh-s/Wikipedia-Vandalism-Detection'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

We identify the cases of vandalism on Wikipedia articles by classifying edits as either regular or vandalism. This is clearly a Binary Classification task, but because of the skewed distribution of regular and vandalism cases in the dataset, we will also explore if this can be modeled as an Anomaly Detection problem.

We use the corpus of vandalism cases found on Wikipedia which is available [here] (http://www.uni-weimar.de/en/media/chairs/webis/corpora/pan-wvc-10/). The corpus consists of 32452 edits on 28468 Wikipedia articles among which 2391 edits have been labeled as vandalism, while the rest are labeled as regular.
