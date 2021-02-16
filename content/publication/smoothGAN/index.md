---
title: "SMOOTH-GAN: Towards Sharp and Smooth Synthetic EHR Data Generation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sina Rashidian
- Fusheng Wang
- Victor Garcia
- Richard Mofitt
- admin
- Wei Chang
- Vishwam Pandya
- Janos Hajagos
- Mary Saltz
- Joel Saltz

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2020-09-26T00:00:00Z"
doi: "https://doi.org/10.1007/978-3-030-59137-3_4"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Artificial Intelligence in Medicine*
publication_short: In *AIME 2020*

abstract: Generative adversarial networks (GANs) have been highly successful for generating realistic synthetic data. In healthcare, synthetic data generation can be helpful for producing annotated data and improving data-driven research without worries on data privacy. However, electronic health records (EHRs) are noisy, incomplete and complex, and existing work on EHR data is mainly devoted to generating discrete elements such as diagnosis codes and medications or frequent laboratory values. In this work, we propose SMOOTH-GAN, a novel approach for generating reliable EHR data such as laboratory values and medications given diagnosis codes. SMOOTH-GAN takes advantage of a conditional GAN architecture with WGAN-GP loss, and is able to learn transitions between disease stages with high flexibility over data customization. Our experiments demonstrate the model's effectiveness in terms of both statistical similarity and accuracy on machine learning based prediction. To further demonstrate the usage of our model, we apply counterfactual reasoning and generate data with occurrence of multiple diseases, which can provide unique datasets for artificial intelligence driven healthcare research.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-59137-3_4#citeas'
url_code: 'https://github.com/anuragdutt/synthehr_medgan/tree/master/src'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
