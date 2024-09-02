---
title: 'Comparing User Space and In-Kernel Packet Processing for Edge Data Centers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Federico Parola
  - Roberto Procopio
  - Roberto Querio
  - Fulvio Risso

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2023-04-20T00:00:00Z'
doi: '10.1145/3594255.3594257'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: SIGCOMM Computer Communication Review
publication_short: SIGCOMM CCR

abstract: 'With the increased availability of small data centers at the edge of the network, telecommunication operators are massively moving their network functions in the above computing facilities.
However, the high performance provided by commonly used technologies for data plane processing such as DPDK, based on kernel-bypass primitives, comes at the cost of rigid resource partitioning.
This is unsuitable for edge data centers, in which efficiency demands both general-purpose applications and data-plane telco workloads to be executed on the same (shared) physical machines.
In this respect, eBPF/XDP looks a more appealing solution, thanks to its capability to process packets in the kernel, achieving a higher level of integration with non-data plane applications albeit with lower performance than DPDK.
In this paper we leverage the recent introduction of AF\_XDP, an XDP-based technology that allows to efficiently steer packets in user space, to provide a thorough comparison of user space vs in-kernel packet processing in typical scenarios of a data center at the edge of the network.
Our results provide useful insights on how to select and combine these technologies in order to improve overall throughput and optimize resource usage.'

# Summary. An optional shortened abstract.
summary: 'With the increased availability of small data centers at the edge of the network, telecommunication operators are massively moving their network functions in the above computing facilities.
However, the high performance provided by commonly used technologies for data plane processing such as DPDK, based on kernel-bypass primitives, comes at the cost of rigid resource partitioning.
This is unsuitable for edge data centers, in which efficiency demands both general-purpose applications and data-plane telco workloads to be executed on the same (shared) physical machines.
In this respect, eBPF/XDP looks a more appealing solution, thanks to its capability to process packets in the kernel, achieving a higher level of integration with non-data plane applications albeit with lower performance than DPDK.
In this paper we leverage the recent introduction of AF\_XDP, an XDP-based technology that allows to efficiently steer packets in user space, to provide a thorough comparison of user space vs in-kernel packet processing in typical scenarios of a data center at the edge of the network.
Our results provide useful insights on how to select and combine these technologies in order to improve overall throughput and optimize resource usage.'

tags: [Data Plane, XDP, AF_XDP, eBPF, NFV, Linux Kernel]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://iris.polito.it/retrieve/ec3b517c-fb4c-4080-98ea-58fbc03f0030/author_Comparing%20User%20Space%20and%20In%20Kernel%20Packet%20Processing%20for%20Edge%20Data%20Centers.pdf'
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
