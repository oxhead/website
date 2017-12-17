+++
title = "Low-Level Augmented Bayesian Optimization for Finding the Best Cloud VM"
date = "2017-12-12"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Chin-Jung Hsu", "Vivek Nair", "Vincent W. Freeh", "Tim Menzies"]

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
publication = "In the *38th IEEE International Conference on Distributed Computing Systems* (submitted)"
publication_short = "In *ICDCS* (submitted)"

# Abstract and optional shortened version.
abstract = "With the advent of big data applications, which tends to have longer execution time, choosing the right cloud VM to run these applications has significant performance as well as economic implications. For example, in our large-scale empirical study of 107 different workloads on three popular big data systems, we found that a wrong choice can lead to a 20 times slowdown or an increase in cost by 10 times.<br /><br />Bayesian optimization is a technique for optimizing expensive (black-box) functions. Previous attempts have only used instance- level information (such as # of cores, memory size) which is not sufficient to represent the search space. In this work, we discover that this may lead to the fragility problem—either incurs high search cost or finds only the sub-optimal solution. The central insight of this paper is to use low-level performance information to augment the process of Bayesian Optimization. Our novel low-level augmented Bayesian Optimization is rarely worse than current practices and often performs much better (in 46 of 107 cases). Further, it significantly reduces the search cost in nearly half of our case studies.<br /><br />Based on this work, we conclude that it is often insufficient to use general-purpose off-the-shelf methods for configuring cloud instances without augmenting those methods with essential systems knowledge such as CPU utilization, working memory size and I/O wait time."

abstract_short = "This work identifies the fragility problem in applying Bayesian Optimization in searching for the best cloud configuration.  We propose a low-level augmented Bayesian Optimization method to alleviate the fragility problem.  Based on this work, we conclude that it is often insufficient to use general-purpose off-the-shelf methods for configuring cloud instances without augmenting those methods with essential systems knowledge such as CPU utilization, working memory size and I/O wait time."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_pdf = "files/paper_abo.pdf"
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
