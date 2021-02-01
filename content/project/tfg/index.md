---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Social media data mining for fast-food prevalence characterization"
summary: "Using Machine Learning models to get insights about fast-food consumption in a region."
authors: []
tags: ["Python", "machine learning", "NLP", "image analysis"]
categories: ["Final Year Project"]
date: 2020-01-23T20:18:42+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/dveni/TFG"
url_pdf: "http://gsi.upm.es/administrator/components/com_jresearch/files/publications/tfg-dani-vera.pdf"
url_slides: ""
url_video: "https://www.youtube.com/watch?v=jM3m-Z3n3yA"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This project was carried out as my Final Year Project.

## Abstract

An escalating global epidemic of overweight and obesity is taking over many parts of the world. Among several factors that influence this, dietary habits are a key element due to they have a profound impact on human life, health, and well-being. In addition, several chronic diseases have been linked to overweight and obesity, which have been found to be positively associated with eating fast-food. Thus, the study of dietary habits is important for both cultural understandings and for monitoring public health. Traditionally, large-scale dietary studies of food consumption used questionnaires and food diaries to keep track of the daily activities of their participants, which can be intrusive and expensive to conduct. In last years social networks have become a valuable source of information to assess the habits, opinions, and decisions taken by their users, so researches are examining ways to use social data to address health-related issues. Framed in a collaboration project part of the Food4Health European program, our work aims to determine if it is possible to characterize fast-food consumption through the in- formation of the messages posted on Twitter. For this purpose, we have made a classifier using machine learning techniques, available with Scikit-learn Python library, capable of classifying tweets from users referring to fast-food. In addition, we have enriched our system with the analysis of the images attached to tweets using both image classification and object detection models. They are based on convolutional neural networks focused on object recognition, and transfer learning techniques have been used to use pre-trained models in our objective, to recognize food. Also, sentiment and emotion analysis have been performed on tweets in order to assess the sentiments and emotions related to fast-food. This system has been tested in the Spanish case, assessing the fast-food prevalence in the country along with image and sentiment analysis to provide health-related information.