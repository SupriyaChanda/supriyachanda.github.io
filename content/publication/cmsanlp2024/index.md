---
title: 'Sentiment analysis of code-mixed Dravidian languages leveraging pretrained model and word-level language tag'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Anshika Mishra
  - Sukomal Pal
  
# Author notes (optional)


date: '2024-09-11T00:00:00Z'
doi: '10.1017/nlp.2024.30'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-11T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Natural Language Processing*
publication_short: In *NLP*

abstract: The exponential growth of social media data in the era of Web 2.0 has necessitated advanced techniques for sentiment analysis. While sentiment analysis in monolingual datasets has received significant attention that in code-mixed datasets still need to be studied more. Code-mixed data often contain a mixture of monolingual content (might be in transliterated form), single-script but multilingual content, and multi-script multilingual content. This paper explores the issue from three important angles. What will be the best strategy to deal with the data for sentiment detection? Whether to train the classifier with the whole of the dataset or only with the pure code-mixed subset from the dataset? How much important is the language identification (LID) for the task? If LID is to be done, how, and when will it be used to yield the best performance? We explore the questions in the light of three datasets of Tamil–English, Kannada–English, and Malayalam–English YouTube social media comments. Our solution incorporated mBERT and an optional LID module. We report our results using a set of metrics like precision, recall,  score, and accuracy. The solutions provide considerable performance gain and some interesting insights for sentiment analysis from code-mixed data.
# Summary. An optional shortened abstract.
summary: The exponential growth of social media data in the era of Web 2.0 has necessitated advanced techniques for sentiment analysis. While sentiment analysis in monolingual datasets has received significant attention that in code-mixed datasets still need to be studied more. Code-mixed data often contain a mixture of monolingual content (might be in transliterated form), single-script but multilingual content, and multi-script multilingual content. This paper explores the issue from three important angles. What will be the best strategy to deal with the data for sentiment detection? Whether to train the classifier with the whole of the dataset or only with the pure code-mixed subset from the dataset? How much important is the language identification (LID) for the task? If LID is to be done, how, and when will it be used to yield the best performance? We explore the questions in the light of three datasets of Tamil–English, Kannada–English, and Malayalam–English YouTube social media comments. Our solution incorporated mBERT and an optional LID module. We report our results using a set of metrics like precision, recall,  score, and accuracy. The solutions provide considerable performance gain and some interesting insights for sentiment analysis from code-mixed data.

tags:
  - Text Classification
  - Sentiment Analysis
  - Code-Mixing
  - Dravidian Languages
  - mBERT
  - cmsa

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: 'https://drive.google.com/file/d/1OYN3BvuU7-RIqQzNYZw_LtjCmWeyRYpf/view'
#url_code: 'https://github.com/shreyaghosh-2016/Elephant-movement'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  #focal_point: ''
  #preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - cmsa

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the _Slides_ button to check out the example.
#{{% /callout %}}

#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
