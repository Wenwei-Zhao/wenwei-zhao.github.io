---
title: "Malicious Forgetting: Backdoor Injection in Active Federated Unlearning and Countermeasure Design"
authors:

- Wenwei Zhao, Yuanzhe Peng, Xiaowen Li, Jie Xu, Yao Liu, Zhuo Lu
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2026-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Conference on Computer Communications"
publication_short: "INFOCOM"

abstract: Federated learning (FL) enables collaborative model training without sharing raw data, but also raises increasing demands for the right to be forgotten. To support data erasure, active federated unlearning (FU) allows clients to actively remove their data's influence from the model. We reveal a critical and overlooked threat: malicious clients can pose as privacy-concerned users requesting to unlearn some of their data, while secretly preparing backdoor attacks during training. We propose FUsion backdoor, a subnetwork-based attack that stealthily constructs a compact backdoor subnetwork from trigger-sensitive units within backdoor-critical layers during training, and rapidly fuses it during the limited rounds of unlearning. FUsion backdoor achieves up to 99\% backdoor success rate across diverse datasets and FU methods. We also develop a detection method that captures directional subspace deviations introduced by coordinated backdoor updates, achieving high attack detection accuracy.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
#url_pdf: https://link.springer.com/chapter/10.1007/978-3-031-53510-9_4
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the #example.
#{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
