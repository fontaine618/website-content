---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Missing Value Imputation of Network Node Attributes"
event: JSM 2021
event_url: https://ww2.amstat.org/meetings/jsm/2021/onlineprogram/AbstractDetails.cfm?abstractid=318894 
location: online
address:
  street:
  city:
  region:
  postcode:
  country:
summary: 
abstract: User profiles in social networks are notoriously incomplete due to self-reporting; predicting or imputing these missing values is often of paramount importance. While missing value imputation has been widely studied in the context of standard data matrices, the network with node attributes case remains fairly unexplored. In particular, using all available information, observed node attributes and edges, should improve on using only the observed attributes, provided some association between attributes and edges. We propose a novel imputation method based on a joint latent space model that allows information between the network adjacency matrix and node attributes to be shared. Additionally, we propose an extension to non-ignorable missing values by directly modeling the missingness process. Using variational inference, we obtain approximate posteriors for the latent variables enabling predictive distributions for the missing values and further allowing assessment of missingness patterns. Numerical experiments, on both simulated and real-world networks, show that our proposed method improves on multiple imputation using only the nodes attributes.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-08-10T10:00:00-04:00
date_end:  
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2021-10-21T14:20:29-04:00

authors: 
  - simfont
  - Ji Zhu
author_notes:
  - "Presenting"
  - ""
tags: []

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides: naivi-jsm-slides.pdf

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---


