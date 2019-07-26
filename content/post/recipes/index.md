---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Working on Historical Recipes"
subtitle: ""
summary: "The last few weeks, I continued work started during the HackaLOD 2018. We extracted recipes from the Allerhande website and used this data to build a method for extracting historical recipes from digitized newspapers."
authors: []
tags: [machine learning, recipes]
categories: []
date: 2018-04-19
lastmod: 2019-07-26T10:32:17+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
Historical newspapers provide a lens on customs and habits of the past. For example, recipes published in newspapers highlight what and how we ate and thought about food. The challenge here is that newspaper data is often unstructured and highly varied, digitized historical newspapers add an additional challenge, namely that of fluctuations in OCR quality. Therefore, it is difficult to locate and extract recipes from them.

After constructing a dataset of recipes using simple query terms, I trained a text classifier based on this dataset. This classifier is able to recognize recipes in historical recipes with an accuracy of 0.96. I then trained a tag classifier based on the Allerhande dataset to automatically tag recipes. Marieke and I also used the ingredients from the Allerhande set to extract ingredient information.
Using Allerhande data as a lexicon to identity ingredients in historical recipes. More on this research and the resulting dataset soon.