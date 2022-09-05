---
title: 'Creating Disaggregated Network Services with eBPF: the Kubernetes Network Provider Use Case'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Federico Parola
  - Leonardo Di Giovanna
  - Giuseppe Ognibene
  - Fulvio Risso

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2022-06-01T00:00:00Z'
doi: '10.1109/NetSoft54395.2022.9844062'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2022 IEEE 8th International Conference on Network Softwarization (NetSoft)*
publication_short: In *NetSoft 2022*

abstract: 'The eBPF technology enables the creation of custom and highly efficient network services, running in the Linux kernel, tailored to the precise use case under consideration.
However, the most prominent examples of such network services in eBPF follow a monolithic approach, in which all required code is created within the same program block.
This makes the code hard to maintain, to extend, and difficult to reuse in other use cases.
This paper leverages the Polycube framework to demonstrate that a disaggregated approach is feasible also with eBPF, with minimal overhead, introducing a larger degree of code reusability.
This paper considers a complex network scenario, such as a complete network provider for Kubernetes, presenting the resulting architecture and a preliminary performance evaluation.'

# Summary. An optional shortened abstract.
summary: 'The eBPF technology enables the creation of custom and highly efficient network services, running in the Linux kernel, tailored to the precise use case under consideration.
However, the most prominent examples of such network services in eBPF follow a monolithic approach, in which all required code is created within the same program block.
This makes the code hard to maintain, to extend, and difficult to reuse in other use cases.
This paper leverages the Polycube framework to demonstrate that a disaggregated approach is feasible also with eBPF, with minimal overhead, introducing a larger degree of code reusability.
This paper considers a complex network scenario, such as a complete network provider for Kubernetes, presenting the resulting architecture and a preliminary performance evaluation.'

tags: [Kubernetes, eBPF, NFV]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
