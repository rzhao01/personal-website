+++

title = "Area-Efficient Pipelining for FPGA-Targeted High-Level Synthesis"
authors = ["Ritchie Zhao", "Mingxing Tan", "Steve Dai", "Zhiru Zhang"]
date = "2015-06-07"

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
publication = "Design Automation Conference (DAC)"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Traditional techniques for pipeline scheduling in high-level synthesis for FPGAs assume an additive delay model where each operation incurs a pre-characterized delay. While a good approximation for some operation types, this fails to consider technology mapping, where a group of logic operations can be mapped to a single look-up table (LUT) and together incur one LUT worth of delay. We propose an exact formulation of the throughput-constrained, mapping-aware pipeline scheduling problem for FPGA-targeted high-level synthesis with area minimization being a primary objective. By taking this cross-layered approach, our technique is able to mitigate the pessimism inherent in static delay estimates and reduce the usage of LUTs and pipeline registers. Experimental results using our method demonstrate improved resource utilization for a number of logic-intensive, real-life benchmarks compared to a state-of-the-art commercial HLS tool for Xilinx FPGAs."

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
doi = "10.1145/2744769.2744801"
arXiv = ""
url_pdf = ""
url_pdf_rel = "papers/dac2015.pdf"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "slides/pipelining-dac2016.pdf"
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = "dac2015-example.svg"
caption = ""

+++
