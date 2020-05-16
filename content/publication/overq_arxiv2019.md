+++

title = "Overwrite Quantization: Opportunistic Outlier Handling for Neural Network Accelerators"
authors = ["Ritchie Zhao", "Christopher De Sa", "Zhiru Zhang"]
date = "2019-10-13"

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
publication = "arxiv preprint"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Outliers in weights and activations pose a key challenge for fixed-point quantization of neural networks. While outliers can be addressed by fine-tuning, this is not practical for machine learning (ML) service providers (e.g., Google, Microsoft) who often receive customers' models without the training data. Specialized hardware for handling outliers can enable low-precision DNNs, but incurs nontrivial area overhead. In this paper, we propose overwrite quantization (OverQ), a novel hardware technique which opportunistically increases bitwidth for outliers by letting them overwrite adjacent values. An FPGA prototype shows OverQ can significantly improve ResNet-18 accuracy at 4 bits while incurring relatively little increase in resource utilization."
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
arXiv = "1910.06909"
url_pdf = ""
url_pdf_rel = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
