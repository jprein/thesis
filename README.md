# Thesis Project

[**⬇️ Download thesis as PDF**](thesis_book/_book/_main.pdf)

This repository contains the framework paper of my cumulative dissertation and its four publications, which are the result of four-and-a-half years as a PhD student at the Comparative Cultural Psychology department at the Max Planck Institute for Evolutionary Anthropology (2020-2023) and the Developmental Psychology department at Leuphana University Lüneburg (2024-2025). Below is the folder structure and a brief description of each component.

![Thesis Logo](figures/diss_logos.svg)

## Folder Structure

```
│
├── figures                 # Logos, plots, etc.
├── papers                  # PDFs of the 4 included publications
├── supplements             # Supplementary material
├── thesis_book             # Files containing the actual writing
│   ├── _book               # Compiled thesis book
│   ├── 01_abstract.Rmd     # Writing of English abstract
│   ├── ...other Rmd files  # Chapter-wise content of thesis
│   ├── acronyms.yml        # Defines acronyms used in thesis
│   ├── index.Rmd           # Title page
│   ├── preamble.tex        # Latex setup & packages
└── └── references.bib      # References
```

## Compiling the thesis

This thesis was written with the help of the bookdown R package (https://bookdown.org). Contents of chapters are stored in separate R Markdown files. In the build process (book bookdown::pdf_book), all files are merged into one complete PDF (\_book > main.pdf) that includes automatic acronyms, contents, and reference lists.
