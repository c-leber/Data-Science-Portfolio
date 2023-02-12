# Christopher A Leber, PhD - Data Science Portfolio
Welcome to my data science porfolio! For more information about me, please see [my LinkedIn profile](https://www.linkedin.com/in/christopheraleber/ "Christopher A Leber's LinkedIn profile"). For my publication list, please see [here](https://github.com/c-leber/Data-Science-Portfolio/blob/main/Publications.md "Christopher A Leber's publication list").

#### Guide
- [Current Focus](#current-focus): how my coding time is currently being spent
- [Personal Explorations](#personal-explorations): toy projects for experimenting with techniques and illustrating how I approach problems
- [PhD Projects - Lead](#phd-projects---lead): computationally-driven works core to my PhD dissertation
- [PhD Projects - Contributor](#phd-projects---contributor): collaborative efforts to which I contributed data science acumen
- [Proprietary Projects](#summary-of-proprietary-projects): summaries of data science and development conducted in the service of industry
- [In the Works](#-in-the-works-): where my head is at, and where my mind is going

## Current Focus

### Senior Data Scientist at Shiru
#### supervised + unsupervised learning | data warehouse & ETL | platform development 
Engineering the data and software foundations of a world-class discovery platform for uncovering plant protein ingredients that can sustainably replace animal products in foods.

- Data science and engineering technical leader
- Lead cross-functional projects, balancing agile responsiveness to short-term stakeholder needs and persistent long-term platform development.
- Leverage supervised and unsupervised machine learning to predict protein functions and attributes.
- Conduct statistical analyses on disparate data sets ranging from transcriptomics to food sensory surveys, thoughtfully contending with challenges related to both big data and limited data, sparsity, non-uniform sampling, and other data biases.
- Design and implement a data warehouse, and associated ETL pipelines, comprising hundreds of millions of proteins and hundreds of features and annotations per protein.
- Engineer cloud computing infrastructure for model benchmarking and scaled deployment, interactive data visualization, and laboratory data tools.

## Personal Explorations

### Predicting Cannabis Effects via Smell
#### supervised learning | classification | probablistic imputation | cross-validation | hyperparamater tuning 
Cannabis produces a plethora of interesting chemical compounds, many of which are thought to act synergistically in producing the pharmacological effects associated with specific strains. Here I perform a broad survey of classifiers, with subsequent hyperparameter tuning on top models, to build models that can be used to predict the effects of cannabis strains, using their aromas and flavors as proxies for terpene composition.

- [1. Model Building Report + Code](https://nbviewer.jupyter.org/github/c-leber/Predicting-Cannabis-Effects-via-Smell/blob/main/Code_and_Report.ipynb)
- [1.1 Kernel Building for Binary Data Report + Code](https://nbviewer.jupyter.org/github/c-leber/Predicting-Cannabis-Effects-via-Smell/blob/main/1.1_Kernel_Building_for_Binary_Data.ipynb)

### California Wildfires: Learning from the Past
#### interactive visualization | geospatial data | time series 
Visualizing the past and future of California Wildfires.

- [Shiny App](https://c-leber.shinyapps.io/ca_wildfire_viz "CA Wildfire App")
- [Source Code](https://github.com/c-leber/CA-Wildfire-Visualizations/blob/main/app.R.ipynb)

### COVID-19 School Reopening Tool
#### interactive visualization
Reopening schools safely requires consideration of multiple timeline, including post holiday break quarantine periods and providing an adequate time window for teachers to be vaccinated and reach peak immunity. Herein is an interactive tool for informing policy decisions via visualization of the multi-dimensional problem being solved.

- [Shiny App](https://c-leber.shinyapps.io/covid19_school_reopening "COVID19 School Reopening App")
- [Source Code](https://github.com/c-leber/COVID19-School-Reopening-Tool/blob/main/app.R.ipynb)

## PhD Projects - Lead

### The Objective Relational Comparative Analyses (ORCA) pipeline
#### unsupervised learning | feature selection | metabolomics data processing & data wrangling
A toolkit for processing and performing comparative analyses on MS1 metabolomics data. Also includes auxiliary tool for analyzing clusters of MS2 spectra.

- [Publication](https://pubmed.ncbi.nlm.nih.gov/33066480/ "Leber et al 2020")
- [Code](https://github.com/c-leber/ORCA "ORCA repo")

### The ORCA Expansion
#### unsupervised learning | feature selection | statistical testing | pairwise comparisons & similarity metrics
An expanded toolkit for processing and performing comparative analyses on MS1 metabolomics data, including metadata supervised feature selection, pariwise feature comparisons, and various metrics for measuring chemical compositional similarity.

- [Abstract](https://github.com/c-leber/Data-Science-Portfolio/blob/main/ORCA_expansion_abstract.md) ::manuscript in prep::
- [Code](https://github.com/c-leber/ORCA/tree/Mb_MS_expansion "ORCA repo - Expansion")

### iTerator (iT)
#### bioinformatics | draft genome improvement | pipeline development | data file handling
A bioinformatic pipeline for iterative de novo scaffolding, referenced scaffolding, gap filling, and gap clearing, for improved genome sequence contiguity and increased biosynthetic gene cluster completeness.

- [Abstract](https://github.com/c-leber/Data-Science-Portfolio/blob/main/iTerator_abstract.md) ::manuscript in prep::
- [Code](https://github.com/c-leber/iTerator "iTerator repo")


## PhD Projects - Contributor

### Cryptic Species Account for the Seemingly Idiosyncratic Secondary Metabolism of Sarcophyton glaucum Specimens Collected in Palau
#### unsupervised learning | clustering | supervised learning | metabolomics

- [Publication](https://pubs.acs.org/doi/abs/10.1021/acs.jnatprod.9b01128?casa_token=K7cL2DPrIvwAAAAA:6qoozeZLoiMZZUiN04AOhPmMeIbN6hpfO4yallyBXKuAsdRB9bmwydqFGjRhcznkWnMnqFEvESvEvyw "Cryptic Species Account for the Seemingly Idiosyncratic Secondary Metabolism of Sarcophyton glaucum Specimens Collected in Palau")

### NPClassifier: A Deep Neural Network-Based Structural Classification Tool for Natural Products
#### supervised learning | classification | deep-learning

- [Pre-print](https://chemrxiv.org/articles/preprint/NPClassifier_A_Deep_Neural_Network-Based_Structural_Classification_Tool_for_Natural_Products/12885494/1 "NPClassifier: A Deep Neural Network-Based Structural Classification Tool for Natural Products")

### COVID-19 Computational Screening Pipeline
#### supervised learning | deep-learning

Initiated a collaborative, international effort to prioritize natural products for pharmacological screening against SARS-CoV-2, the virus that causes COVID-19. Curated data, trained, and ensembled [ChemProp](https://github.com/chemprop/chemprop) neural networks to screen *in silico* over 100,000 compounds from a collection of private compound libraries of (mainly) natural products. Top hits were filtered by a team of chemists, and then advanced to molecular modeling. Efforts continue to source top hits and submit them for validation in pharmacological assays.

For my full publication list, please see [here](https://github.com/c-leber/Data-Science-Portfolio/blob/main/Publications.md).

## Summary of Proprietary Projects

### Oracle Water Services
#### deep learning | computer vision | regression | transfer learning

- Developed deep learning computer vision regression models for industrial applications.
- Iterated over models to improve accuracy and generalizability.
- Applied transfer learning and augmentation techniques to extend the utility of small training datasets.

### Sirenas Marine Discovery / Galileo Biosystems
#### platform development | statistical analyses | bias detection & correction | supervised & unsupervised machine learning

- Extended and refactored elements of an expansive, multi-author, multi-language Luigi-based data pipeline integrating a suite of AWS services, multiple Docker images, and relational and graph-based databases, for making predictions from diverse chemical and biological datasets.
- Implemented recursive feature elimination on a high-dimensional dataset, optimized to improve unsupervised learning via a missing-data-tolerant, modified k-NN algorithm.
- Designed ranking algorithms for sample prioritization, with alternative ranking strategies optimized for user goals. 
- Created a QC protocol with robust statistical analyses for high-throughput multivariate assay data, to quantify uncertainty in results.
- Developed parametric and nonparametric workflows for identifying biases in high-throughput screening data, and custom transformations to correct for inter- and intraplate systemic biases. 
- Produced timely reports with data visualization to articulate actionable findings to colleagues.

### Council Brewing
#### clustering | similarity metrics | time series | geospatial data
- Analyzed trends in demand for different beverage market segments.
- Produced geospatial visualizations of brewery tasting room density across San Diego County.
- Assessed brewery similarities across different feature sets.

## :: In the Works ::

### Determining Land Use from Satelite Imagery: Deep Learning Experimental Playground ::on-going::
#### deep learning | convolutional neural networks | remote sensing | multi-label classification | data handling & ETL
[BigEarthNet](http://bigearth.net/ "BigEarthNet") is an archive of remote sensing images multi-labelled for land-use that can be used to train and benchmark deep learning models. This massive resource of 590,326 x 12 band images offers many opportunities for model building, while also presenting substantial challenges for data handling in the limited resource Google Colab/Google Drive environment.

- Overcoming Challenges in Low Resource Data Handling
- Experiments in Deep Learning

### Predicting Cannabis Effects via Smell
#### supervised learning | classification | probablistic imputation | cross-validation | hyperparamater tuning 
Cannabis produces a plethora of interesting chemical compounds, many of which are thought to act synergistically in producing the pharamcological effects associated with specific strains. Here I perform a broad survey of classifiers, with subseuent hyperparameter tuning on top models, to build models that can be used to predict the effects of cannabis strains, using their aromas and flavors as proxies for terpene composition.

- 2.Feature Engineering Deep Dive
