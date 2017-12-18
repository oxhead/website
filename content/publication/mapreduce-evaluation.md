+++
title = "Evaluation of MapReduce in a large cluster"
date = "2015-06-27"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kamal Kc", "Chin-Jung Hsu", "Vincent W. Freeh"]

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
publication = "In the *IEEE International Conference on Cloud Computing*"
publication_short = "In *CLOUD*"

# Abstract and optional shortened version.
abstract = "MapReduce is a widely used framework that runs large scale data processing applications. However, there are very few systematic studies of MapReduce on large clusters and thus there is a lack of reference for expected behavior or issues while running applications in a large cluster. This paper describes our findings of running applications on Pivotal’sAnalytics Workbench, which consists of a 540-node Hadoop cluster. Our experience sheds light on how applications behave in a large-scale cluster. This paper discusses our experiences in three areas. The first describes scaling behavior of applications as the dataset size increases. The second discusses the appropriate settings for parallelism and overlap of map and reduce tasks. The third area discusses general observations.These areas have not been reported or studied previously. Our findings show that IO-intensive applications do not scale as data size increases and MapReduce applications require different amounts of parallelism and overlap to minimize completion time. Additionally, our observations also highlight the need for appropriate memory allocation for a MapReduce component and the importance of decreasing log file size."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_pdf = "files/paper_mapreduce-evaluation.pdf"
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
