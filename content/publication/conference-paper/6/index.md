---
title: 'Consistency-Preserving Logit Shaping for Robust Model Stealing Defense with Applications in Wireless Spectrum Security'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiaowen Li, Wenwei Zhao, Yao liu, Zhuo Lu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'EqualSkip to content
PDF
 contribution'

date: "2026-06-30T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-06'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).zhao2024detecting
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 2026 ACM Workshop on Wireless Security and Machine Learning
publication_short: WiSec-WiseML 2026

abstract: >-
  Model stealing (model extraction) threatens ML-as-a-service APIs by enabling adversaries to reconstruct proprietary models from queried probability outputs, undermining both intellectual property and privacy. We seek a defense that reduces information leakage without harming utility. We introduce Consistency-Preserving Logit Shaping (CPLS), a simple, margin-adaptive perturbation applied to logits that provably preserves the top-1 label while reducing mutual information in released soft labels. CPLS adds deterministic, input-keyed, class-orthogonal noise bounded by a fraction of the decision margin, yielding closed-form argmax invariance and resistance to expectation-over-transformation averaging. CPLS has a wide range of applications, and achieves up to 13.1% relative mutual information reduction with zero accuracy loss and zero flip rate, and degrades surrogate training on both MNIST and CIFAR-10 datasets under standard knowledge distillation protocols. We further evaluate CPLS on a wireless spectrum sensing dataset, demonstrating generalization to non-image domains. These results suggest CPLS offers a practical, theory-backed mechanism for curbing extraction while retaining model utility.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://dl.acm.org/doi/epdf/10.1145/3811880.3815105"
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
