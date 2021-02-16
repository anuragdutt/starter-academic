---
title: Using Natural Language Processing and Deep Learning Techniques on 8-k reports for stock price movement prediction - Language Understanding and Reasoning Lab, SBU
summary: We examine the significance of text analysis on 8-k financial reports and implement a unified CNN-RNN model to design a NLP based framework for stock movement prediction.

tags:
- Deep Learning
- Natural Language Processing

date: "2019-12-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image: 
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

links:
- icon: laptop
  icon_pack: fab
  name: Lab website
  url: https://twitter.com/stonybrooknlp?lang=en
url_code: "https://github.com/anuragdutt/spred_nlp"
url_pdf: "https://github.com/anuragdutt/spred_nlp/blob/master/Project_Report.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
In this work we test if financial reports can be utilized to research the significance of text analysis for stock price prediction.  Our corpus adjustsportrayals of money related occasions announcedin 8-K records with the relating stock costs, whichencourages  the  improvement  of  stock  price  esti-mation frameworks which joins textual and finan-cial  data.   Utilizing  the  corpus,  we  demonstratethat  using  textual  data  has  a  significant  impactespecially  for  short-term  periods.(the  two  dayspromptly  following  the  occasion). We see that on applying our Bi-LSTM based dependency parser over then RNN-CNN framework, there is improovement to some extent in the performanceof the model as compared to only the CNN or the RNN based model. We believe that this is so because CNN’s pooling activity on nearby words can hold the neighborhood highlights and their consecutive relations  in  a  sentence and,  the RNN  can  learn the  long-term  dependencies  and  the  positional relation of features as well as the global features of the whole sentence.
