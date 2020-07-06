+++
title = "Enabling Energy Efficient Image Encryption using Approximate Memoization"
date = 2019-08-21T21:53:11-05:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Seongmin Hong", "Jaehyung Im", "SM Mazharul Islam", "Jaehee You", "Yongjun Park"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Journal of Semiconductor Technology and Science, Vol.17, No.3, June, 2017"
publication_short = "JSTS, 2017"

# Abstract and optional shortened version.
abstract = "Security  has  become  one  of  the  most important requirements for various devices for multi-sensor based embedded systems. The AES (Advanced Encryption  Standard)  algorithm  is  widely  used  for security, however, it requires high computing power. In  order  to  reduce  the  CPU  power  for  the  data encryption  of  images,  we  propose  a  new  image encryption  module  using  hardware  memoization, which can reuse previously generated data. However, as image pixel data are slightly different each other, the reuse rate of the simple memoization system is low. Therefore, we further apply an approximate concept to the memoization system to have a higher reuse rate by  sacrificing  quality.  With  the  novel  technique,  the throughput can be highly improved by 23.98% with 14.88%  energy  savings  with  image  quality  loss minimization."

abstract_short = "Energy efficient image encryption system."

# Featured image thumbnail (optional)
image_preview = "multi-scale-CNN-for-semantic-segmentation.jpg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Crypto-processor", "Approximation", "Memoization", "AES", "SSIM", "FPGA implementation"]

# Links (optional).
url_pdf = "http://www.jsts.org/html/journal/journal_files/2017/06/Year2017Volume17_03_17.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "http://koreascience.or.kr/article/JAKO201719558339635.page"

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

{{< figure src="/img/jsts_fig.jpg" title="The proposed image encryption using approximate memoization." >}}
