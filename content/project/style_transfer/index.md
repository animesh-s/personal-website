---
title: Neural Style Transfer
summary: About A PyTorch implementation of 'A Neural Algorithm of Artistic Style' by L. Gatys, A. Ecker, and M. Bethge
tags:
  - Deep Learning
date: '2018-04-16T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart

# links:
#  - name: Github
#    url: https://github.com/animesh-s/Neural-Style-Transfer
url_code: 'https://github.com/animesh-s/Neural-Style-Transfer'
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

Neural Style Transfer allows us to combine the style of an image with the content of a natural image by manipulating the feature representations learned by a Convolutional Neural Network. For example, it can enable us to transfer the style from Vincent van Gogh's The Starry Night to an image of Neckarfront in Tübingen.

We can experiment with the different ratios of content and style in the output image using the content and style loss weights. A higher style loss weight would make the output image resemble more closely to the style image rather than the content image. Here are some examples of two different ratios of content and style losses applied to Neckarfront and four different style images.

The first column shows the style images, the second column shows the output from the algorithm when the content and style losses are weighted in a balanced fashion and the third column shows the output when the style loss is weighted very high compared to the content weight.
