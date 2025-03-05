---
title: "TripleA: An Unsupervised Domain Adaptation Framework for Nighttime VRU Detection"
authors:
- admin
- Zhenfeng Shao*
- Jiaming Wang
- Yu Wang
- Yulin Ding
- Gui Cheng

author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2024-04-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Intelligent Transportation Systems.* (Accepted)"
publication_short:

abstract: Detecting vulnerable road users (VRUs) at night presents significant challenges. Numerous methods rely heavily on annotations, yet the low visibility of nighttime images poses difficulties for labeling. To obviate the need for nighttime annotations, unsupervised domain adaptation manifests as a viable solution. However, existing approaches often focus solely on semantic-level domain shifts, neglecting the pixel-level discrepancies due to inherent degradations in the night domain, which can significantly impair machine vision. This oversight limits the effectiveness of nighttime VRU detection. To this end, TripleA, an unsupervised domain adaptation framework is introduced to achieve nighttime VRU detection. Realized through a crucial triple alignment, TripleA first aligns the distributions of the labeled daytime domain with the unlabeled nighttime domain. Then, the degraded image is enhanced in terms of illumination and noise. We present an illumination difference-aware denoising network to address the intractable noise and enable selfsupervised learning through a meticulously designed exchange-recombination strategy, which is integrated into a novel pseudosupervised attention to achieve noise distribution alignment. To further enhance the capabilities of the denoising network under real-world scenarios, we introduce degradation alignment to enforce domain-invariant degradation encoding. Extensive experiments demonstrate that our proposed framework achieves superior performance in nighttime VRU detection without relying on nighttime annotations.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: uploads/TripleA-v2.pdf
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

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
