---
title: Sarcasm Detection in Code-Mixed Data
summary: 
tags:
  - sarcasm-detection
  - Social media
  - NLP
  - Code-Mixing
  - Sarcasm Detection
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

Sarcasm detection in code-mixed text is a particularly challenging task because sarcasm relies heavily on context, tone, and often spans multiple languages within a single sentence. This project aimed to develop a model that could accurately detect sarcasm in code-mixed social media text. A dataset of code-mixed conversations from platforms like Twitter and YouTube was collected and annotated for sarcastic expressions, focusing on capturing nuanced sarcasm markers across languages. Deep learning models such as Long Short-Term Memory (LSTM) networks and transformer-based models were used to capture the context and semantic relationships in the code-mixed text. The challenges in this task included the context-dependency of sarcasm and the fact that different languages express sarcasm in unique ways, making generalization difficult. The models were trained to recognize sarcastic expressions by leveraging syntactic and semantic features. The results demonstrated that fine-tuning transformer models like BERT and XLM-RoBERTa significantly improved sarcasm detection, with the models showing strong performance in capturing cross-lingual cues for sarcasm in code-mixed data.