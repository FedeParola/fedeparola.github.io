---
title: 'Providing Telco-oriented Network Services with eBPF: the Case for a 5G Mobile Gateway'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Federico Parola
  - Fulvio Risso
  - Sebastiano Miano

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2021-06-01T00:00:00Z'
doi: '10.1109/NetSoft51509.2021.9492571'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2021 IEEE 7th International Conference on Network Softwarization (NetSoft)*
publication_short: In *NetSoft 2021*

abstract: Although several technologies exist for high-speed data plane processing, such as DPDK, the above technologies require a rigid partitioning of the resources of the system, such as dedicated CPU cores and network interfaces. Unfortunately, this is not always possible when running at the edge of the network, in which a few servers are available in each cluster and a mixture of data and control plane services must coexist on the same hardware. In this respect, eBPF can become a better alternative thanks to its integration in the vanilla Linux kernel, which enables contemporary support for data and control plane services, hence enabling a more efficient usage of the (scarce) computing resources. This paper proposes the first proof-of-concept open-source implementation of a 5G Mobile Gateway based on eBPF/XDP, highlighting the possible challenges (e.g., to create traffic policers, as buffering is not available in eBPF) and the resulting architecture. The result is characterized in terms of performance and scalability and compared with alternative technologies, showing that it outperforms other in-kernel solutions (e.g., Open vSwitch) and is comparable with DPDK-based platforms.

# Summary. An optional shortened abstract.
summary: Although several technologies exist for high-speed data plane processing, such as DPDK, the above technologies require a rigid partitioning of the resources of the system, such as dedicated CPU cores and network interfaces. Unfortunately, this is not always possible when running at the edge of the network, in which a few servers are available in each cluster and a mixture of data and control plane services must coexist on the same hardware. In this respect, eBPF can become a better alternative thanks to its integration in the vanilla Linux kernel, which enables contemporary support for data and control plane services, hence enabling a more efficient usage of the (scarce) computing resources. This paper proposes the first proof-of-concept open-source implementation of a 5G Mobile Gateway based on eBPF/XDP, highlighting the possible challenges (e.g., to create traffic policers, as buffering is not available in eBPF) and the resulting architecture. The result is characterized in terms of performance and scalability and compared with alternative technologies, showing that it outperforms other in-kernel solutions (e.g., Open vSwitch) and is comparable with DPDK-based platforms.

tags: [Network Functions, eBPF, XDP, 5G Mobile Gateway, 5G User Plane Function]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://iris.polito.it/retrieve/e384c433-c8fc-d4b2-e053-9f05fe0a1d67'
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
