---
title: 'Z-Stack: A High-Performance DPDK-Based Zero-Copy TCP/IP Protocol Stack'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Anvaya B. Narappa
  - Federico Parola
  - Shixiong Qi
  - K. K. Ramakrishnan

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2024-07-10T00:00:00Z'
doi: '10.1109/LANMAN61958.2024.10621881'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 2024 IEEE 30th International Symposium on Local and Metropolitan Area Networks (LANMAN)
publication_short: LANMAN 2024

abstract: 'Data centers require high-performance and efficient networking for fast and reliable communication between applications.
TCP/IP-based networking still plays a dominant role in data center networking to support a wide range of Layer-4 and Layer-7 applications, such as middleboxes and cloud-based microservices.
However, traditional kernel-based TCP/IP stacks face performance challenges due to overheads such as context switching, interrupts, and copying.
We present Z-stack, a high-performance userspace TCP/IP stack with a zero-copy design.
Utilizing DPDK’s Poll Mode Driver, Z-stack bypasses the kernel and moves packets between the NIC and the protocol stack in userspace, eliminating the
overhead associated with kernel-based processing.
Z-stack employs polling-based packet processing that improves performance under high loads, and eliminates receive livelocks compared to interrupt-driven packet processing.
With its zero-copy socket design, Z-stack eliminates copies when moving data between the user application and the protocol stack, which further minimizes
latency and improves throughput.
In addition, Z-stack seamlessly integrates with shared memory processing within the node, eliminating duplicate protocol processing and serialization/deserialization overheads for intra-node communication.
Z-stack uses F-stack as the starting point which integrates the proven TCP/IP stack from FreeBSD, providing a versatile solution for a variety of cloud use cases and improving performance of data center networking.'

# Summary. An optional shortened abstract.
summary: 'Data centers require high-performance and efficient networking for fast and reliable communication between applications.
TCP/IP-based networking still plays a dominant role in data center networking to support a wide range of Layer-4 and Layer-7 applications, such as middleboxes and cloud-based microservices.
However, traditional kernel-based TCP/IP stacks face performance challenges due to overheads such as context switching, interrupts, and copying.
We present Z-stack, a high-performance userspace TCP/IP stack with a zero-copy design.
Utilizing DPDK’s Poll Mode Driver, Z-stack bypasses the kernel and moves packets between the NIC and the protocol stack in userspace, eliminating the
overhead associated with kernel-based processing.
Z-stack employs polling-based packet processing that improves performance under high loads, and eliminates receive livelocks compared to interrupt-driven packet processing.
With its zero-copy socket design, Z-stack eliminates copies when moving data between the user application and the protocol stack, which further minimizes
latency and improves throughput.
In addition, Z-stack seamlessly integrates with shared memory processing within the node, eliminating duplicate protocol processing and serialization/deserialization overheads for intra-node communication.
Z-stack uses F-stack as the starting point which integrates the proven TCP/IP stack from FreeBSD, providing a versatile solution for a variety of cloud use cases and improving performance of data center networking.'

tags: [DPDK, zero-copy, TCP/IP protocol stack, shared memory]

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
