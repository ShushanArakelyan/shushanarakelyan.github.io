---
title: "Bin2vec: learning representations of binary executable programs for security tasks"
authors:
- Shushan Arakelyan
- Sima Arasteh
- Christophe Hauser
- Erik Kline
- Aram Galstyan
date: "2021-05-01T00:00:00Z"
doi: "10.1186/s42400-021-00088-4"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Bin2vec: learning representations of binary executable programs for security tasks"
publication_short: ""

abstract: Tackling binary program analysis problems has traditionally implied manually defining rules and heuristics, a tedious and time consuming task for human analysts. In order to improve automation and scalability, we propose an alternative direction based on distributed representations of binary programs with applicability to a number of downstream tasks. We introduce Bin2vec, a new approach leveraging Graph Convolutional Networks (GCN) along with computational program graphs in order to learn a high dimensional representation of binary executable programs. We demonstrate the versatility of this approach by using our representations to solve two semantically different binary analysis tasks – functional algorithm classification and vulnerability discovery. We compare the proposed approach to our own strong baseline as well as published results, and demonstrate improvement over state-of-the-art methods for both tasks. We evaluated Bin2vec on 49191 binaries for the functional algorithm classification task, and on 30 different CWE-IDs including at least 100 CVE entries each for the vulnerability discovery task. We set a new state-of-the-art result by reducing the classification error by 40\% compared to the source-code based inst2vec approach, while working on binary code. For almost every vulnerability class in our dataset, our prediction accuracy is over 80\% (and over 90\% in multiple classes).

tags:
- ml for code 
- binary analysis
- binary code representation
featured: yes

# links:
# - name: ""
#   url: ""
url_pdf: https://cybersecurity.springeropen.com/articles/10.1186/s42400-021-00088-4
url_code: 'https://github.com/usc-isi-bass/binary_analysis'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://docs.google.com/presentation/d/142d7Z-4ffEVBLRuyD5YdHwhNjCHrrqAx/edit?usp=sharing&ouid=100437562451567329044&rtpof=true&sd=true'
url_source: ''
url_video: assets/media/videos/bin2vec.mp4

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image from a video created by Sima Arasteh for our project! '
  focal_point: "yes"
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [ML for Program Analysis]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: "https://docs.google.com/presentation/d/142d7Z-4ffEVBLRuyD5YdHwhNjCHrrqAx/edit?usp=sharing&ouid=100437562451567329044&rtpof=true&sd=true"
---