# Machine Learning Beyond the Cleveland Dataset: Cross-Cohort Coronary Disease Prediction using Expanded Clinical Features

### ADS503 - Applied Predictive Modeling

### Team 1

# Installation

To get started with this project, please clone the repository into your local machine using the commands below:

```{bash}
> git clone https://github.com/gw-00/ads503_project_g1.git  
> cd ads503_project_g1
```

# Contributors

-   [Graham Ward](https://github.com/gw-00)
-   [Darren Chen](https://github.com/darrencheninfo)
-   [Jun Clemente](https://github.com/junclemente)

# Methods

-   Pre-processing
-   Exploratory Data Analysis
-   Data visualization
-   Statistical Modeling and Machine Learning
    -   Logistic Regression
    -   Random Forest
    -   PLS Discriminant Analysis
    -   k-Nearest Neighbors
    -   Penalized Regression
        -   Lasso Penalization
        -   Ridge Penalization
        -   Elastic Net Model

# Technologies

-   RStudio
-   Quarto
-   R
-   Generative AI
    -   ChatGPT

# Abstract

The goal of this study was to develop a predictive model for identifying coronary heart disease using patient data from four different medical centers around the globe. Leveraging a complete 76-feature heart disease data set from the UCI Machine Learning Repository, records from the Veterans Administration in Long Beach, the Hungarian Insititute of Cardiology, the University Hospital in Zurich, and the Cleveland Clinic underwent merging, pre-processing, and then underwent rigorous modeling. A comprehensive exploratory data analysis (EDA), data cleaning process, and imputation procedures were performed to handle extensive missing values and features with high correlations to avoid impacting model performance and minimizing the amount of bias and variance the models produce. Multiple classification models were developed to include Logistic Regression, Random Forest, Partial Least Squares Discriminant Analysis (PLS-DA), K-Nearest Neighbors (KNN), Penalized Logistic Regression (Lasso, Ridge, and ElasticNet).

# Problem Statement

Previously, predictive model development for coronary heart disease has focused on simplified data sets of 14 features and typically have centered around performing the work on just the Cleveland subset of data. These previous approaches offer the benefit of accessibility and a complete data set for modeling purposes but omit 62 potential valuable predictor information from the entire data set.

## Goal

Enhance predictive accuracy of coronary heart disease by employing a richer and detailed feature set, which will lead to improved performance metrics across the multiple classification machine learning algorithms developed

## Non-goals

1.  Individual Health Tracking: Data collected will not involve personally identifiable health data.
2.  Medical or Clinical Recommendations: Medical treatments, vaccination protocols, or individual health intervention will not be prescribed or evaluated.

# Data Sources

- UCI Irvine Machine Learning Repository - Heart Disease

  - <https://archive.ics.uci.edu/dataset/45/heart+disease>

# Acknowledgements

Portions of this codebase and documentation were developed with assistance from Generative AI, ChatGPT (OpenAI), June 2025.

# References

-   Andras Janosi, W. S. (1989). Heart Disease [Dataset]. UCI Machine Learning Repository. <https://doi.org/10.24432/C52P4X>
-   Cesare, M. D., Perel, P., Taylor, S., Kabudula, C., Bixby, H., Gaziano, T. A., McGhie, D. V., Mwangi, J., Pervan, B., Narula, J., Pineiro, D., & Pinto, F. J. (2024). The Heart of the World. Global Heart, 19(1). <https://doi.org/10.5334/gh.1288>
-   Detrano, R., Janosi, A., Steinbrunn, W., Pfisterer, M., Schmid, J.-J., Sandhu, S., Guppy, K. H., Lee, S., & Froelicher, V. (1989). International application of a new probability algorithm for the diagnosis of coronary artery disease. The American Journal of Cardiology, 64(5), 304–310. [https://doi.org/10.1016/0002-9149(89)90524-9](https://doi.org/10.1016/0002-9149(89)90524-9){.uri}
-   More than half of U.S. adults don’t know heart disease is leading cause of death, despite 100-year reign. (n.d.). American Heart Association. Retrieved June 18, 2025, from <https://newsroom.heart.org/news/more-than-half-of-u-s-adults-dont-know-heart-disease-is-leading-cause-of-death-despite-100-year-reign>
-   Rehman, I., Kerndt, C. C., & Rehman, A. (2025). Anatomy, Thorax, Heart Left Anterior Descending (LAD) Artery. In StatPearls. StatPearls Publishing. <http://www.ncbi.nlm.nih.gov/books/NBK482375/>
-   The top 10 causes of death. (n.d.). Retrieved June 18, 2025, from <https://www.who.int/news-room/fact-sheets/detail/the-top-10-causes-of-death>

# Presentations and Projects

1.  Project Presentation:
2.  Project Slides:
3.  Document Link:
4.  Project Repo: <https://github.com/gw-00/ads503_project_g1>
