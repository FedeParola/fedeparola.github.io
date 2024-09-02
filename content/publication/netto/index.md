---
title: 'Measuring the Cost of the Linux Network Stack in Real-Time'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Davide Miola
  - Fulvio Risso
  - Federico Parola

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2024-06-24T00:00:00Z'
doi: '10.1109/NetSoft60951.2024.10588891'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 2024 IEEE 10th International Conference on Network Softwarization (NetSoft)
publication_short: NetSoft 2024

abstract: 'As network interfaces in the data center get faster and faster, and an increasingly big portion of the services is implemented in software, we must wonder just how much time our servers’ CPUs are spending handling network traffic.
This paper explores the feasibility of measuring the cost of the entire in-kernel network stack in real-time on production systems by relying on the eBPF tracing capabilities instead of utilizing custom logic or kernel patching.
We describe two methods that have been attempted, respectively based on an “exact” instrumentation of the stack and sampling, along with the advantages and defects of each approach.'

# Summary. An optional shortened abstract.
summary: 'As network interfaces in the data center get faster and faster, and an increasingly big portion of the services is implemented in software, we must wonder just how much time our servers’ CPUs are spending handling network traffic.
This paper explores the feasibility of measuring the cost of the entire in-kernel network stack in real-time on production systems by relying on the eBPF tracing capabilities instead of utilizing custom logic or kernel patching.
We describe two methods that have been attempted, respectively based on an “exact” instrumentation of the stack and sampling, along with the advantages and defects of each approach.'

tags: [Linux, Networking, eBPF, Tracing, Observability]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://iris.polito.it/retrieve/0999cf2c-7381-440b-9682-7b6a41fa7848/Measuring%20the%20Cost%20of%20the%20Linux%20Network%20Stack%20in%20Real-Time.pdf'
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
