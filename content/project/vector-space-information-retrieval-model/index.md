---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Vector Space Information Retrieval Model"
summary: "Implement a query search system based on Vector Space Model, using TF-IDF weighting and Cosine Similarity concepts for ranking the related documents"
authors: [Ali Miramirkhani]
tags: ["Semantic Web","Information Retrieval","Query","NLP"]
categories: ["Semantic Web"]
date: 2019-05-07T15:22:11+03:30

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/seiiedali/vector-space-information-retrieval-model"

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

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
# vector space information retrieval model
 This text query system uses vector vector space model for indexing extracted tokens from documents.
 ## Indexing
 Tokens will be parsed through each document text and after some cleaning data(punctuation, white spaces), will be index based on vector space model concepts. Tokenized 
 word are stored in a dictionary with information about their repetition and associated document files. Finally tokens are inserted into another dictionary where their weight on TF-IDF scale are assessed. This data are ready to be any query process.
 ## Query
 After parsing the documents, program would ask you to enter a query up to 4 words. Entered query will be processed in the same way that document were parsed. Final result is ranked related documents which are assessed by Cosine Similarity formula based on TF-IDF values.