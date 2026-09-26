---
title: 'VOID: Backdoor Injection through Knowledge Vacuity in Federated Unlearning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenwei Zhao
  - Yuxuan Xie
  - Haiyun Liu
  - Jie Xu
  - Zhuo Lu
  

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: "2026-9-24T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-09'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Annual Conference on Neural Information Processing Systems (NeurIPS) 2026
publication_short: Annual Conference on Neural Information Processing Systems (NeurIPS) 2026

abstract: |
  Federated unlearning (FU) enables federated systems to remove designated data from a trained global model, but its security risks remain poorly understood. We show that calibration-based FU introduces a structural vulnerability through finite-step post-hoc corrections, which leave behind \emph{knowledge vacuity} in weakly constrained residual dimensions where the unlearned data's influence is suppressed while retained-task recovery pressure remains limited. We propose VOID, an unlearning-phase backdoor attack that exploits knowledge vacuity to implant trigger semantics along the legitimate unlearning trajectory. VOID identifies these residual dimensions through influence-based trajectory estimation and neuron-level vacuity profiling, then performs masked semantic substitution during unlearning. Across datasets and FU methods, VOID achieves up to 99\% attack success, preserves clean accuracy, and persists after post-unlearning finetuning. Our results show that approximate forgetting can expose writable capacity for adversarial reuse.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/40206'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
