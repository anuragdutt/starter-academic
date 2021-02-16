---
title: Multi-Agent Generative Adversarial Self-Imitation Learning (Graduate project)
summary: This project implements and experiments a Generative Adversarial Self-Imitation Learning (GASIL)approach for the multiagent predator prey environment. 

tags:
- Deep Learning
- Generative Adversarial Imitation Learning
- Reinforcement Learning
- Imitation Learning
- Self Imitation Learning

date: "2020-05-18T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image: 
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

links:
- icon: laptop
  icon_pack: fab
  name: Lab website
  url: http://michaelryoo.com/
url_code: "https://github.com/anuragdutt/gasil_robotics/tree/master/multiagent"
url_pdf: "https://github.com/anuragdutt/gasil_robotics/blob/master/gasil_report.pdf"
url_slides: "https://github.com/anuragdutt/gasil_robotics/blob/master/gasil_presentation.pptx"
url_video: "https://drive.google.com/file/d/1ySmY4gkfAEFhHPR9_6Q8m3ZzTcPOu-EE/view?usp=sharing"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: gasil_presentation
---

In GANs, a discriminator is trained to discriminate whether a given sample is drawn from data distribution or model distribution. A generator (i.e., model) is trained to “fool” the discriminator by generating samples that are close to the real data. In reward learning true reward function may not be optimal or even known, GASIL learns a discriminator which acts as an internal reward function that the policy should maximize. In self imitation learning the agent directly from the past experience by retrieving similar states in the past and choosing the best action made in the past. In GASIL architecture, the agent directly learns to imitate past good trajectories without learning a generative model. GASIL can be viewed as a generative adversarial extension of self-imitation learning. The GASIL approach stores and imitates
the high reward trajectories seen in the past, and imitates them in the Adversarial framework.
GASIL could be complemented with the Q-Learning or Policy gradient in the control part of the
reinforcement learning. We implemented the GASIL in multi-agent environment and our results show
that the GASIL outperforms the basline DDPG model.s
