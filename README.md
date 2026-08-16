 # GenAI-Stats-DataScience-Education-HBCU

This repository contains the data, analysis code, reproducibility output, and survey materials associated with the study:

**Perceptions and Utilization of GenAI Tools among Data Science Students and Faculty**

Abeer M. Hasan and Sayed A. Mostafa  
Department of Mathematics & Statistics  
North Carolina A&T State University, Greensboro, NC, USA

## Study Overview

This study examines the use and perceptions of generative artificial intelligence (GenAI) among statistics and data science students and faculty at a Historically Black College or University (HBCU). The study investigates familiarity with GenAI tools, usage patterns, perceived benefits and limitations, AI literacy, subgroup differences, faculty instructional practices, and institutional support needs.

The analyses are based on **119 valid student responses and 14 faculty responses**.

## Publication

Hasan, A. M., & Mostafa, S. A. (2026).  
**Perceptions and Utilization of GenAI Tools among Data Science Students and Faculty.**  
*Journal of Data Science*, 1–17.  
DOI: [10.6339/26-JDS1233](https://doi.org/10.6339/26-JDS1233)

## Repository Structure

### `Data&Code/`

Contains the de-identified analytic data and R/R Markdown files used to reproduce the analyses reported in the manuscript.

The analysis materials include:

- Student survey data preparation and descriptive analyses
- Faculty survey data preparation and descriptive analyses
- Construction of student composite scores
- Confirmatory factor analysis (CFA)
- Reliability analysis using Cronbach's alpha
- Comparisons by academic class level using one-way ANOVA and Tukey HSD
- Comparisons by gender using Welch's two-sample t-test
- Reproduction of Tables 2 and 3
- Reproducibility output generated from the analysis code

### `Survey_Questions/`

Contains the student and faculty survey instruments and related survey documentation used in the study.

### `LICENSE`

Contains the repository license information.

## Reproducing the Analysis

To reproduce the analyses reported in the manuscript:

1. Download or clone this repository.
2. Retain the existing repository folder structure.
3. Use the de-identified data files in `Data&Code/` as the analytic input.
4. Run the R or R Markdown analysis files from the repository using relative file paths.
5. Compare the resulting output with the rendered reproducibility output included in `Data&Code/`.

The composite-score analysis reproduces the confirmatory factor analyses, reliability estimates, and student subgroup comparisons reported in **Tables 2 and 3** of the manuscript.

Because respondents could skip individual survey questions, analytic sample sizes may vary across items, composite scores, and statistical analyses.

## Software and Reproducibility

Analyses were conducted using **R** and **R Markdown**. Required packages are identified in the setup sections of the analysis files.

The reproducibility workflow records the R and package environment used for the final analyses and uses repository-relative file paths to facilitate replication on different systems.

## Relationship to the AI4DS Project

This study is associated with the broader **AI4DS (Artificial Intelligence for Data Science Education)** project, which focuses on the responsible integration of generative AI into statistics and data science education.

For the broader project, related educational activities, and additional AI4DS resources, see:

[AI4DS Project Repository](https://github.com/Nothgisrandom/AI4DS)

This repository serves as the **publication-specific reproducibility archive** for the GenAI student and faculty survey study.

## Citation

If you use the data, code, survey materials, or findings from this repository in scholarly work, please cite the associated publication:

> Hasan, A. M., & Mostafa, S. A. (2026). *Perceptions and Utilization of GenAI Tools among Data Science Students and Faculty*. Journal of Data Science, 1–17. https://doi.org/10.6339/26-JDS1233

## License

This repository is distributed under the **Apache License 2.0**. See the `LICENSE` file for details.

## Contact

**Abeer M. Hasan**  
Department of Mathematics & Statistics  
North Carolina A&T State University  
Greensboro, NC, USA  

Email: [amhasan1@ncat.edu](mailto:amhasan1@ncat.edu)
