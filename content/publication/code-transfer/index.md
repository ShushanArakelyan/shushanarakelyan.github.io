---
title: "Exploring Distributional Shifts in Large Language Models for Code Analysis"
authors:
- Shushan Arakelyan
- Rocktim Jyoti Das 
- Yi Mao
- Xiang Ren
date: "2023-03-15T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing
publication_short: In *EMNLP'23*


abstract: We systematically study the capacity of two large language models for code - CodeT5 and Codex - to generalize to out-of-domain data. In this study, we consider two fundamental applications - code summarization, and code generation. We split data into domains following its natural boundaries - by an organization, by a project, and by a module within the software project. This makes recognition of in-domain vs out-of-domain data at the time of deployment trivial. We establish that samples from each new domain present both models with a significant challenge of distribution shift. We study how well different established methods can adapt models to better generalize to new domains. Our experiments show that while multitask learning alone is a reasonable baseline, combining it with few-shot finetuning on examples retrieved from training data can achieve very strong performance. In fact, according to our experiments, this solution can outperform direct finetuning for very low-data scenarios. Finally, we consider variations of this approach to create a more broadly applicable method to adapt to multiple domains at once. We find that in the case of code generation, a model adapted to multiple domains simultaneously performs on par with those adapted to each domain individually

tags:
- ml for code
- generelization
featured: yes 

# links:
# - name: Arxiv
#  url: https://arxiv.org/abs/2303.09128
url_pdf: https://arxiv.org/pdf/2303.09128.pdf
url_code: https://github.com/ShushanArakelyan/code_transfer
url_dataset: https://github.com/ShushanArakelyan/code_transfer
url_poster: uploads/EMNLP23-poster.pdf
url_project: https://github.com/ShushanArakelyan/code_transfer
url_slides: uploads/EMNLP23-slides.pdf
url_source: 
url_video: https://www.youtube.com/watch?v=XibHuQliPBc

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [ML for Code, Generalizable Models for Code]
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---