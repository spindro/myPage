+++
title = "Distribuited Graph Convolutional Network"
date = 2020-01-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Simone Scardapane", "Indro Spinelli", "Paolo Di Lorenzo"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract and optional shortened version.
abstract = "The aim of this work is to develop a fully-distributed algorithmic framework for training graph convolutional networks (GCNs). The proposed method is able to exploit the meaningful relational structure of the input data, which are collected by a set of agents that communicate over a sparse network topology. After formulating the centralized GCN training problem, we first show how to make inference in a distributed scenario where the underlying data graph is split among different agents. Then, we propose a distributed gradient descent procedure to solve the GCN training problem. The resulting model distributes computation along three lines: during inference, during back-propagation, and during optimization. Convergence to stationary solutions of the GCN training problem is also established under mild conditions. Finally, we propose an optimization criterion to design the communication topology between agents in order to match with the graph describing data relationships. A wide set of numerical results validate our proposal. To the best of our knowledge, this is the first work combining graph convolutional neural networks with distributed optimization."
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
#tags = ["graph neural network", "distributed optimization", "machine learning"]

# Links (optional).
url_pdf = "https://arxiv.org/abs/2007.06281"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
# url_slides = ""
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
#[header]
#image = "mosaic.gif"
#caption = ""

+++
