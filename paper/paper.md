---
title: 'DBCLS BioHackathon 2025 report: Boosting BioRuby Development with AI'
title_short: 'BioHackJP25: Boosting BioRuby Development with AI'
tags:
  - Ruby
  - Bioinformatics
  - Openbio
authors:
  - name: Naohisa Goto
    orcid: 0000-0001-8953-046X
    affiliation: 1
  - name: Kozo Nishida
    orcid: 0000-0001-8501-7319
    affiliation: 2
affiliations:
  - name: Research Institute for Microbial Diseases, The University of Osaka
    index: 1
  - name: RIKEN Center for Biosystems Dynamics Research
    index: 2
date: 20 September 2025
cito-bibliography: paper.bib
event: BH25JP
biohackathon_name: "DBCLS BioHackathon 2025"
biohackathon_url:   "https://2025.biohackathon.org/"
biohackathon_location: "Mie, Japan, 2025"
group: BioRuby-and-Ruby-for-Bioinformatics-with-DevOps-and-AI
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackathon-japan/BH25-bioruby
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
#authors_short: First Author \emph{et al.}
authors_short: Goto and Nishida
---

# Introduction

BioRuby is an open-source software library designed to bring the Ruby programming language into the field of bioinformatics. Alongside sibling projects such as BioPerl, Biopython, and BioJava, it provides a versatile collection of classes and modules that make biological data processing both accessible and reproducible.

At its core, BioRuby supports sequence analysis, genome and proteome data parsing, and interaction with biological databases. It includes parsers for widely used formats such as FASTA, GenBank, and PDB, and provides programmatic access to resources including KEGG, UniProt, and GenBank. The toolkit also implements fundamental algorithms for sequence alignment, translation, and motif discovery. With Ruby’s expressive syntax, BioRuby has proven especially useful for researchers and educators seeking a clear, concise programming environment.

Since its inception in the early 2000s, BioRuby has been a foundational part of the Bio community ecosystem*, supporting open science and enabling collaborations across disciplines. It has served both as a research enabler and as an educational platform, ensuring that Ruby remains a practical language choice for computational biology.

In this article, we also highlight that BioRuby has introduced the latest DevOps practices into its development workflow, ensuring modern maintainability and scalability. Furthermore, the project is rapidly incorporating AI-driven methods to accelerate development speed, making BioRuby one of the first bioinformatics libraries in its ecosystem to experiment with automated code generation, testing, and continuous integration.

## Author information

Information about the authors is given in the [YAML](https://en.wikipedia.org/wiki/YAML) format at the top of this template.
For authors you provide their names, their affiliations, and ideally their [ORCID](https://orcid.org/)
identifier. For affiliations, the [Research Organization Registry](https://ror.org/) (ROR) identifier can be given.
For example, this is the author information for this template:

```yaml
authors:
  - name: Naohisa Goto
    orcid: 0000-0001-8953-046X
    affiliation: 1
  - name: Kozo Nishida
    orcid: 0000-0001-8501-7319
    affiliation: 2
affiliations:
  - name: Research Institute for Microbial Diseases, The University of Osaka
    index: 1
  - name: RIKEN Center for Biosystems Dynamics Research
    ror: 023rffy11
    index: 2
```

# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables

Tables can be added in the following way, though alternatives are possible:

```markdown
Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |
```

This gives:

Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

## Figures

A figure is added with:

```markdown
![Caption for BioHackrXiv logo figure](./biohackrxiv.png)
```

This gives:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

Figures can be scaled by adding the width or height to the Markdown like this:

```markdown
![Caption for BioHackrXiv logo figure](./biohackrxiv.png){ width=50px }
```

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References
