---
title: Word-level Language Identification in Code-Mixed Data 
summary: 
tags:
  - Social media
  - NLP
  - Language Identification
  - Code-Mixing
  - cmlid
  - Bengali-English
  - Hindi-English
  - Spanish-English
  
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

Code-mixed word-level language identification is crucial for accurately tagging the language of each word in a sentence, especially in multilingual social media text. The primary challenge in this task arises from the mixing of languages within a single sentence, script variations, and the phonetic spelling of words. The objective of this project was to develop models that can accurately identify the language at the word level in such mixed-language environments. To achieve this, datasets were collected from social media platforms where users often switch between languages, and each word was manually annotated with its language tag. The project involved using traditional machine learning algorithms like Conditional Random Fields (CRF) and deep learning models like Recurrent Neural Networks (RNN) and transformer-based models such as XLM-RoBERTa. The major challenges included handling ambiguous tokens, mixed-script words, and non-language tokens like hashtags and emoticons. The results demonstrated significant improvements in word-level language identification by fine-tuning multilingual embeddings, providing a strong foundation for further tasks like translation, sentiment analysis, and hate speech detection.