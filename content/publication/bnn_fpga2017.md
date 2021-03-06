+++

title = "Accelerating Binarized Convolutional Neural Networks with Software-Programmable FPGAs"
authors = ["Ritchie Zhao", "Weinan Song", "Wentao Zhang", "Tianwei Xing", "Jeng-Hau Lin", "Mani Srivastava", "Rajesh Gupta", "Zhiru Zhang"]
date = "2017-02-22"

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Int'l Symp. On Field-Programmable Gate Arrays (FPGA)"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Convolutional neural networks (CNN) are the current state-of-the-art for many computer vision tasks. CNNs outperform older methods in accuracy, but require vast amounts of computation and memory. As a result, existing CNN applications are typically run on clusters of CPUs or GPUs. Research on FPGA acceleration of CNN workloads has achieved reductions in power and energy consumption. However, large GPUs outperform modern FPGAs in throughput, and the existence of compatible deep learning frameworks give GPUs a significant advantage in programmability. Recent work in machine learning demonstrates the potential of very low precision CNNs — i.e., CNNs with binarized weights and activations. Such binarized neural networks (BNNs) appear well suited for FPGA implementation, as their dominant computations are bitwise logic operations and their memory requirements are greatly reduced. A combination of low-precision networks and high-level design methodology may help address the performance and productivity gap between FPGAs and GPUs. In this paper, we present the design of a BNN accelerator that is synthesized from C++ to FPGA-targeted Verilog. The accelerator outperforms existing FPGA-based CNN accelerators in GOPS as well as energy and resource efficiency."

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
doi = "10.1145/3020078.3021741"
arXiv = ""
url_pdf = ""
url_pdf_rel = "papers/fpga2017.pdf"
url_code = "https://github.com/cornell-zhang/bnn-fpga"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
