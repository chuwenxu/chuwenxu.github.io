---
title: "Deciphering Transcriptome Complexity via Long-read Sequencing"
authors:
- me
- "Jia Li"
- "Chenxi Yin"
- "Keying Li"
- "Tian Wang"
- "Shiwen Gao"
- "Yue Yu"
- "Cheng Chang"
- "Ye Wang"
- "Guoqing Tong"
- "Liang Gong"
- "Wen Hu"
- "Guoliang Chai"
- "Yilai Han"
- "Qian Qin"
- "Suoqin Jin"
- "Xiufen Zou"
- "Bo Li"
- "Tianyuan Zhang"
- "Ana Conesa"
- "Yunhao Wang"
- "Dingjie Wang"
date: "2019-04-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
# Preprints typically have no formal venue; omit `publication` until the work is accepted.

peer_reviewed: false
open_access: true

abstract: Transcriptomics is moving beyond gene-level quantification toward isoform-resolved interrogation of alternative splicing, transcript structural variation, and repeat-derived transcription. Yet short-read sequencing remains intrinsically limited in accurately reconstructing full-length transcripts and resolving complex repetitive regions, including transposable elements. Recent advances in long-read sequencing, exemplified by Pacific Biosciences (PacBio) and Oxford Nanopore Technologies (ONT), offer a transformative opportunity to directly observe complete RNA molecules and thereby overcome these bottlenecks. However, practical adoption is hindered by demanding library construction and the need to process noisy, fast-evolving long-read data, and the field still lacks a unified resource that guides researchers through the entire experimental and analytical workflow. This review fills that gap by providing a concise, end-to-end, and implementation-oriented roadmap for long-read transcriptomics. We distill the key decisions from platform and library strategy selection to core computational processing and downstream interpretation, and we summarize emerging frontiers and best-practice recommendations. By offering a reusable framework and practical checklists, this guide empowers a broader community to exploit long reads for standardized, reproducible, isoform-level discovery at unprecedented resolution.

# Summary. An optional shortened abstract.
summary: This review provides a concise, end-to-end, and implementation-oriented roadmap for long-read transcriptomics.

tags:
- Transcriptomics
- Long-Read Sequencing
- Bioinformatics
- Transposable Element

featured: true

links:
- type: code
  url: https://github.com/jia10046/LRS_Doc
  icon: brands/github

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "Graphical Abstract"
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

Bridging theoretical transcriptomics with hands-on bioinformatic tool analysis, I took the lead in conceptualizing this review. I synthesized the technical landscape, drafted core sections, and coordinated the manuscript integration across all co-authors.