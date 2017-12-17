+++
title = "Trilogy: Data Placement to Improve Performance and Robustness of Cloud Computing"
date = "2017-12-11"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Chin-Jung Hsu", "Vincent W. Freeh", "Flavio Villanustre"]

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
publication = "In the *6th Workshop on Scalable Cloud Data Management*, conjuncted with *2017 IEEE International Conference on Big Data (BIGDATA)*"
publication_short = "In *SCDM*"

# Abstract and optional shortened version.
abstract = "Infrastructure as a Service, one of the most disrup- tive aspects of cloud computing, enables configuring a cluster for each application for each workload. When the workload changes, a cluster will be either underutilized (wasting resources) or unable to meet demand (incurring opportunity costs). Conse- quently, efficient cluster resizing requires proper data replication and placement. Our work reveals that coarse-grain, workload- aware replication addresses over-utilization but cannot resolve under-utilization. With fine-grain partitioning of the dataset, data replication can reduce both under- and over-utilization. In our empirical studies, compared to a na ̈ive uniform data replication a coarse-grain workload-aware replication increases throughput by 81% on a highly-skewed workload. A fine-grain scheme further reaches 166% increase. Furthermore, a surprisingly small increase in granularity is sufficient to obtain most benefits. Evalu- ations also show that maximizing the number of unique partitions per node increases robustness to tolerate workload deviation while minimizing this number reduces storage footprint."

abstract_short = "Data placement is crititcal to performance of cloud computing.  This work examines partition granularity, replication factors and placement strategies.  Our work concludes that the fine-grain, balanced data placement improves systems performance and is more robust to (slightly) workload changes."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_pdf = "files/paper_trilogy.pdf"
# url_preprint = "#"
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
