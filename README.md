# FoodSecurityMY

LaTeX source and submission package for the literature review paper:

> **Food Security Risk Assessment: A Review of GA-ANN and Fuzzy Logic Techniques in Intelligent Systems**
> Sha'elah Mohd Safri¹, Muhd Khairulzaman Abd Kadir¹ *(corresponding author)*, Giovanni Honakoko²
> ¹ Electronics & Electrical Engineering Technologies, Universiti Kuala Lumpur British Malaysian Institute (UniKL BMI)
> ² Polytech Nice Sophia, Université Côte d'Azur
>
> Prepared for submission to **Applied Soft Computing** (Elsevier)

## Abstract

Food security risk assessment evaluates risks to food availability, accessibility, and economic stability by rating the likelihood and severity of adverse events, using indicators such as crop yield, climate variability, and economic growth. This review examines the integration of Genetic Algorithm-Artificial Neural Networks (GA-ANN) and Fuzzy Logic (FL) in food security risk assessment, aiming to propose an integrated GA-ANN-Fuzzy Logic framework enhanced by big data protocols for more comprehensive analysis, better prediction, and more proactive prevention of food security risk. GA-ANN and FL are complementary intelligent-system techniques: the genetic algorithm improves the neural network by identifying the most relevant food security features and independently optimizing parameter values, increasing prediction accuracy, while the ANN identifies patterns and forecasts factors such as crop yield, economic conditions, and supply chain integrity. Fuzzy logic complements both by transforming uncertain information into fuzzy risk categories (e.g., low, moderate, or high risk). To corroborate this potential, the review highlights a fuzzy logic framework that models real-world distribution logistics; by effectively handling imprecise data, the system achieves 90% classification accuracy, outperforming traditional food security risk models across multiple strategies. By analyzing the integration of these intelligent techniques, the paper provides a roadmap for developing more accurate, interpretable, and scalable food security risk assessment systems.

**Keywords:** Food security · Risk assessment · Artificial Neural Networks · Genetic Algorithms · Fuzzy logic · Decision support systems

## Highlights

- Reviews GA-ANN and fuzzy logic synergy for food security risk assessment
- Identifies 20 key challenges across data, modeling, and system deployment
- Highlights the need for climate-resilient and interpretable AI models
- Maps a future roadmap for scalable, real-time decision support systems

## Repository structure

```
FoodSecurityMY/
├── main.tex                                    # Manuscript source (elsarticle class)
├── elsarticle.cls                              # Elsevier journal LaTeX class
├── elsarticle-num.bst                          # Elsevier numbered bibliography style
├── main.pdf                                    # Compiled manuscript
├── figures/                                    # Figures referenced in main.tex (fig01–fig12)
├── graphical_abstract.jpg                      # Graphical abstract image
├── highlights.docx                             # Highlights (journal submission requirement)
├── Cover Letter for Applied Soft Computing.docx # Cover letter accompanying the submission
├── Declaration_of_Competing_Interest.docx      # Competing interests declaration
├── vitae.docx                                  # Author biography / CV
└── main.aux, main.log, main.out,
    main.spl, main.synctex.gz                   # LaTeX build artifacts
```

## Building the manuscript

The manuscript uses the [`elsarticle`](https://www.elsevier.com/researcher/author/policies-and-guidelines/latex-instructions) document class required by Elsevier's *Guide for Authors*, with the `preprint` option and the numbered (Vancouver-style) reference format.

```bash
pdflatex main.tex
pdflatex main.tex   # second pass: resolves references, citations and the table of contents
```

Both `elsarticle.cls` and `elsarticle-num.bst` are included in the repository, so no additional package installation should be required beyond a standard TeX Live / MiKTeX distribution (packages used: `amssymb`, `amsmath`, `graphicx`, `booktabs`, `array`, `longtable`, `url`, `hyperref`, `seqsplit`).

## Status

Manuscript prepared for submission to *Applied Soft Computing* (Elsevier). This repository is used to version the LaTeX source, figures, and accompanying submission documents (cover letter, highlights, competing interest declaration, author vitae).

## Authors

- **Sha'elah Mohd Safri** — UniKL BMI
- **Muhd Khairulzaman Abd Kadir** — UniKL BMI *(corresponding author: khairulzaman@unikl.edu.my)*
- **Giovanni Honakoko** — Polytech Nice Sophia, Université Côte d'Azur
