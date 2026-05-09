---
title: 'Decoupling MCI-specific signatures from shared neurobiological substrates of cognitive aging via deep learning'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Biying Peng
  - me

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-04-23T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: In *npj Digital Medicine*
publication_short: In *npj Digital Medicine*

abstract: >-
  The specific neuroanatomy of mild cognitive impairment (MCI) is obscured by its clinical heterogeneity and confounding effects from normative variation. This problem is compounded by the inability of conventional neuroimaging methods to disentangle these overlapping influences. Leveraging data from the Beijing Aging Brain Rejuvenation Initiative (BABRI, n = 918) and the Alzheimer’s Disease Neuroimaging Initiative (ADNI, n = 1293), this study employed a conditional variational autoencoder (CVAE) to: (1) systematically distinguish between aging-related cognitive decline and MCI-specific cognitive impairments; (2) implicitly disentangle latent, unknown confounding effects to identify MCI-specific structural brain alterations; and (3) construct individualized scores for predicting the risk of conversion to Alzheimer’s disease (AD). The CVAE effectively extracted MCI-specific latent features from T1 structural MRI, significantly correlated with episodic memory, attention, and executive function impairments. Reconstructions revealed characteristic deformation in regions including the middle and medial temporal lobes, frontal lobe, limbic system, and cerebellum. The robustness of this structural-cognitive impairment association model established in BABRI dataset was validated in the ADNI dataset. Moreover, predictive modeling using these features achieved superior AD-conversion prediction (AUC = 0.83) versus whole-brain atrophy (AUC = 0.74; p < 0.001) or CSF biomarkers (AUC = 0.77; p < 0.001). This work establishes a novel paradigm for isolating MCI-specific brain alterations from physiological aging.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://www.nature.com/articles/s41746-026-02597-3/"
  # - type: code
  #   url: https://github.com/HugoBlox/kit
  # - type: dataset
  #   url: https://github.com/HugoBlox/kit
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/kit
  # - type: video
  #   url: https://youtube.com

# Featured image: uses `featured.png` in this page bundle.
image:
  caption: ''
  focal_point: Center
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
slides: ""
---
<!-- 
> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example. -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
