---
title: 'Hate Content Identification in Code-mixed Social Media Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sukomal Pal

# Author notes (optional)


date: '2024-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['6']

# Publication name and optional abbreviated publication name.
publication: In *Text and Social Media Analytics for Fake News and Hate Speech Detection*
publication_short: In *Chapman and Hall/CRC*

abstract: Social media has witnessed a tremendous boom over the past few years, which has in turn generated vast quantities of user-generated content. Users share their opinions, expressions, and emotions openly on social networking sites. Sometimes, these unabated expressions of feelings and thoughts transcend the limit of decency and lead to swearing, bullying, and character assassination. Harsh and derogatory words are directed toward individuals or groups. Often these acts are termed hate speech. As more and more people gain easy access to the Internet, social media gets flooded with such expressions, comments, and opinions in many diverse languages. It becomes increasingly difficult to police (monitor) such hate speech, especially the posts of multilingual people, which are frequently code-mixed or made up of numerous languages. In order to mitigate the spread of offensive content on social media platforms, the initial step is to detect and identify such textual content. Manually identifying hate speech or bullying in code-mixed languages, if not impossible, is a time-consuming and arduous task. Automating this task involves substantial complications and challenges due to the variety and volume of the data. In a multi-lingual code-mixed environment with multiple languages and scripts, the task becomes even more difficult. This chapter begins with different initiatives and approaches related to the identification of offensive content and hate speech in the English language and then we study their applications on code-mixed data. We evaluate the limitations found in the current state-of-the-art techniques, which demonstrate proficiency in handling text data written in a single language and script. Subsequently, we delve into the challenges associated with processing multi-lingual content. We list down different sources of code-mixed datasets and challenges faced during the processing of the data of multilingual content. We attempt to delineate the timeline with respect to the development of models on hate speech recognition for code-mixed data (with all their advantages, data pre-processing techniques, and limitations), Starting with machine learning (ML) and deep learning (DL) approaches, additional textual representation techniques are increasingly added. We then move on to the multilingual pre-trained models (for example, mBERT, XLMR, MuRIL) for text classification. To corroborate our discussion, we consider a specific dataset (ICHCL 2021, 2022) as a case study for analyzing and identifying hate content from code-mixed online datasets, which are conversational in nature. In addition to considering only single-stand-alone sentences where a sentence holds the context by itself, cases, where previous conversations and the chronology of messages are also taken into account, are discussed. In the end, we discuss the shortcomings of the existing techniques and provide directions for future work.

# Summary. An optional shortened abstract.
# summary: In the midst of the widespread adoption of technology, particularly among younger generations, the increasing prevalence of hate speech online has become a pressing global concern. This research paper aims to address this urgent issue by conducting a thorough investigation into hate speech detection in Hindi-English code-mixed data. Existing research has largely approached hate speech recognition as a text classification problem, focusing on predicting the class of a message based solely on its textual content. Our task, however, delves into the classification of hateful content disseminated through tweets, comments, and replies on Twitter, taking into account the contextual intricacies inherent in social media communication. In this context, contextual nuances play a crucial role in understanding communication dynamics. By employing state-of-the-art deep learning techniques tailored to the unique linguistic characteristics of each language, this research makes a significant contribution to the development of robust and culturally sensitive hate speech detection systems. Such systems are essential for creating safer online environments and promoting cross-cultural understanding.

tags:
  - cm-hate
  - hate

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: 'https://drive.google.com/file/d/1B3ObfDbR1Jjmhj1U7TdgDzV4OFxsHPKS/view'
#url_code: 'https://drive.google.com/drive/u/3/folders/1Qh4IP-8KYrKW6AJQuIvlwHoyu4U2ON2d'


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
  - cm-hate
  - hate

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
