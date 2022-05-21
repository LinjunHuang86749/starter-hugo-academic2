---
title: Example Project
summary: An example of using the in-built project page.
tags:
  - Deep Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

#links:
url_code: 'https://github.com/bingguJ/5242_project'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
{{< icon name="download" pack="fas" >}} Download my {{< staticref "uploads/resume.pdf" "newtab" >}}resumé{{< /staticref >}}.


The research of style transfer expands a lot in recent years due to the evolution of Convolutional Neural Networks. In this report, we build a neural style transfer network based on a pre-trained VGG-19 model that will capture the style and
content from the image. Choosing some specific pre-trained layer from the CNN model and then applying gradient descent, the blending of image style and image content makes this neural network an artist. There are three major improvements based on the current image style transfer paper. The first idea developed from the paper is utilizing a blurred version of the content image as the initial inputs. Secondly, we preprocessed images before taking them into the different choice of CNN layers from the paper. And lastly, the noise of the output image has been optimized.
