# Christopher A Leber, PhD - Data Science Portfolio
Welcome to my data science porfolio! For more information about me, please see [my LinkedIn profile](https://www.linkedin.com/in/christopheraleber/ "Christopher A Leber's LinkedIn profile").

## Personal Explorations

### Predicting Cannabis Effects via Smell
#### supervised learning | classification | probablistic imputation | cross-validation | hyperparamater tuning 
Cannabis produces a plethora of interesting chemical compounds, many of which are thought to act synergistically in producing the pharamcological effects associated with specific strains. Here I perform a broad survey of classifiers, with subseuent hyperparameter tuning on top models, to build models that can be used to predict the effects of cannabis strains, using their aromas and flavors as proxies for terpene composition.

- [1. Model Building Report + Code](https://github.com/c-leber/Predicting-Cannabis-Effects-via-Smell/blob/main/Code_and_Report.ipynb)
- 1.1 Classification with Gaussian Processes Report + Code

### Determining Land Use from Satelite Imagery: Deep Learning Experimental Playground ::on-going::
#### deep learning | convolutional neural networks | remote sensing | multi-label classification | data handling
[BigEarthNet](http://bigearth.net/ "BigEarthNet") is an archive of remote sensing images multi-labelled for land-use that can be used to train and benchmark deep learning models. This massive resource of 590,326 x 12 band images offers many opportunities for model building, while also presenting substantial challenges for data handling in the limited resource Google Colab/Google Drive environment.

- Code + Model Leaderboard
- Overcoming Challenges in Low Resource Data Handling

### California Wildfires: Learning from the Past
#### interactive visualization | geospatial data | time series 
Visualizing the past and future of California Wildfires.

- [Shiny App](https://c-leber.shinyapps.io/ca_wildfire_viz "CA Wildfire App")
- Source Code

### COVID-19 School Reopening Tool
#### interactive visualization
Reopening schools safely requires consideration of multiple timeline, including post holiday break quarantine periods and providing an adequate time window for teachers to be vaccinated and reach peak immunity. Herein is an interactive tool for informing policy decisions via visualization of the multi-dimensional problem being solved.

- [Shiny App](https://c-leber.shinyapps.io/covid19_school_reopening "COVID19 School Reopening App")
- Source Code

## PhD Projects - Lead

### The Objective Relational Comparative Analyses (ORCA) pipeline
#### unsupervised learning | clustering | feature selection | metabolomics data processing & data wrangling
A toolkit for processing and performing comparative analyses on MS1 metabolomics data. Also includes auxiliary tool for analyzing clusters of MS2 spectra.

- [Publication](https://pubmed.ncbi.nlm.nih.gov/33066480/ "Leber et al 2020")
- [Code](https://github.com/c-leber/ORCA "ORCA repo")

### The ORCA Expansion
#### unsupervised learning | feature selection & pseudosupervised learning | statistical testing | pairwise comparisons & similarity metrics
An expanded toolkit for processing and performing comparative analyses on MS1 metabolomics data, including metadata supervised feature selection, pariwise feature comparisons, and various metrics for measuring chemical compositional similarity.

- Abstract ::manuscript in prep::
- [Code](https://github.com/c-leber/ORCA/tree/Mb_MS_expansion "ORCA repo - Expansion")

### iTerator (iT)
#### bioinformatics | draft genome improvement | pipeline development | data file handling
A bioinformatic pipeline for iterative de novo scaffolding, referenced scaffolding, gap filling, and gap clearing, for improved genome sequence contiguity and increased biosynthetic gene cluster completeness.

- Abstract ::manuscript in prep::
- [Code](https://github.com/c-leber/iTerator "iTerator repo")


## PhD Projects - Contributor

### Cryptic Species Account for the Seemingly Idiosyncratic Secondary Metabolism of Sarcophyton glaucum Specimens Collected in Palau
#### unsupervised learning | clustering | supervised learning | metabolomics

- [Publication](https://pubs.acs.org/doi/abs/10.1021/acs.jnatprod.9b01128?casa_token=K7cL2DPrIvwAAAAA:6qoozeZLoiMZZUiN04AOhPmMeIbN6hpfO4yallyBXKuAsdRB9bmwydqFGjRhcznkWnMnqFEvESvEvyw "Cryptic Species Account for the Seemingly Idiosyncratic Secondary Metabolism of Sarcophyton glaucum Specimens Collected in Palau")

### NPClassifier: A Deep Neural Network-Based Structural Classification Tool for Natural Products
#### supervised learning | classification | deep-learning

- [Pre-print](https://chemrxiv.org/articles/preprint/NPClassifier_A_Deep_Neural_Network-Based_Structural_Classification_Tool_for_Natural_Products/12885494/1 "NPClassifier: A Deep Neural Network-Based Structural Classification Tool for Natural Products")

## Summary of Proprietary Projects

### Sirenas Marine Discovery / Galileo Biosystems
#### platform development | statistical analyses | bias detection & correction | supervised & unsupervised machine learning

- Extended and refactored elements of an expansive, multi-author, multi-language Luigi-based data pipeline integrating a suite of AWS services, multiple Docker images, and relational and graph-based databases, for making predictions from diverse chemical and biological datasets.
- Implemented recursive feature elimination on a high-dimensional dataset, optimized to improve unsupervised learning via a missing-data-tolerant, modified k-NN algorithm.
- Designed ranking algorithms for sample prioritization, with alternative ranking strategies optimized for user goals. 
- Created a QC protocol with robust statistical analyses for high-throughput multivariate assay data, to quantify uncertainty in results.
- Developed parametric and nonparametric workflows for identifying biases in high-throughput screening data, and custom transformations to correct for inter- and intraplate systemic biases. 
- Produced timely reports with data visualization to articulate actionable findings to colleagues.

### Council Brewing
#### clustering| similarity metrics | time series | geospatial data
- Analyzed trends in demand for different beverage market segments.
- Produced geospatial visualizations of brewery tasting room density across San Diego County.
- Assessed brewery similarities across different feature sets.
