---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Seeing History: The Visual Side of the Digital Turn (Best Paper Award)"
authors: [Melvin Wevers, Thomas Smits, Juliette Lonij, Willem-Jan Faber]
date: 2018-06-08
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-07-26T10:53:36+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "DH Benelux 2018"
publication_short: "DH Benelux 2018"

abstract: "Scholars are increasingly applying computational methods to analyze the visual aspects of large-scale digitized visual datasets. Inspiring examples are the work of Seguin on visual pattern discovery in large databases of paintings and Moretti’s and Impett’s large-scale analysis of body postures in Aby Warburg’s Atlas Mnemosyne. In our paper, we will present two datasets of historical images and accompanying metadata harvested from Dutch digitized newspapers and reflect on ways to improve existing neural networks for historical research. We will discuss how. The sets were produced during two researcher-in-residence projects at the National Library of the Netherlands. The first set (SIAMESET) consists of more than 400,000 advertisements published in two major national newspapers between 1945 and 1995.3 Using the penultimate layer in a Convolutional Neural Network (CNN), 2,048 visual aspects were abstracted from these images, which can be used to group images together. The second dataset (CHRONIC) includes about 313,000 classified images from newspapers published between 1860 and 1922. The images were classified using a pipeline that consists of three classifiers. The first one detects images with faces, the second categorizes images according to eight different categories (buildings, cartoons, chess problems, crowds, logos, schematics, sheet music, and weather reports), and the last one sorts images as either photographs or drawings. We developed two tools to query these datasets. The first tool (SIAMESE) offers exploratory search in the advertisement dataset, which enables users to find images sharing a degree of visual similarity and can be used to detect visual trends in large visual datasets. For example, you can input an advertisement with a particular design, or perhaps a shape or object, and the algorithm then looks for similar images. The second one (CHRONREADER) enables users to find images in the second set by searching for specific (combinations) of visual categories and keywords. For example, images of ‘buildings’ with ‘faces’ and the keyword ‘protest’ in the text. Our paper discusses several challenges and possibilities of computer vision techniques for historical research. Most CNN’s are trained on contemporary materials (ImageNet). As a result, these networks perform well in recognizing the categories of the ImageNet challenge. However, the fact that they were trained on contemporary data can cause problems when working with historical images. For example, detecting bicycles works relatively well because the design of the bicycle has remained more or less similar during the last century, while trains are much more difficult since they have changed significantly over the years. Also, models trained on ImageNet have difficulties detecting objects in illustrations, which are often used in newspapers. They are regularly classified within the uninformative category ‘cartoon.’ In short, we will discuss how to improve these models and argue for the development and benchmarking of datasets with visual historical material."

# Summary. An optional shortened abstract.
summary: ""

tags: [computer vision]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides: "Wevers_Smits_SEEING_HISTORY_small.pdf"
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
