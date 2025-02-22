---
title: Code-Mixed Sentiment Analysis
summary: 
tags:
  - Social media
  - NLP
  - Sentiment Analysis
  - Code-Mixing
  - cmsa
  - Tamil-English
  - Kannada-English
  - Malayalam-English
  
date: '2025-02-22T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo taken from internet
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://x.com/SUPLIFE24
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: misinformation
---

Sentiment analysis on code-mixed text is essential for understanding user opinions, particularly in regions where people frequently switch between languages in their conversations. Traditional sentiment analysis models face difficulty in handling such data due to the complexity introduced by the mixture of languages and the lack of large labeled datasets. This project aimed to develop a robust model for detecting and classifying sentiment (positive, negative, neutral) in code-mixed social media text. A dataset was collected from social media platforms like Facebook and Twitter, and preprocessing steps included tokenization, language identification, and normalization of code-mixed text. The hybrid model combined traditional machine learning algorithms like Support Vector Machines (SVM) with deep learning techniques like Bidirectional Long Short-Term Memory (BiLSTM). The project also leveraged multilingual embeddings to capture the semantics of the words in different languages. One of the key challenges was handling context-sensitive elements like sarcasm and slang. The results showed improved accuracy by fine-tuning transformer models like BERT and multilingual BERT, significantly enhancing the performance of sentiment classification on code-mixed data.