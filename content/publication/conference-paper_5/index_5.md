---
title: 'TransAnimate: Taming Layer Diffusion to Generate RGBA Video'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xuewei Chen
  - Yiren Song

date: '2025-05-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: In *submission*

abstract: Text-to-video generative models have made remarkable advancements in recent years. However, generating RGBA videos with alpha channels for transparency and visual effects remains a significant challenge due to the scarcity of suitable datasets and the complexity of adapting existing models for this purpose. To address these limitations, we present TransAnimate, an innovative framework that integrates RGBA image generation techniques with video generation modules, enabling the creation of dynamic and transparent videos. TransAnimate efficiently leverages pretrained text-to-transparent image model weights and combines them with temporal models and controllability plugins trained on RGB videos, adapting them for controllable RGBA video generation tasks. Additionally, we introduce an interactive motion-guided control mechanism, where directional arrows define movement and colors adjust scaling,offering precise and intuitive control for designing game effects. To further alleviate data scarcity, we have developed a pipeline for creating an RGBA video dataset, incorporating high-quality game effect videos, extracted foreground objects, and synthetic transparent videos. Comprehensive experiments demonstrate that TransAnimate generates high-quality RGBA videos, establishing it as a practical and effective tool for applications in gaming and visual
effects.

# Summary. An optional shortened abstract.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2503.17934
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

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

---

