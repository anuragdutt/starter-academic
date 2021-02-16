---
title: Dropout - A Simple Way to Prevent GANs from Overfitting (Graduate Project - Columbia)
summary: We propose to incorporate adversarial dropout in generative multiadversarial networks.

tags:
- Deep Learning
- Generative Adversarial Networks

date: "2018-12-21T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image: 
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

links:
- icon: laptop
  icon_pack: fab
  name: Lab website
  url: https://www.ieor.columbia.edu/faculty/ali-hirsa
url_code: "https://github.com/anuragdutt/DropoutGAN"
url_pdf: "https://github.com/anuragdutt/DropoutGAN/blob/master/report/final_paper.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
Overfitting is a serious problem when using deep neural networks with a large
number of parameters. Large networks also take more time to train and test, making it less
practical in the real world. To address this problem, Dropout is widely employed. By randomly
removing units and its connections from the network, the technique significantly reduces co-
adapting effects during training. In our report, we mainly investigate this technique using three
datasets, MNIST, CIFAR10, and CIFAR100, and compare the result with related papers. The
result suggests that Dropout leads to an increase of accuracy making predictions. Batch
Normalization is another powerful technique in deep learning. However, combining Dropout and
Batch Normalization together often result in a worse performance. We explore different
strategies dealing with this problem. At the end, we further apply these strategies to multi-adversarial GANs.
