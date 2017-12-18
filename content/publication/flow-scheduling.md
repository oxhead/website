+++
title = "Flow Scheduling: An Efficient Scheduling Method for MapReduce Framework in the Decoupled Architecture"
date = "2014-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Chin-Jung Hsu", "Vincent W. Freeh"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication = "In the Technical Report"
publication_short = "In *TR*"

# Abstract and optional shortened version.
abstract = "Hadoop is a popular implementation of the MapReduce pro- gramming model for data processing. We first compare dif- ferent Hadoop models and discuss their advantages and lim- itation. The traditional Hadoop system is scalable because a machine serves both computation and storage function. However, this principle imposes a strong constraint on sys- tem design and does not quite fit enterprise and cloud appli- cation, which require to decouple computation and storage nodes. Any naive Hadoop implementations may fail to be optimized because they are designed to preserve data local- ity, which does not exist in the decoupled model. In this paper, we propose a flow scheduling method: it eliminates undesired factors that can decrease processing performance. We model the cost of task assignment based on the penalty of violating flow demand and convert this problem to the network optimization problem. We have implemented Flow Scheduler for Hadoop and the experiment results show that it can maximize the processing flow rate while improving the system throughput by up to 30%. More interestingly, our flow scheduling method can provide more smooth task execution time, which suggests it can eliminate stragglers that caused by resource contention."

abstract_short = "The default scheduler in Hadoop is not optimized for I/O intensive applications.  This work proposes a new scheduling method that optimizes I/O and network utilization.  Our method relies on offline profiling and models the scheduling problem as a min-cost flow optimization problem.  Preliminary results show throughput improvement by up to 30%."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_pdf = "files/paper_flow-scheduling.pdf"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
# url_code = "#"
# url_dataset = "#"
# url_project = "#"
# url_slides = "#"
# url_video = "#"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++
