---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Ad Hoc Monitoring of Vocabulary Shifts over Time"
authors: [Tom Kenter, Melvin Wevers, Pim Huijnen, Maarten de Rijke]
date: 2015-10-18
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-07-25T22:44:42+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "CIKM '15 Proceedings of the 24th ACM International on Conference on Information and Knowledge Management"
publication_short: "CIKM'15"

abstract: "Word meanings change over time. Detecting shifts in meaning for particular words has been the focus of much research recently. We address the complementary problem of monitoring shifts in vocabulary over time. That is, given a small seed set of words, we are interested in monitoring which terms are used over time to refer to the underlying concept denoted by the seed words. In this paper, we propose an algorithm for monitoring shifts in vocabulary over time, given a small set of seed terms. We use distributional semantic methods to infer a series of semantic spaces over time from a large body of time-stamped unstructured textual documents. We construct semantic networks of terms based on their representation in the semantic spaces and use graph-based measures to calculate saliency of terms. Based on the graph-based measures we produce ranked lists of terms that represent the concept underlying the initial seed terms over time as final output. As the task of monitoring shifting vocabularies over time for an ad hoc set of seed words is, to the best of our knowledge, a new one, we construct our own evaluation set. Our main contributions are the introduction of the task of ad hoc monitoring of vocabulary shifts over time, the description of an algorithm for tracking shifting vocabularies over time given a small set of seed words, and a systematic evaluation of results over a substantial period of time (over four decades). Additionally, we make our newly constructed evaluation set publicly available."

# Summary. An optional shortened abstract.
summary: ""

tags: [word embeddings, shico, conceptual history]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dl.acm.org/citation.cfm?id=2806474
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [shico]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
