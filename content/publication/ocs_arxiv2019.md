+++

title = "Improving Neural Network Quantization without Retraining using Outlier Channel Splitting"
authors = ["Ritchie Zhao", "Yuwei Hu", "Jordan Dotzel", "Christopher De Sa", "Zhiru Zhang"]
date = "2019-06-09"

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Booka
# 6 = Book chapter
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "International Conference on Machine Learning (ICML)"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Quantization can improve the execution latency and energy efficiency of neural networks on both commodity GPUs and specialized accelerators. The majority of existing literature focuses on training quantized DNNs, while this work examines the less-studied topic of quantizing a floating-point model without (re)training. DNN weights and activations follow a bell-shaped distribution post-training, while practical hardware uses a linear quantization grid. This leads to challenges in dealing with outliers in the distribution. Prior work has addressed this by clipping the outliers or using specialized hardware. In this work, we propose outlier channel splitting (OCS), which duplicates channels containing outliers, then halves the channel values. The network remains functionally identical, but affected outliers are moved toward the center of the distribution. OCS requires no additional training and works on commodity hardware. Experimental evaluation on ImageNet classification and language modeling shows that OCS can outperform state-of-the-art clipping techniques with only minor overhead."
abstract_short = ""

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = false

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Links (optional)
doi = ""
arXiv = "1901.09504"
url_pdf = "http://proceedings.mlr.press/v97/zhao19c/zhao19c.pdf"
url_pdf_rel = ""
url_code = "https://github.com/cornell-zhang/dnn-quant-ocs"
url_dataset = ""
url_project = ""
url_slides = "https://s3.amazonaws.com/postersession.ai/83213bc7-60a0-4d0e-b47d-6186a03a72a0.pdf"
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
