# Generic AI-DLT Enterprise System

This repository contains the publication artifacts for:

> Walter Kurz, Michel Malara, and Velimir Dedić. “Generic AI-DLT Enterprise System: Architecture and methodology for scalable domain adaptation from a unified core framework.” *Swissi AI Journal*, Volume 2025, Article SAIJ-soeptiqyucow.

- Journal record: https://journal.swissi-ai.institute/en/doi/soeptiqyucow
- DOI: `10.5281/zenodo.21901257`
- Full paper: [`paper.pdf`](paper.pdf)
- arXiv source archive: [`arxiv-source.zip`](arxiv-source.zip)
- Extracted LaTeX source: [`source/`](source/)

## Research artifacts

The reproducible publication set comprises the complete LaTeX source, bibliography, included research figures, compiled PDF, and arXiv upload archive.

Included research figures:

- [`source/3-assets/1-User/AI_and_DLT_Enterprise_System.png`](source/3-assets/1-User/AI_and_DLT_Enterprise_System.png)

Bibliographic records are stored at [`source/4-bib/2-bib.bib`](source/4-bib/2-bib.bib).

## Build

A TeX installation with `pdflatex` is required. Run:

```sh
./build.sh
```

The script compiles the paper from the committed source and processed bibliography.

## License

The paper and repository contents are published under the [Creative Commons Attribution 4.0 International License](LICENSE).
