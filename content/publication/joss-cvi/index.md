---
title: "ClusterValidityIndices.jl: Batch and Incremental Metrics for Unsupervised Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-07-01T00:00:00Z"
# doi: "https://doi.org/10.1103/PhysRevB.93.100201"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *American Physical Society Physical Review B*
publication_short: In *APS PhysRevB*

abstract: ClusterValidityIndices.jl is a Julia package for evaluating the performance the performance of clustering algorithms without the aid of supervised labels. Cluster Validity Indices (CVI) provide a metric of the over- or under-partitioning of an arbitrary clustering algorithm with only the original data and labels assigned by the clustering algorithm. Furthermore, there exist formulations of every CVI such that they may run incrementally (i.e. Incremental CVIs, or ICVI),streaming alongside the clustering algorithm and producing the same results as in their batch implementations. Using a standard interface, each CVI in this package can be run with any clustering algorithm to produce a metric of that algorithm’s performance in scenarios where explicit supervised labels do not exist, which is extremely useful in real-world applications where that is often the case.

# Summary. An optional shortened abstract.
summary: ClusterValidityIndices.jl is a Julia package for evaluating the performance the performance of clustering algorithms without the aid of supervised labels.

tags: ["Julia", "CVI"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://joss.theoj.org/papers/49689a7f5baf94f5d403a18a73b2d99e'
url_code: 'https://github.com/AP6YC/ClusterValidityIndices.jl'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
