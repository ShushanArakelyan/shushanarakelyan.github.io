---
title: "An example journal article"
authors:
- Shushan Arakelyan
- Sima Arasteh
- Christophe Hauser
- Erik Kline
- Aram Galstyan
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-05-01T00:00:00Z"
doi: "10.1186/s42400-021-00088-4"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Bin2vec: learning representations of binary executable programs for security tasks"
publication_short: ""

abstract: Tackling binary program analysis problems has traditionally implied manually defining rules and heuristics, a tedious and time consuming task for human analysts. In order to improve automation and scalability, we propose an alternative direction based on distributed representations of binary programs with applicability to a number of downstream tasks. We introduce Bin2vec, a new approach leveraging Graph Convolutional Networks (GCN) along with computational program graphs in order to learn a high dimensional representation of binary executable programs. We demonstrate the versatility of this approach by using our representations to solve two semantically different binary analysis tasks – functional algorithm classification and vulnerability discovery. We compare the proposed approach to our own strong baseline as well as published results, and demonstrate improvement over state-of-the-art methods for both tasks. We evaluated Bin2vec on 49191 binaries for the functional algorithm classification task, and on 30 different CWE-IDs including at least 100 CVE entries each for the vulnerability discovery task. We set a new state-of-the-art result by reducing the classification error by 40\% compared to the source-code based inst2vec approach, while working on binary code. For almost every vulnerability class in our dataset, our prediction accuracy is over 80\% (and over 90\% in multiple classes).

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- ml for binary analysis; binary code representation
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://cybersecurity.springeropen.com/articles/10.1186/s42400-021-00088-4
url_code: 'https://cybersecurity.springeropen.com/articles/10.1186/s42400-021-00088-4'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://docs.google.com/presentation/d/142d7Z-4ffEVBLRuyD5YdHwhNjCHrrqAx/edit?usp=sharing&ouid=100437562451567329044&rtpof=true&sd=true'
url_source: 'https://github.com/usc-isi-bass/binary_analysis'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).