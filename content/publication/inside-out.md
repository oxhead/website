+++
title = "Inside-Out: Reliable Performance Prediction for Distributed Storage Systems in the Cloud"
date = "2016-09-26"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Chin-Jung Hsu", "Rajesh K Panta", "Moo-Ryong Ra", "Vincent W. Freeh"]

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
publication = "In the *35th Symposium on Reliable Distributed Systems*"
publication_short = "In *SRDS*"

# Abstract and optional shortened version.
abstract = "Many storage systems are undergoing a significant shift from dedicated appliance-based model to software-defined storage (SDS) because the latter is flexible, scalable and cost-effective for modern workloads. However, it is challenging to provide a reliable guarantee of end-to-end performance in SDS due to complex software stack, time-varying workload and performance interference among tenants. Therefore, modeling and monitoring the performance of storage systems is critical for ensuring reliable QoS guarantees. Existing approaches such as performance benchmarking and analytical modeling are inadequate because they are not efficient in exploring large configuration space, and cannot support elastic operations and diverse storage services in SDS. <br /><br />This paper presents Inside-Out , an automatic model building tool that creates accurate performance models for distributed storage services. Inside-Out is a black-box approach. It builds high-level performance models by applying machine learning techniques to low-level system performance metrics collected from individual components of the distributed SDS system. Inside-Out uses a two-level learning method that combines two machine learning models to automatically filter irrelevant features, boost prediction accuracy and yield consistent prediction. Our in-depth evaluation shows that Inside-Out is a robust solution that enables SDS to predict end-to-end performance even in challenging conditions, e.g., changes in workload, storage configuration, available cloud resources, size of the distributed storage service, and amount of interference due to multi-tenants. Our experiments show that Inside-Out can predict end-to-end performance with 91.1% accuracy on average. Its prediction accuracy is consistent across diverse storage environments."

abstract_short = "Software-defined storage requires to meet users' performance requirements.  Machine learning techniques are used to create reliable performance models from low-level system metrics collected at runtime.  The accurate performance model enables service providers to provision storage resources in a more fine-grained way."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_pdf = "files/paper_inside-out.pdf"
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
