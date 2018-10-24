+++

title = "A Parallel Bandit-Based Approach for Autotuning FPGA Compilation"
authors = ["Chang Xu", "Gai Liu", "Ritchie Zhao", "Stephen Yang", "Guojie Luo", "Zhiru Zhang"]
date = "2017-02-22"

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
publication = "Int'l Symp. On Field-Programmable Gate Arrays (FPGA)"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Mainstream FPGA CAD tools provide an extensive collection of optimization options that have a significant impact on the quality of the final design. These options together create an enormous and complex design space that cannot effectively be explored by human effort alone. Instead, we propose to search this parameter space using autotuning, which is a popular approach in the compiler optimization domain. Specifically, we study the effectiveness of applying the multi-armed bandit (MAB) technique to automatically tune the options for a complete FPGA compilation flow from RTL to bitstream, including RTL/logic synthesis, technology mapping, placement, and routing. To mitigate the high runtime cost incurred by the complex FPGA implementation process, we devise an efficient parallelization scheme that enables multiple MAB-based autotuners to explore the design space simultaneously. In particular, we propose a dynamic solution space partitioning and resource allocation technique that intelligently allocates computing resources to promising search regions based on the runtime information of search quality from previous iterations. Experiments on academic and commercial FPGA CAD tools demonstrate promising improvements in quality and convergence rate across a variety of real-life designs."
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
doi = "10.1145/3020078.3021747"
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
