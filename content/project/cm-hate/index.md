---
title: Hate Speech Identification in Code-Mixed Data
summary: 
tags:
  - Social media
  - NLP
  - Hate Speech
  - cm-hate
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

Hate speech identification in code-mixed text is a challenging but necessary task given the rise of harmful content on social media platforms. The goal of this project was to detect and classify hate speech in code-mixed social media conversations, which often involve multiple languages within a single text. To build an effective model, a dataset of code-mixed text was collected and manually annotated with labels indicating hate speech, offensive language, or neutral text. The primary challenge lay in the implicit nature of hate speech, where users often use metaphors or sarcasm to convey harmful messages across languages. The project utilized transformer-based models like BERT, XLM-RoBERTa, and MURIL to capture the deep semantics of these mixed-language texts. Special attention was given to handling code-switching patterns and the context in which the hate speech was expressed. The results showed that transformer-based models significantly outperformed traditional approaches in identifying hate speech in code-mixed data, especially when dealing with implicit language and sarcasm.
