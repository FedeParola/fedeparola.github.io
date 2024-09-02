---
title: 'Achieving Linear CPU Scaling in WireGuard with an Efficient Multi-tunnel Architecture'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mirco Barone
  - Davide Miola
  - Federico Parola
  - Fulvio Risso

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2024-07-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Netdev 0x18, THE Technical Conference on Linux Networking
publication_short: Netdev 0x18

abstract: 'Despite widespread adoption, the WireGuard tunneling mechanism available in the Linux kernel is unable to provide high-speed connectivity in a site-to-site setup when routing through a standard single-tunnel configuration.
In fact, its capability to scale with the number of available CPU cores is limited, even in the presence of a software architecture that is intrinsically
parallel.
In this paper we investigate the multi-core scalability properties of WireGuard, identifying current limitations and proposing an improved design that aids effective scaling, reaching a near-linear throughput increase depending on the number of involved CPU cores.
Furthermore, we propose a multi-tunnel approach to parallelize stages of the WireGuard pipeline limited to a single core per tunnel and propose a modified architecture tailored to multi-tunnel support.
This architecture shows an almost 2x performance improvement over a multi-tunnel deployment of vanilla WireGuard, and supports 18x times the throughput of a single tunnel setup on our machines.'

# Summary. An optional shortened abstract.
summary: 'Despite widespread adoption, the WireGuard tunneling mechanism available in the Linux kernel is unable to provide high-speed connectivity in a site-to-site setup when routing through a standard single-tunnel configuration.
In fact, its capability to scale with the number of available CPU cores is limited, even in the presence of a software architecture that is intrinsically
parallel.
In this paper we investigate the multi-core scalability properties of WireGuard, identifying current limitations and proposing an improved design that aids effective scaling, reaching a near-linear throughput increase depending on the number of involved CPU cores.
Furthermore, we propose a multi-tunnel approach to parallelize stages of the WireGuard pipeline limited to a single core per tunnel and propose a modified architecture tailored to multi-tunnel support.
This architecture shows an almost 2x performance improvement over a multi-tunnel deployment of vanilla WireGuard, and supports 18x times the throughput of a single tunnel setup on our machines.'

tags: [WireGuard, Tunneling, Multi-core scalability]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://netdevconf.info/0x18/docs/netdev-0x18-paper23-talk-paper.pdf'
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
