---
title: 'Enabling Scalable SFCs in Kubernetes with eBPF-based Cross-Connections'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Francesco Monaco
  - Giuseppe Ognibene
  - Federico Parola
  - Fulvio Risso

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2022-11-14T00:00:00Z'
doi: '10.1109/NFV-SDN56302.2022.9974828'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 2022 IEEE Conference on Network Function Virtualization and Software Defined Networks (NFV-SDN)
publication_short: IEEE NFV-SDN 2022

abstract: 'Service Function Chains (SFCs) are composed of an ordered set of Network Functions (NFs) that provide network services to the handled traffic.
However, traffic is highly variable over time, thus telco operators need to deploy scalable chains that can quickly and easily adapt to the load fluctuations.
Although Kubernetes has already brought benefits in terms of increased scalability and flexibility to general-purpose applications, it is not natively suitable for network workloads since it lacks some functionalities required by network services.
This paper presents a simple, cloud-native architecture that integrates SFCs in Kubernetes, with the aim of seamlessly leveraging cloud-native features such as horizontal autoscaling.
The solution is based on flexible cross-connections, namely logical links that connect adjacent network functions, which can promptly adapt the distribution of the network traffic to the existing network functions in case of scale in/out events affecting the number of NF instances.
The architecture has been validated with an open-source proof-of-concept implementation based on dedicated Kubernetes operators and an eBPF load balancer, demonstrating the feasibility and the efficiency of the proposed approach.'

# Summary. An optional shortened abstract.
summary: 'Service Function Chains (SFCs) are composed of an ordered set of Network Functions (NFs) that provide network services to the handled traffic.
However, traffic is highly variable over time, thus telco operators need to deploy scalable chains that can quickly and easily adapt to the load fluctuations.
Although Kubernetes has already brought benefits in terms of increased scalability and flexibility to general-purpose applications, it is not natively suitable for network workloads since it lacks some functionalities required by network services.
This paper presents a simple, cloud-native architecture that integrates SFCs in Kubernetes, with the aim of seamlessly leveraging cloud-native features such as horizontal autoscaling.
The solution is based on flexible cross-connections, namely logical links that connect adjacent network functions, which can promptly adapt the distribution of the network traffic to the existing network functions in case of scale in/out events affecting the number of NF instances.
The architecture has been validated with an open-source proof-of-concept implementation based on dedicated Kubernetes operators and an eBPF load balancer, demonstrating the feasibility and the efficiency of the proposed approach.'

tags: [Kubernetes, NFV, Service Function Chaining, eBPF]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://iris.polito.it/retrieve/96ee56f4-e44c-486e-826c-658e389b4669/author_Enabling%20Scalable%20SFCs%20in%20Kubernetes%20with%20eBPF-based%20Cross-Connections.pdf'
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
