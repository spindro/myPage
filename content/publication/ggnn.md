+++
title = "Efficient data augmentation using graph imputation neural networks"
date = 2019-12-07T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Indro Spinelli","Simone Scardapane", "Michele Scarpiniti", "Aurelio Uncini"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = "WIRN 2019"

# Abstract and optional shortened version.
abstract = "Recently, data augmentation in the semi-supervised regime, where unlabeled data vastly outnumbers labeled data, has received a considerable attention. In this paper, we describe an efficient technique for this task, exploiting a recent framework we proposed for missing data imputation called graph imputation neural network (GINN). The key idea is to leverage both supervised and unsupervised data to build a graph of similarities between points in the dataset. Then, we augment the dataset by severely damaging a few of the nodes (up to 80% of their features), and reconstructing them using a variation of GINN. On several benchmark datasets, we show that our method can obtain significant improvements compared to a fully-supervised model, and we are able to augment the datasets up to a factor of 10x. This points to the power of graph-based neural networks to represent structural affinities in the samples for tasks of data reconstruction and augmentation. "
abstract_short =""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
#tags = ["3D reconstruction", "augmented reality", "computer vision", "image processig", "mapping", "open source", "perception", "robotics", "sensors", "SLAM", "TRADR"]

# Links (optional).
url_pdf = "https://arxiv.org/abs/1906.08502"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "https://spindro.github.io/files/ggnn.pdf"
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "mosaic.gif"
#caption = ""

+++

