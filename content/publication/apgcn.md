+++
title = "Adaptive Propagation Graph Convolutional Network"
date = 2020-01-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Indro Spinelli","Simone Scardapane", "Aurelio Uncini"]

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
abstract = "Graph convolutional networks (GCNs) are a family of neural network models that perform inference on graph data by interleaving vertex-wise operations and message-passing exchanges across nodes. Concerning the latter, two key questions arise: (i) how to design a differentiable exchange protocol (e.g., a 1-hop Laplacian smoothing in the original GCN), and (ii) how to characterize the trade-off in complexity with respect to the local updates. In this paper, we show that state-of-the-art results can be achieved by adapting the number of communication steps independently at every node. In particular, we endow each node with a halting unit (inspired by Graves' adaptive computation time) that after every exchange decides whether to continue communicating or not. We show that the proposed adaptive propagation GCN (AP-GCN) achieves superior or similar results to the best proposed models so far on a number of benchmarks, while requiring a small overhead in terms of additional parameters. We also investigate a regularization term to enforce an explicit trade-off between communication and accuracy. The code for the AP-GCN experiments is released as an open-source library."
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
#tags = ["Graph neural network", "graph data", "Machine learning", "Node classification"]

# Links (optional).
url_pdf = "https://arxiv.org/abs/2002.10306"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
# url_slides = "https://spindro.github.io/files/ginn.pdf"
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
