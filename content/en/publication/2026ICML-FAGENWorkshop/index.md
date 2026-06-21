---
title: "CyDRA: Diagnosis-Guided Zero-Shot Prompting for Text-to-Cypher Generation"
authors:
- dayeonshin
- admin
date: "2026-06-22T04:00:00+09:00"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-06-22T04:00:00+09:00"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*[ICML 2026 Workshop - Failure Modes in Agentic AI](https://fagen-workshop.github.io)*"
publication_short: "In *ICML 2026 Workshop on Failure Modes in Agentic AI*"

abstract: |
  Execution accuracy alone is a terminal-score metric: it reveals that an LLM-generated Cypher query is wrong, but not why or in what systematic way. We present CyDRA, a Cypher Diagnostic Rule Alignment framework that operationalizes Text-to-Cypher failure as a taxonomy of 11 structurally grounded error categories covering graph pattern construction, aggregation, deduplication, and return projection, each with deterministic triggering conditions derived from AST-lite comparison against gold queries. This taxonomy serves simultaneously as a trace-level diagnostic and as the input to a mitigation strategy: CyDRA distills offline failure signal into a frozen natural-language prompt policy that requires no retrieved examples. On the CypherBench benchmark across seven held-out graph domains, CyDRA improves execution accuracy by 8.92 percentage points on average over a zero-shot baseline across five LLMs, whereas a documentation-only policy lacking diagnostic evidence yields no consistent gain, offering controlled evidence of both effective and ineffective intervention directions. We offer this framework as a case study in how failure taxonomies with operational definitions can close the loop from trace-level diagnostics to verifiable prompt interventions.

# Summary. An optional shortened abstract.
summary: |
  We present CyDRA, a diagnosis-guided prompting framework that uses a structured taxonomy of Text-to-Cypher failures to improve the reliability of LLM-generated Cypher queries without retrieved examples.

tags:
- [Text-to-Cypher, Graph Databases, Failure Taxonomy, LLM Reliability, Zero-Shot Prompting]

links:
# - name: PDF
#   url: https://arxiv.org/pdf/2506.01994
# - name: Github
#   url: TODO
# - name: arXiv
#   url: https://arxiv.org/abs/2506.01994
- name: openreview
  url: https://openreview.net/attachment?id=0COE7JEI0Y&name=pdf


# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "ICML 2026 Workshop - Failure Modes in Agentic AI: **[Website](https://fagen-workshop.github.io/)**"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
