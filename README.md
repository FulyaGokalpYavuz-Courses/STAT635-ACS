# STAT 635 — Advanced Computational Statistics

Course materials and website repository for **STAT 635: Advanced Computational Statistics**, offered by the Department of Statistics at Middle East Technical University (METU).

## Course Overview

This course covers computational methods used in modern statistical analysis, with an emphasis on both the principles behind the methods and their practical implementation.

Topics include exploratory data analysis, numerical computing and optimization, simulation and Monte Carlo methods, resampling methods, Markov Chain Monte Carlo (MCMC), and other computational approaches to statistical inference.

Throughout the semester, students will work with real-world datasets and use computational tools to implement, evaluate, and compare statistical methods.

## Computational Tools

The course primarily uses:

- **R**
- **Python**
- **GitHub**

Students are expected to have prior working knowledge of R, Python, and SQL/relational databases. Open-source software, libraries, documentation, and publicly available computational resources will be used throughout the course.

## Research Project

An important component of the course is an individual research-oriented data analysis project.

Each student will select a research topic of interest, identify an appropriate dataset, formulate a research question, and conduct an independent statistical analysis. Students will develop their work throughout the semester and prepare a research paper based on their analysis.

The goal is to produce a manuscript that, when appropriate, can be further developed for presentation at a scientific conference or submission to a peer-reviewed journal.

## Course Website

This repository contains the source files for the STAT 635 course website, built using [Quarto](https://quarto.org/).

### Preview locally

```bash
quarto preview
```

### Build

```bash
quarto render
```

The rendered website is generated in the `_site/` directory.

## Adding a Week

1. Copy `weeks/_template.qmd` to the corresponding weekly file (e.g., `weeks/week-02.qmd`).
2. Set `title`, `description`, and `order` (the week number).
3. The new page will automatically appear on the Weekly Schedule page.

## Publishing

Push changes to the `main` branch on GitHub. The workflow in `.github/workflows/publish.yml` publishes the website to GitHub Pages.

For the initial setup, run:

```bash
quarto publish gh-pages
```

Then configure GitHub Pages to serve the `gh-pages` branch.

## Instructor

**Fulya Gokalp Yavuz**  
Department of Statistics  
Middle East Technical University (METU)
