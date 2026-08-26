---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV (PDF)](Resume.pdf)

Research profile
================

Interdisciplinary researcher with experience in microbial genomics, antimicrobial resistance,
infectious-disease epidemiology, chemical genomics, microbiological laboratory work, and machine
learning. My research at KAUST focuses on linking bacterial genomic variation to clinically and
biologically important phenotypes using population-genomic, bioinformatic, and interpretable
machine-learning approaches.

Education
=========

* **M.S. Electrical Engineering (Digital Signal and Systems Processing)**, National University of Sciences and Technology, Pakistan, 2017–2020
  * Thesis: *Formal Verification of E-Voting Protocols Using Probabilistic Model Checking*
* **B.E. Electrical Engineering (Electronics)**, Air University, Pakistan, 2013–2017
  * Thesis: *Blind Spot Detection System for Vehicles*

Research experience
===================

**Research Assistant, King Abdullah University of Science and Technology (KAUST)**
March 2024–present

* Analyze bacterial whole-genome sequencing data and AMR profiles using bioinformatics and machine-learning workflows.
* Develop predictive and interpretable models relating genomic variation to bacterial phenotypes and clinical outcomes.
* Contribute to genomic epidemiology and population-level analyses of pathogens including *Klebsiella pneumoniae* and *Staphylococcus aureus*.
* Conduct antimicrobial susceptibility testing and genomic DNA extraction.
* Integrate genomic, clinical, phenotypic, and environmental data for infectious-disease research.
* Support laboratory safety, risk assessment, procurement, and research continuity.

**Remote Researcher, Environmental AI, Pakistan**
June 2023–February 2024

* Applied machine learning, explainable AI, data analysis, and scientific software development to environmental and biomedical research problems.

**Lab Technician, Ulsan National Institute of Science and Technology, South Korea**
June–October 2021 and June–October 2022

* Conducted laboratory experiments to quantify water-quality parameters.

**Teacher, Dot & Line, Pakistan**
May 2020–March 2023

Selected projects
=================

* [Saudi Pathogen Atlas](https://saudipathogenatlas.kaust.edu.sa) — genomic surveillance of clinical and environmental antimicrobial-resistant bacterial isolates in Saudi Arabia.
* [GenoPredict](https://genopredict.kaust.edu.sa) — interpretable, genome-based prediction of clinically relevant outcomes.
* **AI-Assisted Antibiotic Prescription** — comparison of physician decisions and LLM outputs using structured clinical vignettes.

Technical and laboratory skills
===============================

* **Computational:** Python, NumPy, pandas, xarray, Matplotlib, TensorFlow, scikit-learn, XGBoost, LightGBM, CatBoost, Git, and Weights & Biases.
* **Modeling:** neural networks, time-series modeling, genotype-phenotype prediction, model deployment, and large multimodal datasets.
* **Explainable AI:** SHAP, partial dependence, integrated gradients, and attention-based methods.
* **Bioscience:** microbial genomics, bioinformatics, AMR profiling, genomic pattern interpretation, antimicrobial susceptibility testing, and genomic DNA extraction.
* **Laboratory operations:** safety, risk assessment, procurement, and research continuity.

Open-source software
====================

* **AutoTab** — owner; machine-learning pipeline optimization for tabular and time-series data.
* **easy_mpl** — owner; publication-ready scientific visualization utilities.
* **SeqMetrics** — contributor; unified regression and classification metrics for Python.
* **AquaFetch** — contributor; acquisition and harmonization of water-resource datasets.
* **AI4Water** — contributor; data-driven environmental modeling framework.

Awards and languages
====================

* Final Year Project Research Grant, National ICT R&D, Pakistan, 2016.
* English: IELTS 7.0, 2026.

Publications
============

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
