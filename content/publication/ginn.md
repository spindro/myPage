+++
title = "Missing Data Imputation with Adversarially-trained Graph Convolutional Networks"
date = 2020-06-01T00:00:00
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
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Neural Networks, 2020"
publication_short = "Neural Networks, 2020"

# Abstract and optional shortened version.
abstract = "Missing data imputation (MDI) is a fundamental problem in many scientific disciplines. Popular methods for MDI use global statistics computed from the entire data set (e.g., the feature-wise medians), or build predictive models operating independently on every instance. In this paper we propose a more general framework for MDI, leveraging recent work in the field of graph neural networks (GNNs). We formulate the MDI task in terms of a graph denoising autoencoder, where each edge of the graph encodes the similarity between two patterns. A GNN encoder learns to build intermediate representations for each example by interleaving classical projection layers and locally combining information between neighbors, while another decoding GNN learns to reconstruct the full imputed data set from this intermediate embedding. In order to speed-up training and improve the performance, we use a combination of multiple losses, including an adversarial loss implemented with the Wasserstein metric and a gradient penalty. We also explore a few extensions to the basic architecture involving the use of residual connections between layers, and of global statistics computed from the data set to improve the accuracy. On a large experimental evaluation, we show that our method robustly outperforms state-of-the-art approaches for MDI, especially for large percentages of missing values."
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
#tags = ["graph neural networks", "data imputation"]

# Links (optional).
url_pdf = "https://www.sciencedirect.com/science/article/abs/pii/S0893608020302185"
url_preprint = ""
url_code = "https://github.com/spindro/GINN"
url_dataset = ""
url_project = ""
#url_slides = "https://spindro.github.io/files/ginn.pdf"
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
