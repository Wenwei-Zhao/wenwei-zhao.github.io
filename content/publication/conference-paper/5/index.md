---
title: 'Adapter-Based Parameter-Efficient Adversarial Training for Enhanced Clean Accuracy'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiaowen Li, Wenwei Zhao, Yao liu, Zhuo Lu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

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
  Adversarial training has emerged as a leading defense against adversarial attacks in deep learning, but suffers from a fundamental robustness-generalization trade-off that can severely degrade clean accuracy. We propose Adapter-based Adversarial Training (Adapter-AT), a novel approach that addresses this critical limitation by leveraging parameter-efficient transfer learning techniques. Our method freezes a clean-trained base model and trains only lightweight adapter modules using adversarial examples, preserving the original clean decision boundaries while adding robustness capabilities. Extensive experiments on MNIST and CIFAR-10 demonstrate that Adapter-AT achieves remarkable clean accuracy improvements of 40.4% and 50.6% respectively compared to standard adversarial training, while maintaining over 98% robustness retention across PGD and AutoAttack evaluations. Our approach requires only 2–3% trainable parameters and provides 73.7% memory reduction as beneficial side effects. These properties make Adapter-AT particularly well-suited for wireless security applications, such as adversarially robust spectrum sensing and signal authentication, where both clean accuracy and computational efficiency are critical constraints. These results establish adapter-based training as an effective solution to the robustness-generalization trade-off, making adversarial training practically viable for applications where clean performance is critical.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://dl.acm.org/doi/pdf/10.1145/3811880.3815103"
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
