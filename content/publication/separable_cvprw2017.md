+++

title = "Binarized Convolutional Neural Networks with Separable Filters for Efficient Hardware Acceleration"
authors = ["Jeng-Hau Lin", "Tianwei Xing", "Ritchie Zhao", "Zhiru Zhang", "Mani Srivastava", "Zhuowen Tu", "Rajesh K. Gupta"]
date = "2017-07-21"

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Booka
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Computer Vision and Pattern Recognition Workshops (CVPRW)"
publication_short = ""

# Abstract and optional shortened version.
abstract = "State-of-the-art convolutional neural networks are enormously costly in both compute and memory, demanding massively parallel GPUs for execution. Such networks strain the computational capabilities and energy available to embedded and mobile processing platforms, restricting their use in many important applications. In this paper, we propose BCNN with Separable Filters (BCNNw/SF), which applies Singular Value Decomposition (SVD) on BCNN kernels to further reduce computational and storage complexity. We provide a closed form of the gradient over SVD to calculate the exact gradient with respect to every binarized weight in backward propagation. We verify BCNNw/SF on the MNIST, CIFAR-10, and SVHN datasets, and implement an accelerator for CIFAR10 on FPGA hardware. Our BCNNw/SF accelerator realizes memory savings of 17% and execution time reduction of 31.3% compared to BCNN with only minor accuracy sacrifices."
abstract_short = ""

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = false

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Links (optional)
doi = "10.1109/CVPRW.2017.48"
arXiv = ""
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
