# 🥔 ShinyPotato

**ShinyPotato** is an interactive R Shiny application developed by the Laboratoire de Biotechnologie et Biologie Appliquée (CARAH asbl, Belgium) for the exploration of potato SSR genotype data and parentage analysis.

The application provides an intuitive graphical interface for navigating a potato genotype database and performing similarity- and likelihood-based analyses using Jaccard similarity coefficients and LOD scores.

---

## Overview

ShinyPotato was developed to facilitate analytical and routine analyses performed in potato variety characterization and parentage inference.

The application integrates several complementary tools within a single interface, including:

- interactive exploration of potato variety metadata
- pedigree visualization
- parent, offspring and sibling exploration
- Jaccard similarity analysis
- likelihood-based LOD analysis
- combined Jaccard–LOD interpretation
- pairwise LOD computation
- varietal identification for routine analysis
- SSR marker data visualization and statistical analyses

---

## Demonstration video

A short demonstration video illustrating the main features of the application is available in:

📹 **demo/ShinyPotato_demo.mp4**

The video presents:

- launching the standalone application
- dashboard overview
- variety identity cards
- Jaccard and LOD analysis per variety
- detailed Jaccard computation per primer mix
- pairwise LOD analysis
- marker exploration tools

---

## Screenshots

Example screenshots are available in the **screenshots/** directory.

---

## Scientific background

The analytical methods implemented in ShinyPotato are described in:

> *Improving parent identification in plant breeding using combined similarity and likelihood metrics.*

The complete analytical source code is available in the companion repository:

➡️ https://github.com/ale-nir/parent-identification-plant-breeding

The repository contains:

the complete R and Rcpp source code implementing the analytical methods;
detailed documentation for the main functions;
reproducible examples illustrating the workflow presented in the manuscript.

---

## Software availability

ShinyPotato is currently maintained as an internal research application developed at CARAH asbl.

This repository documents the application and provides demonstration material illustrating its main functionalities.

The graphical interface source code is **not publicly distributed**.

---

## Contact and Feedback

Questions, comments and feedback are welcome through the Issues section of this repository.
For scientific questions regarding the application:

© 2026 Alexandra Nirsha - CARAH asbl


This repository is provided for demonstration purposes only.
The ShinyPotato application and its graphical interface remain the property of CARAH asbl and are not distributed through this repository.