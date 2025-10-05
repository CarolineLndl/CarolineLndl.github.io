---
title: "Cerebro-spinal somatotopic organization"
authors:
- admin
date: "2024-10-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: In this study, we used simultaneous brain and cervical spinal cord functional magnetic resonance imaging (fMRI) to demonstrate how the coordinated activities of these two CNS levels at rest can reveal their shared somatotopy. These findings underscore the potential of resting-state cerebro-spinal cord fMRI to probe the large-scale organization of the human sensorimotor system with minimal experimental burden, holding promise for gaining a more comprehensive understanding of normal and impaired somatosensory-motor functions.

# Summary. An optional shortened abstract.
summary: In this study, we used simultaneous brain and cervical spinal cord functional magnetic resonance imaging (fMRI) to demonstrate how the coordinated activities of these two CNS levels at rest can reveal their shared somatotopy. These findings underscore the potential of resting-state cerebro-spinal cord fMRI to probe the large-scale organization of the human sensorimotor system with minimal experimental burden, holding promise for gaining a more comprehensive understanding of normal and impaired somatosensory-motor functions.

tags:
- Lastest publications

featured: true

links:
- name: Link
  url: https://doi.org/10.1162/imag_a_00284
url_pdf: 
url_code: 'https://github.com/CarolineLndl/BrainSpineSomatotopy2024'
url_dataset: 
url_poster: 
url_project: 
url_slides: 
url_source: 
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Figure 2'
  focal_point: 0
  preview_only: false
  resize: "100x100"

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

{{ with .Params.image }}
  <figure>
    <img src="{{ .src | relURL }}" alt="Featured Image" style="width: {{ .resize }}">
    <figcaption>{{ .caption }}</figcaption>
  </figure>
{{ end }}