+++

title = "Improving High-Level Synthesis with Decoupled Data Structure Optimization"
authors = ["Ritchie Zhao", "Gai Liu", "Shreesha Srinath", "Christopher Batten", "Zhiru Zhang"]
date = "2016-06-05"

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
abstract = "Existing high-level synthesis (HLS) tools are mostly effective on algorithm-dominated programs that only use primitive data structures such as fixed size arrays and queues. However, many widely used data structures such as priority queues, heaps, and trees feature complex member methods with data-dependent work and irregular memory access patterns. These methods can be inlined to their call sites, but this does not address the aforementioned issues and may further complicate conventional HLS optimizations, resulting in a low-performance hardware implementation. To overcome this deficiency, we propose a novel HLS architectural template in which complex data structures are decoupled from the algorithm using a latency-insensitive interface. This enables overlapped execution of the algorithm and data structure methods, as well as parallel and out-of-order execution of independent methods on multiple decoupled lanes. Experimental results across a variety of real-life benchmarks show our approach is capable of achieving very promising speedups without causing significant area overhead."

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
doi = "10.1145/2897937.2898030"
arXiv = ""
url_pdf = ""
url_pdf_rel = "papers/dac2016.pdf"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "slides/decoupled-dac2016.pdf"
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
